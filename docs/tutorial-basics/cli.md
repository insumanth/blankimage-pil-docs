---
title: CLI
description: using cli.
---

# CLI

#### blankimage-pil is a python cli to generate blank images. It has simple cli interface to get the job done.

Use `blankimage-pil` or `blankimage` to invoke the cli tool.

```bash

 $ blankimage --help
usage: blankimage [-h] 
[--size HEIGHT WIDTH] 
[--color-mode {RGB,RGBA,HSV,CMYK,YCbCr,LAB,P,RGBX,1,F,I,L,HEX}] 
[--color COLOR] 
[--image-format {BLP,BMP,DDS,DIB,EPS,GIF,ICNS,ICO,IM,JPEG,JPEG_2000,MSP,PCX,PNG,PPM,SGI,SPIDER,TGA,TIFF,WebP,XBM,PALM,PDF,XV}] 
[--params PARAMS] [filename]

positional arguments:
  filename              File name of the generated file. File extension is used to infer the image file type.

options:
  -h, --help            show this help message and exit
  --size HEIGHT WIDTH   Image dimensions
  --color-mode {RGB,RGBA,HSV,CMYK,YCbCr,LAB,P,RGBX,1,F,I,L,HEX}
                        Color format to use in image and given in --color.
  --color COLOR         Color value to use in image, Hex string or comma seperated list of numbers as per --color-mode format.
  --image-format {BLP,BMP,DDS,DIB,EPS,GIF,ICNS,ICO,IM,JPEG,JPEG_2000,MSP,PCX,PNG,PPM,SGI,SPIDER,TGA,TIFF,WebP,XBM,PALM,PDF,XV}
                        Image file format. Overrides the inferred file type from file name.
  --params PARAMS       Additional params in JSON format that will be passed when saving image.

```
