filename=cv

all: compile
	
compile:
	@echo "*********************************************************"
	@echo "*                                                       *"
	@echo "* Compilando Xelatex to my cv			       *"
	@echo "*                                                       *"
	@echo "*********************************************************"
	@echo "Compilando..."
	xelatex $(filename).tex
	xelatex $(filename).tex
	@clear
	@echo "Processo finalizado com sucesso!"

	
clean:
	@echo -n "Limpando arquivos auxiliares...\n"
	@rm -f *.out *.aux *.xml *.bcf *.log *~
	@rm -f $(filename).pdf
	@echo "Processo finalizado com sucesso!"	
