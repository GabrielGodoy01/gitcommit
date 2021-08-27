# Como fazer commit por linha de comando para automação do Jira funcionar:

## 1 - git checkout -b SeuNickGithub/FM-2  -> cria (-b) uma nova branch já linkada com o Jira e já muda pra essa branch (checkout)
## 2 - git push --set-upstream origin SeuNickGithub/FM-2  -> pra levar a branch que você criou localmente para o GitHub
## 3 - git status
## 4 - git add . ou git add (nome_do_arquivo que você quer comitar)
## 5 - git commit -m "[FM-2] - Mensagem de commit"  -> [FM-2] é o id do seu card no Jira
## 6 - git push


## Terminou o projeto?
## Faça a Pull Request no GitHub e manda mensagem para Guerreiro para aceitar a pr, cabo
## nome da Pull Request: "[FM-2] - Qual PR"
