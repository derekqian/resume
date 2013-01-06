# "sudo apt-get install tex4ht" for htlatex

all : resume DerekQianResume631420OSSWI

resume : 
	latex resume
	dvips resume
	ps2pdf resume.ps

DerekQianResume631420OSSWI :
	htlatex DerekQianResume631420OSSWI
	latex DerekQianResume631420OSSWI
	dvips DerekQianResume631420OSSWI
	ps2pdf DerekQianResume631420OSSWI.ps

clean : 
	rm *.aux
	rm *.dvi
	rm *.log
	rm *.ps
	rm *.pdf
