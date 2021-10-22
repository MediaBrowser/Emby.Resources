## Emby SVG-Logo Reconstruction

The logo from the tvOS repo (InkscapeEmbyLogoNoText.svg) is inaccurate in its outsets. They are not equal on all sides.

For that reason, I have re-constructed the logo icon using precise values for position, widths and heights.

The starting point is 

### EmbyLogo_Reconstruct_Step1.svg

Not yet rotated
All values are accurate
Rectangles are separate

### EmbyLogo_Reconstruct_Step2_Outset_12.svg

Not yet rotated
Rects are outset by 12 units
(outset corresponding to the original logo)
Rectangles are separate

### EmbyLogo_Reconstruct_Step2_Outset_15.svg

Not yet rotated
Rects are outset by 15 units
This version is intended for rendering at small sizes (<= 32x32), where the 12 unit outset can look like as if it was flawed rather than intential.
Don't use this for larger presentations
Rectangles are separate

## EmbyLogo_Reconstruct_Step3_Outset_12.svg

Rotated
Green area combined to a single shape

## EmbyLogo_Reconstruct_Step3_Outset_15.svg

Rotated
Green area combined to a single shape


Use Save-As "optimized SVG" in Inkscape for using any output

