# Architecture

## Stack

- App platform: native macOS.
- Language: Swift.
- UI: SwiftUI with AppKit interop for custom floating window behavior.
- Media integration: macOS Now Playing and remote command APIs where available, with AppleScript or app-specific adapters only if necessary.
- Persistence: UserDefaults for MVP preferences; lightweight local store only if future activity history requires it.
- Profiling: Xcode Instruments for CPU, memory, animation, and energy validation.

## Architectural Style

Use a small shell plus activity modules:

- app-shell
- island-window
- live-activity-core
- music-activity
- preferences
- diagnostics

The island shell owns placement, expansion, animation orchestration, and input routing. Activity modules own domain-specific state and commands.

## Core Boundaries

- `LiveActivity` defines module identity, priority, display state, compact view model, expanded view model, and supported commands.
- `ActivityCoordinator` selects the currently visible activity and handles transitions.
- `IslandWindowController` manages floating window level, display changes, hit testing, and full-screen behavior.
- `IslandViewModel` maps the active activity into UI state.
- `MusicActivityProvider` reads media metadata and playback state.
- `AnimationPolicy` applies user preference and power-aware animation settings.

## Resource Strategy

- Prefer event-driven metadata updates over polling.
- Use polling only when a media source lacks reliable events, and back off aggressively.
- Stop live animations when playback is paused, app is hidden, or reduced motion is enabled.
- Avoid expensive blur or artwork processing on every frame.
- Cache artwork-derived colors instead of recomputing during animation.

## Technical Risks

- macOS may limit access to Now Playing metadata or controls for some media apps.
- Floating windows can behave differently across full-screen spaces and multiple displays.
- Always-on animation can affect battery life if not carefully bounded.
- App Store review may scrutinize private APIs, so MVP should avoid them.

## Decision Records Needed

- ADR-0001: Native SwiftUI and AppKit shell versus Electron or Tauri.
- ADR-0002: Now Playing metadata strategy and fallback adapters.
- ADR-0003: Window placement behavior across menu bar, notch, spaces, and displays.
