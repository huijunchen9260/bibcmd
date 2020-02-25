# bibcmd

A collection of POSIX shell scripts to manage and utilize bibtex

Used in upcoming project `dmenubib`.

## `bibsearch`

Need to set `$BIB` environment variable into your `.bib` file.

Functions:

`[bibsearch "Title"]`:
Search title in [Crossref](https://search.crossref.org/), and generate bibtex by manually copying doi from search result.

`[bibsearch "PDF"]`:
Search title in [Crossref](https://search.crossref.org/) from pdf metadata.

`[bibsearch "doi"]`:
Search doi and generate bibtex.

## `bibrefer`

List papers in `.bib` file based on

1. title
2. authoryear
3. mixed (authoryear and title)

and copy the label to clipboard.
