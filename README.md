This repository is a collection of reference styles for biology papers.

It is primarily for personal use, but is released for the free use of anyone who wishes it.
I make no guarantees about correctness, completeness, or backwards compatibility.
In particular, it will typically only handle journal articles and books, with other sources only handled as I require them.
I may make breaking changes, and will not be versioning this, so use of git submodules is recommended if you wish to include this in your project.

As the style files may `\input` additional files within this repository, they should be added using `\import`, rather than `\input`.
For example:
```latex
\usepackage{import}
\import{reference-styles/}{authoryear.tex}
\addbibresource{X.bib}
```
