ArXiv Template ZIB

# Guidelines to edit the source files

## General recommendations: 

* use british english (optimise, behaviour, fulfil, ...)
* newline at the end of each sentence
* the following should always be preceded and followed by a comma: "that is", "namely", "specifically", "i.e.", "e.g.", "for instance", "say", "etc."

## Bibliography 
* if your bibliography is contained in a bib directory, where each file is a single bib file, then you can create the file `main.bib` with: `cat ../bib/*.bib > main.bib`
* if, instead, you manage your bibliography with a big `.bib` file containing all of your bib entries from the creation of the world to nowadays, and you want to filter it to contain only the citations in your `main.tex`, and you potentially want to sort it: then use https://github.com/giommazz/useful-scripts/blob/main/bib_filter_sort/fsbib.sh

### Naming conventions for the bibliography
* naming convention for bib keys is
* single author: first three letters, year ("Wer89")
* up to four authors: all initials, year ("CHSH69")
* more than five authors: first three initials, "+", year: ("HQV+17")
