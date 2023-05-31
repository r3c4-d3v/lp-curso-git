# Curso de git

### Criamos um repositório e enviamos nosso projeto desenvolvido em outro curso de html e css.  
<br>

Gera a chave com o email cadastrado no github
```
ssh-keygen -t ed25519 -C "email@cadastrado.com"
```
Inicia o ssh-agent
```
eval "$(ssh-agent -s)"
```
Adiciona a chave ao agente
```
ssh-add ~/.ssh/id_ed25519
```

<br>

## Comandos GIT

```
git status
```

inicializa o git na pasta que o comando for executado
```
git init
```

adiciona os arquivos selecionados
```
git add nome_do_arquivo nome-do-outro-arquivo
```

Adiciona todos os arquivos na pasta atual
```
git add . 
```

Cria um commit o -m é o parametro que indica a mensagem
```
git commit -m "mensagem do commit"
```

Cria uma nova branch e efetua a troca para essa branch
```
git checkout -b nome-da-branch
```

Efetua a troca para e branch designada
```
git checkout nome-da-branch
```

Aponta para o repositório no github
```
git remote add origin git@github.com:r3c4-d3v/lp-curso-git.git
```

Esta linha é apenas para criarmos mais um commit
