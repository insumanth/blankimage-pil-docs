---
title: Color Mode
description: color-mode option
---

# `--color-mode {RGB,RGBA,HSV,CMYK,YCbCr,LAB,P,RGBX,1,F,I,L,HEX}`

Use one of the below supported color format.

* `HEX` hex color code.
* `1` (1-bit pixels, black and white, stored with one pixel per byte)
* `L` (8-bit pixels, grayscale)
* `P` (8-bit pixels, mapped to any other mode using a color palette)
* `RGB` (3x8-bit pixels, true color)
* `RGBA` (4x8-bit pixels, true color with transparency mask)
* `CMYK` (4x8-bit pixels, color separation)
* `YCbCr` (3x8-bit pixels, color video format). Note that this refers to the JPEG, and not the ITU-R BT.2020, standard
* `LAB` (3x8-bit pixels, the L*a*b color space)
* `HSV` (3x8-bit pixels, Hue, Saturation, Value color space). Hue’s range of 0-255 is a scaled version of 0 degrees <= Hue < 360 degrees
* `I` (32-bit signed integer pixels)
* `F` (32-bit floating point pixels)


