
NAME =paper

all: $(NAME).pdf

clean:
	rm -rf *.log *.aux *.toc  *.dvi *.ps *.pdf *.mps

$(NAME).pdf: *.tex
	latex $(NAME).tex
	latex $(NAME).tex
	latex $(NAME).tex
	latex $(NAME).tex
	pdflatex $(NAME).tex abc.pdf
	rm -rf *.log *.aux *.toc  *.ps *.mps *.dvi
