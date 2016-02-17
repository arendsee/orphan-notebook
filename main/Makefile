.PHONY: notes.pdf clean

all: notes.pdf

notes.pdf:
	latexmk --pdf --bibtex notes.tex

clean:
	latexmk -CA
