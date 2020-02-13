.PHONY: zip

zip: *.zip

INH-PROT-05-01.pdf: tex/INH-PROT-05-01.tex
	pdflatex tex/INH-PROT-05-01.tex

INH-OC-05-01.pdf: tex/INH-OC-05-01.tex
	pdflatex tex/INH-OC-05-01.tex

formationvdr4.zip: *.pdf ../../suplement/suplement.pdf
	rm -f formationdvr4.zip
	zip -j formationvdr4.zip *.pdf \
		../../suplement/suplement.pdf

clean:
	rm -f *.aux *.log
