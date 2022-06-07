# commands
RM      := rm -rf
LATEX   := pdflatex

default: TheoreticalNeuroscience.pdf

%.pdf : %.tex png chap
	$(LATEX) $<
	$(LATEX) $<

clean:
	$(RM) ./auto *.aux *.bbl *.blg *.dvi *.log *.spl *.toc *~ */*~

realclean:
	$(MAKE) clean
	$(RM) *.pdf
