# TODO-Liste

* \captionabove kann z.B. für Tabellen eingesetzt werden. Hier wird dann dem Linespacing von "Überschriften" Rechnung getragen.


Die folgenden Punkte könnte (sollte?) man auch in ein separates Dokument auslagern!

* Abschnitt über "Interessante Pakete"
  * booktabs, xcolor, xspace, mdframe, ...
  * varioref, hyperref und cleverref genau in der Reihenfolge. Sowohl varioref als auch cleverref nutzen den Parameter [ngerman].  Siehe archive/unsorted/publish/.../test-cleverref-varioref-hyperref.ltx!
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

