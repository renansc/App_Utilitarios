# CONFIGURAÇÕES
---
## 1.set user	
`git config --global user.name`
## 1. set email
`git config --global user.email`
#REPOSITÓRIO JÁ EXISTENTE
---
## 1.copiando  para localmente
`git clone url`
#VERIFICAÇÃO
---
## 1.verifica na branch
`git status`
##1.verifica com hash do do container
`git log  --oneline  --graph  --all`	
## 1. verifica modificações antes do container
`git diff`	
#MOVIMENTAÇÕES  NO PROJETO
---
`git add arquivo`  ou  `git add  .`  para todos
#MOVIMENTAÇÕES PARA O CONTAINER
---
## 1.remove do container
`git reset HEAD`
## 1.envia para container
`git commit -m "comentario"`
### 1.envia para container sem usar add 
`git commit -am "comentario"`
#MOVIMENTAÇÕES PARA O REPOSITÓRIO
---
## 1.envia para o github
`git push` pede usuario e senha depois
#CONTROLE DE VERSOES___
## 1.visualizar versão atual 
`git branch`
## 1.visualiza outra versão
`git checkout -b hash do commit`
## 1.volta para ultima versão  ou ramo
`git checkout master`
#CONTROLE DE RAMIFICAÇÕES
---
## 1.cria novo ramo
`git checkout -b "novoramo"`
## 1.mistura ramos
`git  merge nome do ramo que vai para o master`
#VALIDAÇÃO PELO SSH (USO DE SENHA AUTOMATICO PARA PUSH)
---
## 1.criar chave local
`ssh-keygen -t rsa -b 4096 -c "email git"`
## 1.executar
`eval ssh-agent  -s ` e `ssh-add ~/.ssh/id_rsa`
## 1.entrar no github e adicionar a chave clicando na foto e settings
## 1.verificar chave 
`git remote -v`
## 1.mudar de https para ssh
`git remote set-url origin git@github.com:"seu user"/seu repositorio`
## 1.instalar o xclip, copiar chave id_rsa.pub para o git

