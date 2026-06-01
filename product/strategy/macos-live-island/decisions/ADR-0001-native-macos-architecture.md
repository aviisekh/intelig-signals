# ADR-0001: Native macOS Architecture

## Status

Proposed

## Context

The product needs to feel native, animate smoothly, and use minimal system resources. It also needs deep control over floating window behavior around the menu bar, notch, full-screen spaces, and multiple displays.

## Decision

Use Swift and SwiftUI for the app UI, with AppKit interop for custom borderless floating window behavior.

## Rationale

- Native frameworks give the best chance of low idle resource usage.
- SwiftUI is suitable for compact reactive island surfaces and preferences.
- AppKit is still necessary for precise window level, placement, hit testing, and display behavior.
- Electron would add unnecessary memory and energy overhead for an always-running utility.
- Tauri is lighter than Electron, but still adds a web layer that is not needed for this MVP.

## Consequences

- Development requires Xcode and macOS-specific implementation.
- Some UI work may need hybrid SwiftUI and AppKit patterns.
- Future plugin support should be designed carefully so it does not compromise native performance.
