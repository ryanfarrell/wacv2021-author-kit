# WACV 2021 Author Kit (Latex)

## Overleaf Template
We highly recommend the use of the [Overleaf Template](http://foo).  Overleaf has all of the needed packages/fonts by default and moreover, allows for synchronous collaboration/editing of multiple authors.  It is very user-friendly, but also fully functional.  The overleaf version is identical to the version found in this github repository.

### Other Latex Build Tools
If you prefer to use an alternative editor/build engine to overlaf, you can either:
* clone this git repository (`git clone https://github.com/ryanfarrell/wacv2021-author-kit.git`), or
* download the author kit found here at [this link](https://github.com/ryanfarrell/wacv2021-author-kit/archive/master.zip).

There are a variety of latex editing/build tools you can find on the web.

### Command-line (e.g. Linux)
If you plan to generate your paper via the command-line, you may need to install latex packages/fonts (e.g. `texlive-latex-base texlive-latex-recommended texlive-latex-extra texlive-fonts-recommended`).

To generate the document from the latex file, it is recommended that you use `pdflatex`.  For example, also using `bibtex` to generate references:

```$ pdflatex egpaper.tex; bibtex egpaper; pdflatex egpaper.tex```

### Microsoft Word Template (None Provided)
We are no longer providing a Microsoft Word template, and are actively discouraging the use of Word for preparing papers for WACV 2021.  Latex is used for the vast majority of conferences and journals in our field and Overleaf makes the use of Latex very straightforward, even for first-time users.  Overleaf provides an excellent tutorial titled [Learn Latex in 30 minutes](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes).


## Notes on Review vs. Camera-ready Formats:
The typical `egpaper_for_review.tex` and `egpaper_final.tex` files have been merged into a single file, `egpaper.tex`.  The file is initially set up for review submission -- all you need to add is your CMT paper ID.

There are important instructions at the top of the combined `egpaper.tex` document describing (i) how to use `\wacvfinalcopy` to toggle between the review and final (camera-ready) formats and (ii) how to set your Paper ID (which is assigned upon creation of your paper submission in CMT) for the review version and (iii) how to set the page number for the camera-ready version.
