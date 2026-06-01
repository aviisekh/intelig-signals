# Design

## Experience Direction

The island should feel like a quiet system surface, not a dashboard. The default state is compact and information-dense: artwork hint, track identity, and a small live motion signal. The expanded state adds controls and slightly richer metadata, then returns to compact mode.

Alcove sets a useful quality reference for native feel and minimalism. This product should push further on clarity: fewer distracting surfaces, stronger typography, cleaner first-run setup, and a richer but still restrained music presentation.

## Layout

### Collapsed State

- Width: content-aware with a conservative minimum.
- Height: compact enough to sit below or near the menu bar without becoming a banner.
- Content: small artwork thumbnail or fallback glyph, track title, playback indicator.
- Motion: subtle waveform, equalizer bars, or artwork glow only while playing.

### Expanded State

- Content: artwork, title, artist, playback controls, optional progress.
- Controls: previous, play/pause, next, and a settings affordance if needed.
- Behavior: expand from the compact island using spring-like motion and collapse after inactivity.

## Visual Style

- Use native materials or carefully tuned translucent surfaces.
- Keep corners and shadows restrained.
- Avoid large gradients, decorative blobs, or heavy visual effects.
- Support light mode, dark mode, and high contrast accessibility settings.
- Make typography compact and readable; long track names should truncate cleanly.

## Interaction States

- Idle: island hidden or minimized when no useful activity exists, depending on user preference.
- Playing: compact visible with subtle live animation.
- Paused: compact visible with static state.
- Expanded: controls visible and animation slightly more expressive.
- Error or unavailable: show a neutral fallback without alarming language.

## Future Activity Patterns

- AirDrop: show sender, file count, progress, accept or dismiss when supported.
- Downloads: show file name, progress, pause or reveal action.
- Timers: show countdown and quick stop or extend controls.
- Meetings or calls: show mute, camera, and elapsed time if integrations allow.

Every future module should use the same compact-to-expanded model so the product stays predictable.

## Differentiation

- Cleaner onboarding: no long setup flow before the island becomes useful.
- Richer music feel: artwork-aware visuals, subtle live animation, and strong fallback states.
- Lower visual noise: avoid turning the island into a tray of unrelated utilities.
- Better value: price below premium competitors while preserving a polished native experience.
