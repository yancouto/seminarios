all:
	latexmk --pdf -lualatex -shell-escape main.tex

full:
	texliveonfly -c lualatex --arguments="-shell-escape -interaction=nonstopmode" main.tex
	latexmk --pdf -lualatex -shell-escape main.tex
	cp main.pdf ../site/seminario-aho-corasick.pdf

pvc:
	latexmk --pdf -lualatex -shell-escape -pvc -interaction=nonstopmode main.tex

clean:
	latexmk --pdf -lualatex -shell-escape main.tex -C
	rm -rf *.nav *.snm *.vrb luadebug.lua _minted-main
