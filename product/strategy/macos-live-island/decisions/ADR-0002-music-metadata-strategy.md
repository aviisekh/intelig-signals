# ADR-0002: Music Metadata Strategy

## Status

Proposed

## Context

The MVP depends on showing current music metadata, artwork, playback state, and basic controls. macOS media metadata availability can vary across Apple Music, Spotify, browsers, and other media apps.

## Decision

Start with public macOS media and remote command capabilities where available. Validate source behavior before committing to app-specific adapters. Avoid private APIs for the MVP.

## Rationale

- Public APIs reduce review and compatibility risk.
- A source validation spike will reveal whether Apple Music, Spotify, and browser playback can share one provider.
- App-specific fallbacks can be added later if they are necessary and stable.
- Private APIs may work temporarily but are risky for distribution.

## Validation Plan

- Test Apple Music metadata and playback commands.
- Test Spotify metadata and playback commands.
- Test browser media playback from Safari and Chrome.
- Record which sources provide title, artist, artwork, duration, progress, and remote command support.

## Consequences

- The first prototype may have uneven source support.
- The PRD must document source limitations clearly before release.
- Music provider code should be isolated so fallback adapters can be added without changing the island shell.
