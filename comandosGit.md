# CONFIGURAÇÕES___
##seta usuario	
		git config --global user.name
##seta email
		git config --global user.email
#REPOSITÓRIO JÁ EXISTENTE___
##copia para maquina local
		git clone url
#VERIFICAÇÃO___
##verifica na branch
		git status
##verifica com hash do do container
		git log  --oneline  --graph  --all
##verifica modificações antes do container
		git diff
#MOVIMENTAÇÕES  NO PROJETO___
		git add arquivo ou * .
#MOVIMENTAÇÕES PARA O CONTAINER___
##	remove do container
		git reset HEAD
##envia para container
		git commit -m "comentario"
##envia para container sem usar add 
		git commit -am "comentario"
#MOVIMENTAÇÕES PARA O REPOSITÓRIO
##envia para o github
		git push renansc  - R&n@n1988
#CONTROLE DE VERSOES___
##visualizar versão atual 
		git branch
##visualiza outra versão
		git checkout -b hash do commit
##volta para ultima versão  ou ramo
		git checkout master
#CONTROLE DE RAMIFICAÇÕES___
##cria novo ramo
		git checkout -b "novoramo"
##mistura ramos
		git  merge nome do ramo que vai para o master
#VALIDAÇÃO PELO SSH (USO DE SENHA AUTOMATICO PARA PUSH)___
##criar chave local
		ssh-keygen -t rsa -b 4096 -c "email git"
##executar
		eval ssh-agent  -s 
		ssh-add ~/.ssh/id_rsa
##entrar no github e adicionar a chave clicando na foto e settings
##verificar chave 
		git remote -v
##mudar de https para ssh
		git remote set-url origin git@github.com:"seu user"/seu repositorio
##instalar o xclip, copiar chave id_rsa.pub para o git

