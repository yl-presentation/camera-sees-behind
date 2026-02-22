all: main

main: proposal.tex
	latexmk -pdf -bibtex -shell-escape -interaction=nonstopmode -output-directory="./out" -f proposal.tex
	cp out/proposal.pdf ./
