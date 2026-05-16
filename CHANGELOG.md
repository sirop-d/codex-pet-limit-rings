# Changelog

Notable changes to `codex-pet-limit-rings` are recorded here.

## Unreleased

### Added

- Per-pet ring color controls for the outer and inner rings, available from the menu-bar `Ring Colors` menu.
- Separate preset and macOS `Custom...` colors for each ring, saved per selected Codex pet.
- Always-visible bottom reset readouts for the short-window and weekly limits.

### Changed

- Bottom readouts now use a two-line layout: remaining percentage on top and reset countdown below.
- Bottom readout capsules size from their text, then both capsules match the wider one so the pair stays visually balanced.
- Bottom readouts sit closer to the ring while leaving a small gap so they do not collide with ring strokes.
- Rings now follow pet drags from the live Codex overlay window at drag-time, reducing visible lag when moving the pet.

### Fixed

- Cross-display pet drags bridge brief live-overlay coordinate gaps from the mouse-to-pet offset instead of waiting for persisted pet state to catch up.
