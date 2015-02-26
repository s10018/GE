
RM=/bin/rm

.PHONY: xelatex platex clean

xelatex: test_xelatex.tex
	xelatex test_xelatex
	xelatex test_xelatex

platex: test_platex.tex
	platex test_platex && platex test_platex && dvipdfmx test_platex

clean:
	${RM} -rf auto *.nav *.out *.snm *.toc *.vrb *.dvi *.aux *.log

