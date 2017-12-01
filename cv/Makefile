all:	cv-mk.html

%.html:	%.md
	pandoc -t html -o $@ $< -c cv-mk.css

clean:
	rm -f *~ *.html *.log *.pdf
