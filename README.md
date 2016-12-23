# language-praat package

This package adds support for the PRAAT scripting language in Atom. Both syntax highlighting and snippets are included. [Literate programming](http://www.literateprogramming.com) is also possible, both using `noweb` and `markdown` syntax.

![Screenshot](https://github.com/stefanocoretta/language-praat/blob/master/praat-syntax.png?raw=true)

## Praat (Noweb)

The package allows syntax highlighting in `noweb` files. Code chunks in `noweb` are enclosed between the begin (`<<*>>=`) and end (`@`) markers.
Text within chunk markers is highlighted according to PRAAT syntax, while text outside the code chunks is rendered as `LaTeX` code.

## Praat (GitHub Markdown)

[GitHub Markdown](https://guides.github.com/features/mastering-markdown/) is also supported. Use the standard method for delimiting code chunks ````(```)````.

## Acknowledgements

This package has been converted to an Atom package from [praatSublimeSyntax](https://github.com/mauriciofigueroa/praatSublimeSyntax.git).
