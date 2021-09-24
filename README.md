# Como fazer commit por linha de comando para automação do Jira funcionar:

- git checkout -b feature/FM-2  -> cria (-b) uma nova branch já linkada com o Jira e já muda pra essa branch (checkout)
- git push --set-upstream origin feature/FM-2  -> pra levar a branch que você criou localmente para o GitHub
- git status
- git add . ou git add (nome_do_arquivo que você quer comitar)
- git commit -m "[FM-2] - Mensagem de commit"  -> [FM-2] é o id do seu card no Jira
- git push

# Terminou o projeto?
- Faça a Pull Request no GitHub e manda mensagem para Guerreiro para aceitar a pr
- nome da Pull Request: "[FM-2] - Qual PR"
