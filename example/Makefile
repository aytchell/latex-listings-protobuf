all: example.pdf

example.pdf: example.tex ../protobuf/lang.sty ../protobuf/style.sty
	TEXINPUTS=.:..: pdflatex example

.PHONY: clean
clean:
	rm -r example.aux example.log
