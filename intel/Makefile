# "sudo apt-get install tex4ht" for htlatex, mk4ht

all : resume DerekQianResume631420OSSWI

resume : 
	latex resume
	dvips resume
	ps2pdf resume.ps

DerekQianResume631420OSSWI :
	htlatex DerekQianResume631420OSSWI
	mk4ht oolatex DerekQianResume631420OSSWI.tex
	latex DerekQianResume631420OSSWI
	dvips DerekQianResume631420OSSWI
	ps2pdf DerekQianResume631420OSSWI.ps
	pdflatex DerekQianResume629945ASE.tex

clean : 
	rm *.aux
	rm *.dvi
	rm *.log
	rm *.ps
	rm *.pdf
