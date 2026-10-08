# Devadot

Devadot is an 8-bit inspired Devanagari pixel typeface unleashing the power of quirky Indic typefaces. Designed by Saurav Harsh, it supports both Devanagari and Latin scripts.

## License

Devadot is licensed under the SIL Open Font License, Version 1.1. See [OFL.txt](OFL.txt) for the full license text.

## Repository structure

- `sources/` — Glyphs source file and build configuration
- `fonts/ttf/`, `fonts/otf/`, `fonts/webfonts/` — built fonts
- `documentation/` — specimen image

## Building

Install the build dependencies and run the build in one command:

```sh
pip install -r requirements.txt
gftools builder sources/config.yaml
```

This regenerates the fonts in `fonts/ttf/`, `fonts/otf/`, and `fonts/webfonts/` from the Glyphs source.
