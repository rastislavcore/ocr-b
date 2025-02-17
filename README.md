# OCR-B Monospace Font

OCR-B is a monospace font originally developed in 1968 by Adrian Frutiger. This distribution brings many improvements. Extremely useful for documents in Eastern-European countries.

## Development

The font source is in UFO format, which can be opened and modified using font editors like:

- [FontForge](https://fontforge.org)
- [Glyphs](https://glyphsapp.com)
- [RoboFont](https://robofont.com)

To modify the font:

1. Install a UFO-compatible font editor
2. Open the `OCR-B.ufo` folder in your editor
3. Make your changes and export the font files

## Distribution Files

All compiled font files are located in the `dist` folder:

- `OCR-B.ttf` - TrueType font
- `OCR-B.otf` - OpenType font

Css file is in the `implementation` folder:

- `ocrb.css` - CSS for web usage

## CDN

CSS import of the latest version

```css
@font-face {
  font-family: "OCR-B";
  src: url(https://cdn.jsdelivr.net/gh/rastislavcore/ocr-b/dist/OCR-B.ttf) format("truetype"),
       url(https://cdn.jsdelivr.net/gh/rastislavcore/ocr-b/dist/OCR-B.otf) format("opentype");
}
```

CSS with Minor updates and patch fixes within a major version

```css
@font-face {
  font-family: "OCR-B";
  src: url(https://cdn.jsdelivr.net/gh/rastislavcore/ocr-b@1/dist/OCR-B.ttf) format("truetype"),
       url(https://cdn.jsdelivr.net/gh/rastislavcore/ocr-b@1/dist/OCR-B.otf) format("opentype");
}
```

Using SRI with exact version

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/rastislavcore/ocr-b@1.2/dist/ocrb.css" integrity="sha384-{hash}" crossorigin="anonymous" />
```

> Please, replace {hash} with hash generated for chosen specific version. You can use for example this [SRI Hash Generator](https://www.srihash.org/).

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1. See the [LICENSE](LICENSE) file for full details.

## Funding

If you find this project useful, please consider supporting it:

- [GitHub Sponsors](https://github.com/sponsors/rastislavcore)

List of sponsors: [![GitHub Sponsors](https://img.shields.io/github/sponsors/rastislavcore?label=Sponsors&logo=githubsponsors&color=EA4AAA)](https://github.com/sponsors/rastislavcore)
