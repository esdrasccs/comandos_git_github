# :eagle: COMANDOS GIT - GITHUB :eagle:

### git init
- Inicia um repositorio na pasta selecionada
- 
### git config -- list 
- Lista a configuração dos dados git

### git config --global user.name <-nome->
- Atribui um nome ao usuário git

### git config --global user.email <-email->
- Atribui um email ao usuario git

### git config --global --unset <oque desejar removar a atribuição>
- Remove a atribuição, nome , email ou demais configurações ao usuario git.

### git add

- Adiciona arquivos ou diretorios Untraked para o git gerenciar. 
  ou adiciona arquivos ou diretorios Modify para Statmen, assim fica disponivel para o commit.

### git commit -m <-Comentario para registro->

- Envia as modificações nos arquivos para o repositorio local.

### git commit -am <-Comentario para registro->

- Faz a mesma função do git Add e do commit, quando os arquivos já são gerenciados pelo git.

### git status

- Verifica o status dos arquivos

### git remote add origin <-remote url->

- Adiciona o repositorio remoto ao git

### git remote -v

- Exibe a URL do repositorio remoto atribuido.

### git push <-remote-> <-branch->

- Empurra os dados do branch especifico para o remoto.

### git pull <-remote> <-branch->

- Pucha os dados branch para o local.

### git clone <-url - remote->

- Clona um repositorio para sua maquina, na pasta selecionada.

### git log

- Mostra o log de commits do repositorio em questão.

### git log --oneline

- Mostra o log de commits do repositorio em questao de forma mas simples. 

### git reset --hard HEAD~1

- Reseta todas as alterações no git e arquivos até o commit selecionado.

  ### --soft HEAD~1
    - Desfaz o commit selecionado e mantem as alterações no diretorio.
  ### HEAD path/to/file
    - Reseta um arquivo especifico.
  ### --hard <commit_hash>
    - Reseta apagando tudo para um commit especifico.
  

### git revert HEAD

- Cria um novo commit com as alterações do commit anterior.

### git revert (Chave-SH1)

- Cria um novo commit, com as alterações do commit cujo a chave foi apresentada.

### git branch
- Exibe todos os branch locais disponiveis

### git branch <-nome do branch->

- Criar um novo branch de acordo com o nome.

### git branch -d <-nome do branch->

- Remove uma branch de acordo com o nome passado. 

### git push <-remote-> :<-nome do branch->
### git push <-remote->  --delete <-nome do branch->
- Remove uma branch do repositorio na nuvem.

### git checkout <-nome do branch->

- Alterna entre branch de acordo com o nome.

### git diff

- Mostra as modificações feitas em arquivos antes do commit comparados ao commit anterior.

### git diff --name-only

- Mostra o nome dos arquivos que foram modificados.

### git merge <-branch-> 

- Une as branchs especificadas, trazendo todos os comits da branch mergeada

### git rebase -i <-branch->
  - Server para remover commits especficos da branch

    ### - pick 
      - Mantem o commit
    ### - drop 
      - Remove o commit

### git cherry-pick (Chave-sh1)

- Copia um commit especifico para a branch escolhida .

### .gitignore

- criar um arquivo com este nome, e colocar dentro dele o nome, extenções ou diretorios que deseja ignorar na hora de fazer um puch para o github.

