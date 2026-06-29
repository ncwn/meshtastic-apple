# meshtastic-apple (SELFCIUS fork)

> This is a fork of `meshtastic/Meshtastic-Apple` on the `selfcius/main` branch.
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

## SELFCIUS Status

- No SELFCIUS Apple app features are implemented yet in this fork.
- Do not infer mobile support from firmware, relay, or TTN bench evidence. Treat SELFCIUS phase evidence as bench validation unless a gate document explicitly says field/mobile validation.
- When SELFCIUS Apple work starts, keep changes on `v4`, document each fork change in **V4 Modifications**, and coordinate protobuf changes only through the wrapper-level protobuf escalation policy.

## Rules

- Always merge upstream, **never rebase selfcius/main**
- Update the V4 Modifications section below when changing files
- Feature work goes on branches off selfcius/main, merged back to selfcius/main
- After pushing selfcius/main, update the wrapper repo submodule SHA
- Do not describe SELFCIUS mobile features as implemented until source code exists in this fork

## V4 Modifications

<!-- When you modify a file, add an entry here:

### path/to/File.swift
- **What:** Brief description of the change
- **Why:** Reason this modification is needed for SELFCIUS
- **Conflict risk:** Low / Medium / High when merging upstream
-->

### CLAUDE.md
- **What:** Added SELFCIUS status guidance clarifying that no Apple app features are implemented yet and that firmware bench evidence must not be described as mobile validation.
- **Why:** Future agents need accurate scope boundaries before planning or reporting SELFCIUS mobile work.
- **Conflict risk:** Low - documentation-only fork guidance.
- **What:** Renamed the tracked integration branch from `v4` to `selfcius/main` for handoff clarity.
- **Why:** Future intERLab-AIT maintainers need project-specific branch names rather than the old wrapper-era `v4` label.
- **Conflict risk:** Low - branch guidance only; the old `v4` branch remains as a temporary fallback.

### New Files

<!-- Files added that don't exist in upstream -->

_None yet._

### Deleted Files

<!-- Upstream files removed intentionally -->

_None yet._
