# "sudo apt-get install tex4ht" for htlatex, mk4ht

all : DerekQianCoverLetter

DerekQianCoverLetter :
	htlatex DerekQianCoverLetter
	latex DerekQianCoverLetter
	dvips DerekQianCoverLetter
	ps2pdf DerekQianCoverLetter.ps

clean : 
	rm *.aux
	rm *.dvi
	rm *.log
	rm *.ps
	rm *.pdf
