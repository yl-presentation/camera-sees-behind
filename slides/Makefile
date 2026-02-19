all: slides

slides: slide.tex
	latexmk -pdf -bibtex -shell-escape -interaction=nonstopmode -output-directory="./out" -f slide.tex
	cp ./out/slide.pdf ./
