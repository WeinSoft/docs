[![Documentation Status](https://readthedocs.org/projects/cryptomator/badge/?version=latest)](https://docs.cryptomator.org/en/latest/?badge=latest)

# Cryptomator Documentation

This is the English Cryptomator documentation.

If you want to contribute documentation in different languages, please let us know.

## Contributing

- View the [MkDocs documentation](https://www.mkdocs.org).
- Fork this repo
- Send us a pull request

<!--
How tow record `.gif`s:

1. Record screen using Quicktime on #FCFCFC background
2. Generate palette for PNG: `ffmpeg -i recording.mov -vf "fps=10,palettegen" -y palette.png`
2. Generate GIF: `ffmpeg -i recording.mov -i palette.png -lavfi "fps=10 [x]; [x][1:v] paletteuse" -y result.gif`
-->
