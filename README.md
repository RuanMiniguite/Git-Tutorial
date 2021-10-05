<div align="center">

# Git-Tutorial
###### Guia Básico, comandos mais utilizados 

</div>

---

<div align="center">

### Configuração Inicial

</div>

**Instalação Git** 

###### Windons
```bash
https://git-scm.com/download/win
```

###### macOS
```bash
https://git-scm.com/download/mac
```
###### Linux
```bash
https://git-scm.com/download/linux
```

<br>

**Configurar Nome e Email do usuário**
```bash
git config --global user.name nome-sobrenome
git config --global user.email email@email.com.br
```

<br>
<div align="center">

### Criar um novo repositório

</div>

**Crie uma nova pasta, execute o comando**
```bash
git init
```

**Link entre o repositório remoto e o local**
```bash
git remote add origin <link-repositório>
```

**Alterar a branch de Master para Main**
```bash
git branch -M main
```

**Clonar repositório, já criado remotamente**
```bash
git clone <link-repositorio>
```

<br>
<div align="center">

### Comando básicos

</div>

**Adicionar todos os arquivos para serem commitados**
```bash
git add .
```

**Commitando os arquivos**
```bash
git commit -m "Mensagem do commit".

```
***Sugestão de [EMOJIS PARA MENSAGEM](https://github.com/RuanMiniguite/Commit-Message)***


**Enviar alteração para repositório remoto**
```bash
git push origin <branch>
```

**Puxar alteração do repositório remoto**
```bash
git pull origin <branch>
```

**Status do repositório**
```bash
git status
```

**Log dos commits**
```bash
git log // todos os commits
git log --oneline // exibe log com hash e título do commit
```

<br>

---

**Livro Pro Git**

Escrito por Scott Chacon e Ben Straub e publicado pela Apress

```bash
http://git-scm.com/book/pt-br/v2
```
