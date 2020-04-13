# CONFIGURAÇÕES
---
### set user	
`git config --global user.name`
###  set email
`git config --global user.email`

REPOSITÓRIO JÁ EXISTENTE
---
### copiando  para localmente
`git clone url`

# VERIFICAÇÃO
---
### verificar na ramificaçãoA
`git status`
###verifica com hash do do container
`git log  --oneline  --graph  --all`	
###  verifica modificações antes do container
`git diff`	

#MOVIMENTAÇÕES  NO PROJETO
---
`git add arquivo`  ou  `git add  .`  para todos

#MOVIMENTAÇÕES PARA O CONTAINER
---
### remove do container
`git reset HEAD`
### envia para container
`git commit -m "comentario"`
#### envia para container sem usar add 
`git commit -am "comentario"`

#MOVIMENTAÇÕES PARA O REPOSITÓRIO
---
### envia para o github
`git push` pede usuario e senha depois

#CONTROLE DE VERSOES
---
### visualizar versão atual 
`git branch`
### visualiza outra versão
`git checkout -b hash do commit`
### volta para ultima versão  ou ramo
`git checkout master`

#CONTROLE DE RAMIFICAÇÕES
---
### cria novo ramo
`git checkout -b "novoramo"`
### mistura ramos
`git  merge nome do ramo que vai para o master`

#VALIDAÇÃO PELO SSH (USO DE SENHA AUTOMATICO PARA PUSH)
---
### criar chave local
`ssh-keygen -t rsa -b 4096 -c "email git"`
### executar
`eval ssh-agent  -s ` e `ssh-add ~/.ssh/id_rsa`
### entrar no github e adicionar a chave clicando na foto e settings
### verificar chave 
`git remote -v`
### mudar de https para ssh
`git remote set-url origin git@github.com:"seu user"/seu repositorio`
### instalar o xclip, copiar chave id_rsa.pub para o git

