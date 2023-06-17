# Documentação git

Documentação do git para ajuda nos comandos.

## Ele inicia o arquivo ".git/" para controlar a pasta.
````
git init
````

Ele é responsável por validar os arquivos modificados dentro do projeto.
Em vermelho ele mostra os arquivos modificados.
Em verde mostra os arquivos que foram adicionado pelo "git add"
````
git status
````

git add: Ele é responsável por coloca o arquivo modificado em uma area segura.

Configuração do usuário do git:
git config --global user.name "<seu_nome>"
git config --global user.email "<seu_email>"

git commit -m "<texto_da_modificação>": Ele é responsável por criar uma nova versão do projeto com as referencia do criador.

git log: Validar os meus comentários e modificações

git checkout -b <nome_da_branch>: Cria um nova branch ou ramo 

git checkout <nome_da_branch>: Muda de branch/ramo

git merge <nome_da_branch>: Ele adiciona a branch atual o conteúdo de outra branch.

git clone <url>: Baixa o projeto do repositório.
git push: Ele envia alteração para o repositório.

git pull: Ele puxa as alterações do repositório.

Possíveis Erros:
403: Apagando as credenciais, gerenciamento de credenciais
