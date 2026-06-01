# Product Requirements

## MVP Scope

Build a native macOS app that displays a compact always-available island for live music playback. The MVP should show current media metadata, playback state, subtle live animation, and basic controls while proving the product can run smoothly in the background.

The product should compete with paid notch and Dynamic Island utilities such as Alcove by offering a cleaner first-run experience, lower price, and a focused music-first MVP that still has an obvious path toward richer live activities.

## Functional Requirements

### Island Shell

- The app must display a borderless floating island near the top center of the primary display.
- The island must support collapsed and expanded states.
- The island must avoid blocking normal menu bar usage where possible.
- The island must preserve position across display changes and full-screen app transitions where macOS permits.
- The island must expose preferences for launch at login, visibility, and animation intensity.

### Music Activity

- The app must read current Now Playing metadata from macOS-supported sources where available.
- The island must show track title, artist, artwork when available, and playback state.
- The island must animate subtly while audio is playing and settle when paused.
- The expanded state must expose play/pause and previous/next controls where the source supports remote commands.
- The app must handle missing artwork, unavailable metadata, and stopped playback gracefully.

### Interaction

- The user must be able to click the collapsed island to expand it.
- The expanded island must collapse automatically after inactivity.
- Controls must be keyboard and accessibility friendly.
- The user must be able to quit the app from a menu bar item or settings surface.

### Activity Model

- The app must define a shared Live Activity interface for modules.
- The music module must be implemented through that interface.
- The activity model must support priority, compact content, expanded content, animation state, and lifecycle events.
- Only one activity module is required for MVP, but the architecture must not hardcode music into the island shell.

### Commercial Requirements

- The app must support a simple one-time purchase model for the initial release.
- The target public price should be below Alcove and similar polished paid alternatives.
- The app should include a free trial or free limited mode so users can evaluate animation quality and resource usage before paying.
- The first paid version must feel complete for music use, not like a placeholder for future modules.
- Future modules may justify paid upgrades, but the MVP should avoid subscriptions.

## Non-Functional Requirements

- Build as a native macOS app using Swift and SwiftUI unless implementation findings show a platform blocker.
- Prefer system frameworks over embedded web views for the core shell.
- Keep idle CPU near zero when metadata is unchanged.
- Avoid continuous timers when playback is paused or no activity is visible.
- Use Instruments during implementation to validate CPU, memory, animation, and energy behavior.
- Keep visuals minimal, high contrast, and readable in light and dark mode.
- Use separated product documents and lifecycle tracking per `DOC-NAME-*`, `DOC-STRUCT-*`, and `WORK-*` process rules.

## MVP Exclusions

- AirDrop activity implementation.
- Download manager implementation.
- Plugin marketplace or third-party SDK.
- Cross-device sync.
- Custom media library management.
- Windows or Linux support.
- Subscription billing.
