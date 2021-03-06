# mgli

You need to save the `template.tex` file to regenerate the PDF. You can open the intergrated PDF Viewer from VSCode to see live updates.

## Installation

- Install a LaTeX distribution like [TeX Live](https://www.tug.org/texlive/)
- Install [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) for VSCode
- You may need to install [Latexmk](https://mg.readthedocs.io/latexmk.html)

You should be able to run `tlmgr` commands in your terminal if everything
is installed correctly.

### MacOS instruction

As I'm using MacOS as my primary system, I documented my installation procedure:

- `brew cask install mactex`
- make sure `"/usr/local/texlive/2020/bin/x86_64-darwin"` is in PATH and reload the Terminal
- `sudo tlmgr option repository ctan`
- `sudo tlmgr update --self`
- `sudo tlmgr install latexmk`
- `sudo tlmgr install latexindent`
- `sudo tlmgr install chktex`
- `code --install-extension James-Yu.latex-workshop`

I still get **Formatting failed** warnings when saving, even though the output
log shows no errors. Something to fix at some point ¯\\\_(ツ)\_/¯.

## Timeline

- **Gruppenarbeit 1, Abgabe 13.10.2020** (06.10.2020 Draft)<br />
  Angelo: Aussagenlogik, Fabian: Prädikate, Reto: Mengenlehre
- **Gruppenarbeit 2, Abgabe 10.11.2020** (03.11.2020 Draft)<br />
  Relationen und Funktionen, Graphen
- **Gruppenarbeit 3, Abgabe 05.01.2020** (29.12.2020 Draft)<br />
  Vollständige Induktion, Beweismethoden, Rekursion
- **Gruppenarbeit 4, Abgabe 12.01.2020**<br />
  Formale Sprachen und Automaten, Grammatiken

## Resources

Some helpful resources:

- http://www.math.union.edu/~niefiels/old/Symbols.pdf
- https://patrick-robrecht.de/downloads/latex-kurzreferenz.pdf
- https://de.wikibooks.org/wiki/LaTeX-Kompendium:_F%C3%BCr_Mathematiker
- https://www.overleaf.com/learn/latex/Paragraphs_and_new_lines
