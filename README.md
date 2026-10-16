# The Other Doors

A companion text for **HOH 2080 Holistic Health, Wellness and Medicine**,
Vermont State University Online.

**Read it here:** https://kashee12345.github.io/hoh2080-companion-text/

Seven chapters, roughly 62,000 words, 29 figures. Written to be read in place
of a purchased textbook and free to students.

## What it covers

| Chapter | |
| --- | --- |
| 1 | What Counts as Medicine |
| 2 | How American Medicine Became Dominant |
| 3 | The Hands On Traditions |
| 4 | Mind and Body |
| 5 | Whole Systems |
| 6 | Nature, Place and Daily Life |
| 7 | Telling Them Apart |

## How it is built

`index.html` is the whole book: one self contained file with the text, the
styles and all 29 figures inlined as SVG. Nothing is loaded from anywhere
else, so it works offline and will not break when a CDN moves.

Every figure is click through: a figure with `data-steps` walks the reader
through its own argument one stage at a time. Figures use `currentColor` and
CSS custom properties, so they follow the page theme rather than fighting it.

`print.html` is the same content laid out for printing or for generating a PDF.

## A note on the sourcing

Every statistic in this book traces to a source that was retrieved and read,
not recalled. Where a figure would have made a sentence more impressive but
had not been checked, the sentence was written without it, and the book says
so. Each chapter ends with a section called **Where the evidence runs out**
that states plainly what the author does not know.

Chapter 3 covers the author's own clinical field and opens by saying so.

## Author

Vidya Aggrawal, D.C. Vermont State University.

## License

CC BY-NC-SA 4.0. See LICENSE.
