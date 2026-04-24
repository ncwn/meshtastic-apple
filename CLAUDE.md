# meshtastic-apple (v4 fork)

> This is a fork of `meshtastic/Meshtastic-Apple` on the `v4` branch.
> When merging upstream releases, consult the V4 Modifications section
> to understand which conflicts are expected vs accidental.

## Upstream Base

- **Tag:** Current
- **Commit:** 24a7270e50937b284ed6d1bc5fa5d00c7246bca1
- **Channel:** stable
- **Upstream repo:** meshtastic/Meshtastic-Apple
- **Fork repo:** ncwn/meshtastic-apple

## Build

- Xcode / Swift Package Manager project
- Open `Meshtastic.xcodeproj` in Xcode
- Build: Cmd+B or `xcodebuild -scheme Meshtastic`
- See project settings for minimum iOS/macOS deployment targets

## Rules

- Always merge upstream, **never rebase v4**
- Update the V4 Modifications section below when changing files
- Feature work goes on branches off v4, merged back to v4
- After pushing v4, update the wrapper repo submodule SHA

## V4 Modifications

<!-- When you modify a file, add an entry here:

### path/to/File.swift
- **What:** Brief description of the change
- **Why:** Reason this modification is needed for the v4 project
- **Conflict risk:** Low / Medium / High when merging upstream
-->

_No modifications yet — v4 branch starts clean from upstream base._

### New Files

<!-- Files added that don't exist in upstream -->

_None yet._

### Deleted Files

<!-- Upstream files removed intentionally -->

_None yet._
