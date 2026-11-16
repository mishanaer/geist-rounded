# Geist Rounded

A softer take on [Geist](https://github.com/vercel/geist-font), the typeface Vercel designed for developers and designers. Geist Rounded keeps its proportions, rhythm and character set, with rounded corners and stroke endings.

An independent, fan-made font. Not an official Vercel release.

[Try the font](https://mishanaer.com/ui/geist-rounded) · [Download fonts](https://github.com/mishanaer/geist-rounded/releases/latest)

## About the font

Each corner is rounded in proportion to the stroke it belongs to. Stroke ends turn into half circles, apexes into a single arc, and dots into true circles. Inner corners and counters stay crisp, so letters keep their shape at small sizes.

The result is quiet at Thin, where it reads almost as sharp as Geist, and friendly at Black, where the rounding carries the whole word.

Spacing and kerning are based on Geist, with tighter spacing for diagonal letters such as ж, к and x in heavier weights.

## Features

- Variable weight axis from 100 to 900.
- Nine static weights, from Thin to Black.
- 975 glyphs, including Latin and Cyrillic characters.
- 11 stylistic sets, inherited from Geist.
- TTF files for desktop use and WOFF2 files for the web.
- Upright styles only; this release does not include italics.

## Download and install

Download `GeistRounded-1.000.zip` from the [latest release](https://github.com/mishanaer/geist-rounded/releases/latest) and extract it.

For desktop apps, open `variable/GeistRounded[wght].ttf` and install it through your operating system's font manager. It contains the full weight range in one file.

If an app requires separate font files, install the weights you need from `static/` instead.

| Weight | Style |
| --- | --- |
| 100 | Thin |
| 200 | ExtraLight |
| 300 | Light |
| 400 | Regular |
| 500 | Medium |
| 600 | SemiBold |
| 700 | Bold |
| 800 | ExtraBold |
| 900 | Black |

## Use on the web

Copy `webfonts/GeistRounded[wght].woff2` into your project's font directory and load it with `@font-face`. Adjust the URL to match your project:

```css
@font-face {
  font-family: "Geist Rounded";
  src: url("./fonts/GeistRounded[wght].woff2") format("woff2");
  font-weight: 100 900;
  font-style: normal;
  font-display: swap;
}

body {
  font-family: "Geist Rounded", sans-serif;
}
```

The `webfonts/` directory also contains a separate WOFF2 file for each static weight.

## Files

- `variable/` — variable TTF, weights 100–900.
- `static/` — nine individual TTF weights.
- `webfonts/` — variable and static WOFF2 files.
- `OFL.txt` — license and copyright notices.

This repository distributes the font files. The interactive specimen is available at [mishanaer.com/ui/geist-rounded](https://mishanaer.com/ui/geist-rounded).

## License and credits

Geist Rounded is based on [Geist by Vercel](https://github.com/vercel/geist-font) and distributed under the [SIL Open Font License 1.1](OFL.txt). It is free to use, including in commercial projects, subject to that license.

Copyright 2024 The Geist Project Authors. Copyright 2026 Geist Rounded modifications (rounded corners).
