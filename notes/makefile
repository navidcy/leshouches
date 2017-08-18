file=17leshouches_notes

.PHONY: now
now:
	pdflatex ${file}
	bibtex ${file}

.PHONY: show
show:
	open /Applications/Preview.app ${file}.pdf

