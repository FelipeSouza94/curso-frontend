# curso-frontend
#### EBAC

# GIT
### versionamento 
 - Historico
 - Controle de versão
 - Quem alterou
 - O quê alterou
 - Quando alterou
 - Todos arquivos
 - evoção continua

 Arquivo A | Versão 1 | Versão 2
 Arquivo B | Versão 1 | Versão 2

## Instalação do Git
https://git-scm.com/ 

windows: https://git-scm.com/download/win
Linux (apt-get): sudo apt-get install git
Mac (brew): install git

## Criar conta no github

## Clonar projeto

## Commits
Informação de alteração
- após testado todo seu código
- git add *
- git commit -m 'mensagem'
- git push ( enviar alterações para o repositório)
- git pull (trazer alterações do github)

## Gitflow
fluxo do git


### Branchs
são retificações / versões paralelas

-  mais / master (vai para produção, quando o projeto e publicado)
- develop
-  DOD (definition of done): criteiro de aceite
- versionamento 

git checkout -b dev (cria uma branch)
git checkout main    (mudar de branch)

### Merge
mescla de brachs
você poode precisar resolver conflitos manualmente

git merge main


### Pull Reaquest
Mescla de branchs no reporsitorio
permite o code review
o respositorio resolve  o conflito automaticamente

### Configura o gitflow
git flow init
git flow feature start (nome-da-feature)