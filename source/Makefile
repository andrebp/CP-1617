default: ghci

relatorio: cp1617t.aux cp1617t.idx
	bixtex cp1617t.aux
	makeindex cp1617t.idx

ghci: cp1617t.lhs
	ghci -XNPlusKPatterns cp1617t.lhs
