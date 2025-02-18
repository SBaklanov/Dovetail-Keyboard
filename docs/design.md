# Design

## Design Requirements

### Must have

* Have a full ANSI 104 key set.
* Narrow keyboard profile, similar to tenkeyless.
* Profile should be ergonomic, with sloped key sections to avoid wrist strain.
* Ortholinear or staggered layout.
* Per-key backlight.

### Good to have

* OpenRGB-compatible RGB backlight.

## Design Considerations

### Software

1. QMK
    * Widely adopted in both commercial and hobby projects.
    * LED Matrix support.
    * Compatible with OpenRGB.
    * Bigger community.
1. ZMK
    * More modern option.
    * Embraces board/shield separation.
    * Optimized for ProMicro-compatible wireless boards.
    * Does not support LED matrix.

Winner: QMK.

### Architecture

1. Shield/Board
    * Readily-available solutions.
    * Easy wireless implementation.
    * No-brainer controller and USB implementation.
1. Single board
    * Solid and flat.
    * More pain.
    * More fun!

Winner: Single board.
