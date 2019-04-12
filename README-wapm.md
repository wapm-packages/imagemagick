# ImageMagick

You can install ImageMagick with:

```shell
wapm install imagemagick
```

## Running

You can run magick cli

```shell
$ wapm run magick identify -verbose samples/rotate/rotate.png
```


## Building from Source

You will need Emscripten SDK (emsdk) to build the `magick.wasm` file.

Steps:

1. Setup emsdk (>= 1.38.11), see [Installation Instructions](https://github.com/juj/emsdk#installation-instructions)
2. Run `npm run build-wasm && npm run copy-magickWasm`
