# Makefile 
# Creado para ahorrar un poco el trabajo. 
# Walter Vargas <walter@covetel.com.ve>

NAME=$(shell pwd | xargs basename)

all: cv clean

cv: ${NAME}.pdf

${NAME}.pdf: ${NAME}.tex 
	pdflatex ${NAME}.tex

clean: 
	rm -f *.aux *.log *.out *.ps *.toc *.nav *.snm *.dvi;
