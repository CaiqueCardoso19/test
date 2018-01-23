# Workflow #

Guia para utilizar o git e o markdown

### Ferramentas e Plataformas

- [Git Bash](http://gitforwindows.org/)
- [GitLab](https://gitcorp.prod.cloud.ihf/luxavfe/NF2-Treinamento-Simple-App/blob/development/README.md)
- [Jenkins](http://10.31.65.158:8080/)
- [SonarQube](http://nexusinternet.itau/sonar/)

### Tecnologias do Projeto
- Java 8
- JavaScript
- HTML 5
- CSS

### Conceitos abordados

- Arquitetura MVC
- Spring Framework
- Testes unitários
- Router & URL Resolver
- Actions & Menus
- Serialização & Deserialização


_______________________________

**RACF** | **NOME** | **FUNCIONAL** | **DATA**
---- | ---- | --------- | ----
rcaique | Caique Cardoso Reis | 987291031 | 22/01/2018
luxavfe | Lucas Xavier Ferreira | 987288538 | 23/01/2018
_______________________________

**[ TEORIA ]**
- O que é git?
- Para que serve o git?
- Quem criou e por qual motivo?
- Diferença entre SVN e DISTRIBUIDO?
- Links úteis:
    - [Nosso GitLab](https://gitcorp.prod.cloud.ihf/)
    - [Tutoriais de markdown](https://guides.github.com/features/mastering-markdown/)
    - [Tutoriais de git](url aqui)
    - [gitflow](url aqui)

```git
    [ COMANDOS ]
        - git config --global [ user.name | user.email ] [ caique | caique.reis@~ ]
        - git init
        - git clone [ https & ssh ]
        - git status
        - git add [ <filename> | . | * | pasta/*.js ]
        - git commit [ -m <'text'> | -am '<text>' | ammend ] 
        - git reset <filename> | git checkout <filename>
        - git pull
        - git fetch
        - git push
        - git checkout -d <'name'>
        - git checkout <'name'>
        - git stash
        - git log
        - git diff
        - git rebase
        - git branch
        - git -help
        - git merge
        - git reflog - lista os HEADs
        - git rever HEAD@{n} - reverte o commit
        - git blame [ CAGUETA ]

    [ DEFAULT ]
        .gitignore <ignores>        
        README.md - markdown
        pull request
    
    [ DICAS ]
        - Primeiro commit [ .gitignore && README.md ]
        - Commits pequenos ( poucas linhas de código )
        - Comentar o commit de forma coerente
        - Seguir a consistência de mensagens de commit do projeto: #TASK203 - Definindo nome da página
        - Não modificar o .gitignore se não souber o que está fazendo
        - Sempre criar uma branch development
        - Criar sub-branches por feature
```
