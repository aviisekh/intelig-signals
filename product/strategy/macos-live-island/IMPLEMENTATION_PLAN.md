# Implementation Plan

## Phase 1: Product Foundation

- Finalize product name and target macOS version.
- Validate public API access for music metadata and remote commands.
- Create ADRs for app stack, metadata strategy, and window placement.
- Define the MVP interaction contract for compact and expanded island states.

## Phase 2: Native App Shell

- Scaffold a SwiftUI macOS app.
- Add an AppKit-backed borderless floating window.
- Implement top-center placement, display change handling, and basic preferences.
- Add launch-at-login support if appropriate for MVP.

## Phase 3: Live Activity Core

- Define `LiveActivity`, activity state, priority, commands, and view models.
- Build `ActivityCoordinator`.
- Connect the island shell to activity state without music-specific assumptions.
- Add diagnostics for frame rate, update frequency, and animation mode.

## Phase 4: Music MVP

- Implement `MusicActivityProvider` for current Now Playing metadata.
- Add artwork, title, artist, playback state, and fallback UI.
- Add play/pause, previous, and next commands where supported.
- Build compact and expanded island states.

## Phase 5: Motion and Polish

- Add subtle playing animation with reduced motion support.
- Tune expansion, collapse, hover, and control transitions.
- Validate truncation, light mode, dark mode, and high contrast.
- Add preference controls for visibility and animation intensity.

## Phase 6: Verification

- Profile idle, playing, paused, and expanded states with Instruments.
- Validate behavior across primary display, external display, and full-screen apps.
- Test with Apple Music, Spotify, browser playback, and missing metadata cases.
- Document known platform limitations and fallback behavior.

## Four-Week MVP Target

- Week 1: API validation, ADRs, app shell, floating window prototype.
- Week 2: activity core, music metadata pipeline, compact island.
- Week 3: expanded controls, animation policy, preferences.
- Week 4: profiling, multi-display polish, accessibility, release candidate.
