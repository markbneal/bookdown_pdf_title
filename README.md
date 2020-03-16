This was a minimal example of a book based on R Markdown and **bookdown** (https://github.com/rstudio/bookdown).

This example has been modified as per stackoverflow suggestions here (https://stackoverflow.com/questions/45963505/coverpage-and-copyright-notice-before-title-in-r-bookdown/48371022?noredirect=1#comment107413960_48371022) in order to add a title page (in this case text and image) at the start of the book. This includes adding lines to the `preamble.tex`, and creating a `before_body.tex`.

Current version does not work (17/3/2020).
Error message on build:
! Undefined control sequence.
l.127 \\maketitle

Error: LaTeX failed to compile bookdown-demo.tex. See https://yihui.org/tinytex/r/#debugging for debugging tips. See bookdown-demo.log for more info.
Execution halted

Exited with status 1.