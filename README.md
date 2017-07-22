# Gentoo Slim Themes

A small collection of SLiM login manager themes, intended to complement my <a
href="github.com/telemin/gentoo-grub-themes">Grub2</a> themes in the same
style.

Both 1920x1080 and 3840x2160 versions are provided here. If you would like an
alternative aspect ratio please let me know and I will do my best to oblige.

## Glass

<img src="./previews/glass.png" width="400">

## Dark Glass

<img src="./previews/dark_glass.png" width="400">

# Design Notes

### Image file size

I suggest creating the initial gradients with a 32-bit colorspace, this can
then be reduced to a 16- or 8-bit colorspace for outputting the final image.
To get good crisp edges on the gentoo logo, png is the better image format,
naturally this leads to a much larger image that the equivalent jpeg.
Naturally, if space is at a premium and the softness is acceptable to you, feel
free to use jpeg versions.

### Gradient

The light gradient runs between #8f88bd - #f8f7fb
The dark gradient runs between #8f88bd - #0e0d12

### Logo size and placement

The gentoo logo is directly converted to png from the gentoo-signet.svg from
gentoo.org. It has vertical height 750/1080 of the full image height. Use
inkscape in preference to the gimp to get high quality conversions with minimal
aliasing.

The logo is vertically centered and the left edge of the logo frame is
1000/1080 from the left edge of the image frame.

# License

This project is licensed under the ![MIT License](./LICENSE).

Gentoo Logo is copyright Gentoo Foundation and Lennart Andre Rolland, licensed
under CC-BY-SA/2.5. 

### Author
Phil Tooley

