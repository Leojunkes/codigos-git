# Códigos-Git
códigos úteis no GIT

Ajuda comandos específicos:

   `git help add`
   `git help commit`
   `git help <qualquer comando git>`
   
   
Setar Usuário:

```git config --global user.name "seu nome"```

Setar Email:
   
```git config --global user.email "seu email"```

Setar editor:

```git config --global core.editor seu editor```

Setar ferramenta de de merge:

```git config --global merge.tool vimdiff```

Setar arquivos a serem ignorados:

```git config --global core.excludesfile ~/.gitignore```

Listar configurações:

```git config --listgit```

Criar novo repositório Local:

```git init```

Verificar estado dos arquivos/diretórios:

```git status```

Adicionar um arquivo em específico:

```git add meu_arquivo.txt```

Exibir histórico com diff das duas últimas alterações:

```git log -p -2```

Exibir histório de um arquivo específico:

```git log -- <caminho_do_arquivo>```

Desfazendo alteração local (working directory) OBS: quando o arquivo não foi adicionado na estaged area:

```git checkout -- meu_arquivo.txt```

Desfazendo alteração local (staging area):

```git reset HEAD meu_arquivo.txt```

A alteração do diretório pode ser realizada através do comando abaixo:

```git checkout meu_arquivo.txt```

Repositório Remoto:

```git remote```

Exibir os repositórios remotos:

```git remote -v```

Vincular repositório local com um repositório remoto

`git remote add origin git@github.com:Leojunkes/seuRepositório`

Exibir informações dos repositórios remotos

`git remote show origin`

Renomear um repositório remoto

`git remote rename origin curso-git`

Desvincular um repositório remoto

`git remote rm curso-git`

O primeiro push de um repositório deve conter o nome do repositório remoto e o branch.

`git push -u origin main` 

Os demais pushes não precisam dessa informação

`git push`

Atualizar os arquivos no branch atual

`git pull`

Clonar um repositório remoto já existente

`git clone git@github.com:leocomelli/seuRepositório.git`






