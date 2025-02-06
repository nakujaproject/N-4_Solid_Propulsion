.PHONY: all clean

all: target

target: main.aux main.tex
	pdflatex main.tex	\
	&& biblatex main.aux	\
	&& pdflatex main.tex	\
	&& pdflatex $main.tex

clean:
	rm -f target
