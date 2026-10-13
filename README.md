# The Composing Room

Hand composition in 12-point type, from a California job case into the stick.

The Composing Room simulates setting type by hand the way a nineteenth-century compositor did: picking sorts from a job case into a composing stick, spacing out and justifying each line to the measure, dumping lines onto the galley, pulling a proof, correcting it, and distributing the type back into the case. It is built for a touch screen, and it is meant to be a pleasure to work, not a punishment. It is one web page. There is nothing to install and no server.

**Use it:** https://drmarsden.github.io/composing-room/

Or download `index.html` from this repository and open it in any current browser.

## What it does

- **A California job case** in roman, italic and black letter, laid out as the real case was: lower case in the two left bays, capitals on the right with J and U after Z, ligatures, figures, and spaces from the em quad down to brass and copper thins. Each box holds a finite number of sorts, so a case can run out.
- **A composing stick** that shows the type as the compositor saw it, upside down and left to right, with a right-reading aid for beginners. It reports how much of the measure is left, and whether a line is tight, loose or overfull.
- **Justifying.** Step along the line, lift a space out, and put a wider or thinner one in until the line is tight. Short last lines can be quadded out, and long verse lines can be turned over with an indented runover, as Whitman's long lines had to be.
- **The galley and the proof.** Dumped lines stand on the galley. Pull a proof and have it read against the copy: errors are marked in the margin with proofreader's marks. Tap a line on the galley to take it back into the stick and correct it.
- **Distribution.** Return the type to the case all at once, or by hand, sort by sort, which drills the lay of the case. An optional setting lets a missed sort foul the case, to turn up later in someone's line.
- **A tutor.** Ab Tolliver, a journeyman printer, walks a beginner through the work, and "Watch the foreman" shows a whole job done with every tap visible. His remarks can be turned off.
- **Copy to set:** the opening of the 1855 *Leaves of Grass*, Franklin's epitaph for himself, or your own text.
- **Into Sigla.** "Copy text" copies the galley as plain text, ready to paste into [Sigla](https://github.com/DrMarsden/sigla) as a witness, so students can collate what they set against the copy.

Measure (16, 20 or 24 picas), leading, sound, and "hide the lay" (work from memory) are set at the top of the page. A keyboard also works: letters set sorts, the space bar sets a 3-em space, Backspace lifts out, Enter dumps the line.

## Limits

- Widths of sorts are measured from a digital typeface (IM Fell English), not from a historical font of metal type.
- The case is one compositor's California job case, with two thin-space boxes added for convenience. The work stops at the galley proof: there is no imposition and no press.
- There is a box for the opening quotation mark; the closing one is set as two apostrophes, as compositors often did.

## How it was made

The Composing Room was written in October 2026 by Claude, an AI model made by Anthropic, in conversation with Steve Marsden. Marsden supplied the purpose and judged the results; he did not write the code.

## Privacy

Work in progress is kept in your browser's own storage on your device. Nothing is sent to a server. The page requests its typefaces from Google Fonts.

## Citing

Marsden, Steve, and Claude. *The Composing Room*. 2026. https://drmarsden.github.io/composing-room/

## Related tools

- [Sigla](https://github.com/DrMarsden/sigla), a collator for the witnesses of a text.
- [Revision Slider](https://github.com/DrMarsden/revision-slider), which plays a Sigla collation version by version.
- [Core Elements](https://github.com/DrMarsden/core-elements), an MLA 9 citation trainer.

All are collected at https://tinyurl.com/drmarsden.

## Licence

MIT. See `LICENSE`.

## Contact

Steve Marsden, Stephen F. Austin State University. dr.marsden@gmail.com
