RAPPORT = rapport.tex
PDF = $(addsuffix .pdf, $(basename $(RAPPORT)))
TOC = $(addsuffix .toc, $(basename $(RAPPORT)))
LOG = $(addsuffix .log, $(basename $(RAPPORT)))
AUX = $(addsuffix .aux, $(basename $(RAPPORT)))
OUT = $(addsuffix .out, $(basename $(RAPPORT)))
TMP = $(TOC) $(LOG) $(AUX) $(OUT)

$(PDF) : $(RAPPORT)
	pdflatex $^
	pdflatex $^
	rm -f $(TMP)
	evince $@

clean :
	rm -f $(PDF) $(LOG) $(AUX) $(OUT)
