file: *.tex
	pdflatex -shell-escape *.tex
	rm *.aux 

clean_after_vscode:
	cp -r *.log logs/.
	rm *.fdb_latexmk *.fls *.synctex.gz *.aux *.bbl *.log *.blg *.lof *.toc *.out *.pyg
