
tester:	
	# copiando código do estudante para soma.sci
	cp __USERCODE__ soma.sci

run:
	# executando testador
	scilab -nb -nwni -f tester.sce > output
	cat output | grep "GRADE"
