# Vision

The product becomes a lightweight live activity layer for macOS: a small, beautiful island near the top of the screen that expands only when useful, animates with restraint, and gives users immediate context for music and other transient system activities.

## Product Positioning

A minimal, premium-feeling macOS live activity island for music first, extensible to system workflows later, priced to feel easier to buy than current polished paid alternatives.

## Market Reference

Alcove is the clearest inspiration point: a paid Dynamic Island-style macOS app with strong native feel, smooth animation, and a focused interpretation of Apple's iPhone pattern. This product should learn from that quality bar while competing on cleaner scope, better affordability, and a richer future activity model.

The goal is not to copy Alcove feature-for-feature. The goal is to build a calmer, more accessible, better-priced alternative that feels equally polished and becomes more useful over time.

## Primary Users

- Focused Mac user: wants glanceable music context without opening Spotify, Apple Music, or a browser tab.
- Creator or developer: spends long sessions on Mac and values ambient feedback that does not interrupt flow.
- Power user: wants future live surfaces for AirDrop, downloads, timers, calls, and meetings from one consistent interaction model.

## Success Criteria

- A user can see the current track and playback state at a glance.
- The island can expand for controls and collapse back without visual jank.
- The app remains idle-efficient when music metadata is unchanged.
- The MVP works with Apple Music and system Now Playing metadata where macOS allows it.
- New activity modules can be added without rewriting the island shell.

## Product Principles

- Ambient, not attention-seeking: the island should communicate state without demanding action.
- Native macOS feel: use platform APIs, window behaviors, accessibility expectations, and system materials where appropriate.
- Low resource by default: polling, animations, and rendering must have strict budgets.
- Extension-ready core: music is the first module, not a hardcoded product boundary.
- Tasteful motion: animation should make state legible, not decorative.
- Affordable premium: pricing should feel like an easy utility purchase, not a high-consideration app.
