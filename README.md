
# Caprasimo

Caprasimo is a DocRepair font, intended to improve compliance with the ISO/IEC 29500 standard by providing fallback that minimizes text reflow in Office Open XML documents. Caprasimo is based on Fraunces, a display, old-style soft-serif typeface inspired by the mannerisms of early 20th century typefaces such as the Cooper Series. Fraunces was designed by Phaedra Charles and Flavia Zimbardi, partners at Undercase Type.

## About

Based on [Fraunces](https://github.com/undercasetype/Fraunces) 

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://docrepair-fonts.github.io/dr-sheldon-fonts.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
