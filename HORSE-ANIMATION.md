# Motivation background

Compile `dynamic-turn (2).tex` with pdfLaTeX twice, keeping `horse-frames.pdf`
beside it. No shell escape or conversion step is needed in Overleaf.

Only the **Motivation section divider** has the moving background. The PDF
contains 15 distinct frames, looping at the original speed of 10 frames per
second. The heading and violet veil are drawn above the animation using
the `animate` package's `method=ocg` option.

Download the compiled PDF and open it in **desktop Adobe Acrobat Reader or
Okular with JavaScript enabled**. Overleaf and other unsupported previews
may display only the first frame. The animation starts when the divider
opens; the subsequent slides use the normal background.

## Image credit

Photographs: Eadweard Muybridge, *Animal Locomotion*, plate 626 (1887).
Animation: Waugsberg. Wikimedia Commons identifies the source as public domain.

Source: https://commons.wikimedia.org/wiki/File:Muybridge_race_horse_animated.gif

`horse-frames.pdf` contains the 15 coalesced GIF frames, one per PDF page.
The original GIF has a 100 ms duration per frame (1.5 seconds per loop).

Package documentation: https://tug.ctan.org/macros/latex/contrib/animate/animate.pdf
