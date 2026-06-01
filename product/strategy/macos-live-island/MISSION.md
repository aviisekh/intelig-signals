# Mission

Mac users have rich system activity happening all day, but the menu bar and notification center are either too small, too noisy, or too interruptive. Music playback is a good first use case: users want to glance at the current track, feel that playback is alive, and control it without opening a full app.

This product exists to create a minimal, smooth, low-resource macOS island that makes live activity feel present without stealing attention. The first version focuses on music because it gives the product an emotionally clear, visually rich, and technically bounded MVP. The architecture should leave room for future modules such as AirDrop progress, timers, downloads, calls, meetings, and device handoff.

## Problem

- macOS has no native Dynamic Island-style surface for ambient live activity.
- Menu bar music indicators are often too static or hidden behind clicks.
- Full notification banners are disruptive for state that changes continuously.
- Existing always-on overlays can feel heavy, visually noisy, or battery hungry.
- Future live activities need a common interaction model instead of one-off widgets.

## Mission Outcomes

- Deliver a calm, polished macOS island for current media playback.
- Keep CPU, memory, and energy usage low enough for all-day background use.
- Build animation primitives that feel smooth at 60 FPS without unnecessary work.
- Establish a plugin-like activity model for future live sections.
- Manage product strategy, scope, status, and implementation through Intelig Signals.

## Non-Goals

- This is not a full media player replacement.
- This is not a notification center clone.
- This is not an iPhone Dynamic Island copy; it should feel native to macOS.
- This is not a broad plugin marketplace in the MVP.
