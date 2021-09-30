# Como fazer commit por linha de comando para automação do Jira funcionar:
- git checkout -b feature/FM-2  -> cria (-b) uma nova branch já linkada com o Jira e já muda pra essa branch (checkout)
- git push --set-upstream origin feature/FM-2  -> pra levar a branch que você criou localmente para o GitHub
- git status
- git add . ou git add (nome_do_arquivo que você quer comitar)
- git commit -m "[FM-2] - Mensagem de commit"  -> [FM-2] é o id do seu card no Jira
- git push

# Terminou o projeto?
- Faça a Pull Request no GitHub adicionando os Reviewers (Gabriel Godoy e Daniel Branquinho) e assignes (você)
- Nome da Pull Request: "[FM-2] - Qual PR"
- Atualize o seu card do Jira com as horas trabalhadas e print da tela
- Avise no grupo do wpp Front para Tech Leader aceitar seu código
- Com o código aceito é passado ao PO aceitar o produto final
- Modelo de mensagem no wpp: "Aceitar pr [FM-33]: https://github.com/Maua-Dev/System_Maua_Front/pull/75"

# Foi solicitado mudanças?
- Commit as mudanças no mesmo padrão
- Solicite a review novamente na PR do Github no botão de refresh:
![image](https://user-images.githubusercontent.com/61150821/135380404-63c26f85-25f1-4945-8ec9-4d964344714e.png)
- Mande mensagem nesse modelo no wpp: "Aceitar alterações na pr [FM-33]: https://github.com/Maua-Dev/System_Maua_Front/pull/75"
