all:
	latexmk --pdf -lualatex -shell-escape main.tex

pvc:
	latexmk --pdf -lualatex -shell-escape -pvc -interaction=nonstopmode main.tex

clean:
	latexmk --pdf -lualatex -shell-escape main.tex -C
	rm -rf *.nav *.snm *.vrb luadebug.lua _minted-main
