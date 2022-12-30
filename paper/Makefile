# If you want to compile your LaTeX file using the Linux/Posix command line.

.phony: build 
build: seminar_hannah_lappe.tex bibliography.bib
	latexmk -lualatex -shell-escape -outdir=out -synctex=1 -interaction=nonstopmode -file-line-error $<
