plump.pdf: plump.tex
	pdflatex plump.tex
	pdflatex plump.tex
	pdflatex plump.tex

plump.tex: plump.nw
	noweave -index plump.nw > plump.tex

plump.py: plump.nw
	notangle plump.nw > plump.py
	chmod +x plump.py

clean:
	rm -f *.log
	rm -f *.aux
	rm -f *.toc
	rm -f *.tex
