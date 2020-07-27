Files/folders:
- ms.tex: main .tex file
- preamble.tex: subsidiary .tex file called by ms.tex
- bibl.bib: bibliographic repository, called by ms.tex
- tikz (folder): contains .tex files for TikZ drawings, called by ms.tex
- COPYING.txt: license information.

To produce PDF lecture notes, compile ms.tex using pdfLaTeX. Run biber to create a new .bbl file.