![Introduction banner: a single blank scroll tag turned toward old slanted light by a hand at the frame edge, mosaic tesserae on a tally tray and long obelisk shadows on a courtyard wall behind it, abacus beads on their frame farther off, no lettering anywhere](intro-banner.png)

# dm-data-rounding-masker

Chronicle entry, the season of the ships' return: the name above is set in Cantarell in ming blue, in the hand of a chronicle entry, and the scroll tag below is drawn small beside this first heading only. The remaining headings keep the chronicle dress without the tag.

![Logo: a blank scroll tag with a cord hole at its head, a folded foot, and one cinnabar seal dot](logo.png)

![Banner](banner.png)

![Animated scene: the copying room in three bands, courtyard wall and sweeping obelisk shadow above, copying desks with sliding tesserae counters and a wax tablet in the middle, the borrowing desk with a turning scroll tag below](scene.svg)

![Major separator: a wax tablet stylus writing and smoothing, with seal rings](sep-heavy.svg)

# dm-data-rounding-masker
Rounds numerical data to a specified precision. Masks the original data granularity and adds a layer of obfuscation. - Focused on Tools designed to generate or mask sensitive data with realistic-looking but meaningless values

> Chronicle entry: Rounding is performed to a specified precision.

> Chronicle entry: A small random value may be added before rounding.

![Major separator: a wax tablet stylus writing and smoothing, with seal rings](sep-heavy.svg)

## Install
`git clone https://github.com/ShadowGuard-AI/dm-data-rounding-masker`

> Ledger note, corrected in this wave: the clone line formerly spelled the organisation without its hyphen; it now reads ShadowGuard-AI.

![Minor separator: a short centred stylus line](sep-light.svg)

## Usage
`python3 main.py [INPUT_DATA] [options]`

The invocation is shown as a shape and no more than a shape. The source publishes no worked call, no input file name, and no column name, and none is invented here.

![Minor separator: a short centred stylus line](sep-light.svg)

## Parameters
- `input_data`: Numerical data to round (single number or comma-separated list). Optional; if not provided, reads from stdin.
- `-h`: Show help message and exit
- `-p`, `--precision`: Number of decimal places to round to. Defaults to 0.
- `-r`, `--randomize`: Add a small random value before rounding.
- `-m`, `--multiplier`: Multiplier to apply to the number before rounding. Defaults to 1.0.
- `-v`, `--verbose`: Enable verbose logging.

> Chronicle entry, corrected in this wave: two controls formerly carried no description; -p and -m now carry their parser meanings and defaults.

> Chronicle entry, corrected in this wave: the clone line formerly spelled the organisation without its hyphen; it now reads ShadowGuard-AI.

The controls -p and -m formerly carried no description in the source; both are now described in the parameter list above, with -p default 0 and -m default 1.0. The source never states a unit or scale beyond decimal places for -p, and none is invented here.

![Minor separator: a short centred stylus line](sep-light.svg)

## License
This project is released under the license in the [LICENSE](LICENSE) file. See LICENSE for details.

The closing line above is corrected in this wave to point at LICENSE; the organisation spelling there now carries its hyphen.

![Major separator: a wax tablet stylus writing and smoothing, with seal rings](sep-heavy.svg)

## Kept at the copying room desk

The main button of this re-skin reads Round the Figures. Its precision field label reads Kept Precision. Its nudge toggle label reads Nudge Before Rounding. Its logging heading reads Verbose Logging. To round to a specified precision is to declare how much fineness a figure may keep; everything finer than that declaration is surrendered by design, so a reader of the output learns the neighbourhood of a value without recovering its exact address within it. The copy goes out into the world. The original granularity stays home. The record closes on the scroll tag in lamplight, its face blank, its seal dot uppermost.
