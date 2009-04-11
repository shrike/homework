.PHONY: clean

all: ps4.pdf

%.dvi: %.latex
	latex $<

%.pdf: %.dvi
	dvipdf $<

clean:
	rm -rf *log *pdf *dvi *aux
