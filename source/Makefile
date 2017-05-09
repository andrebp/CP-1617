default: ghci

relatorio: cp1617t.aux cp1617t.idx cp1617t.lhs
	bibtex cp1617t.aux
	makeindex cp1617t.idx
	lhs2TeX cp1617t.lhs > cp1617t.tex
	pdflatex cp1617t

ghci: cp1617t.lhs
	ghci -XNPlusKPatterns cp1617t.lhs
