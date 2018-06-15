# TODO-Liste

* \captionabove kann z.B. für Tabellen eingesetzt werden. Hier wird dann dem Linespacing von "Überschriften" Rechnung getragen.
* Kapitel über "schöne Tabellen" mit booktabs einfügen. 
  * Das alternierende Einfärben mit \rowcolors aus dem Paket xcolor auch aufnehmen.
  * Besonderheiten von longtable
  * sidewaytable

~~~~
\usepackage[table]{xcolor}
\definecolor{Gray}{gray}{0.9}
\rowcolors{2}{Gray}{white}
\begin{tabular}{l l}
\toprule
foo & bar \\
\midrule
...
\bottomrule
~~~~


Die folgenden Punkte könnte (sollte?) man auch in ein separates Dokument auslagern!

* Abschnitt über "Interessante Pakete"
  * booktabs, xcolor, xspace, mdframe, ...
  * varioref, hyperref und cleverref genau in der Reihenfolge. Sowohl varioref als auch cleverref nutzen den Parameter [ngerman].  Siehe archive/unsorted/publish/.../test-cleverref-varioref-hyperref.ltx!
  * enumitem -- Control layout of itemize, enumerate, description. Das ist der Nachfolger von mwdlist!
  * mdwlist -- neues environment `itemize*` mit geringerem Linespacing zwischen den "Items".
* Abschnitt über "Interessante Tools"
  * TeXstudio
  * TeXclipse
  * latexrun
  * awk zur Extraction...
* Bibtex 
  * das berühmte "et al" bekommt man mit "and others". Tests siehe `Tests/latex-stuff/bibtex/`
  * To typeset accented characters inside bibliography fields for processing with BibTeX, encase them in curly braces. To list but a few accented characters ![accented-chars-samples.png](sample of accented characters):

~~~~
{\"a} {\^e} {\`i} {\.I} {\o} {\'u} {\aa} {\c c} {\u g} {\l} {\~n} {\H o} {\v r} {\ss}
~~~~

