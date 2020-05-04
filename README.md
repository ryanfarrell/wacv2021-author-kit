# WACV 2021 Author Kit (Latex)

_Notes:_
The typical `egpaper_for_review.tex` and `egpaper_final.tex` files have been merged.  There are important instructions at the top of the document describing (i) how to use `\wacvfinalcopy` to toggle between the review and final (camera-ready) formats and (ii) how to set your Paper ID (assigned upon creation of your paper submission in CMT) for the review version and (iii) how to set the page number for the camera-ready version.

### Overleaf Template

We highly recommend the use of the [Overleaf Template](http://foo).  Overleaf has all of the needed packages/fonts by default and moreover, allows for synchronous collaboration/editing of multiple authors.  The overleaf version is identical to the version found in this github repository.

### Other Latex 
If you will not be using overleaf, there are instructions below for generating your paper.

You may want to make sure that you have the following packages installed


To generate the document from the latex file, it is recommended that you use `pdflatex`.  For example:
$ pdflatex egpaper.tex; bibtex egpaper; pdflatex egpaper.tex


### Microsoft Word Template

We are no longer providing a Microsoft Word template.  Latex is used for the vast majority of conferences and journals in our field and overleaf makes the use of latex very straightforward.
