# CONFIGURAÇÕES
	seta usuario	
		git config --global user.name
	seta email
		git config --global user.email
#REPOSITÓRIO JÁ EXISTENTE
	copia para maquina local
		git clone url
#VERIFICAÇÃO
	verifica na branch
		git status
	verifica com hash do do container
		git log  --oneline  --graph  --all
	verifica modificações antes do container
		git diff
#MOVIMENTAÇÕES  NO PROJETO
		git add arquivo ou * .
#MOVIMENTAÇÕES PARA O CONTAINER
	remove do container
		git reset HEAD
	envia para container
		git commit -m "comentario"
	envia para container sem usar add 
		git commit -am "comentario"
#MOVIMENTAÇÕES PARA O REPOSITÓRIO
	envia para o github
		git push renansc  - R&n@n1988
#CONTROLE DE VERSOES
	visualizar versão atual 
		git branch
	visualiza outra versão
		git checkout -b hash do commit
	volta para ultima versão  ou ramo
		git checkout master
#CONTROLE DE RAMIFICAÇÕES
	cria novo ramo
		git checkout -b "novoramo"
	mistura ramos
		git  merge nome do ramo que vai para o master
ultima aula
https://www.youtube.com/watch?v=iRs6sQOPcvg&list=PLbEOwbQR9lqzK14I7OOeREEIE4k6rjgIj&index=5
	
	
