<div align="center" id="home">
  
  # Histórico
  
</div>


<!-- ===== INDEX ===== -->
<details>
  <summary>Index</summary>
  <ol>
    <li><a href="#lista-todos-os-arquivos-novos-ou-modificados">Lista todos os arquivos novos ou modificados</a></li>
    <li><a href="#visualizar-alterações">Visualizar alterações</a></li>
    <li><a href="#histórico-de-versões ">Histórico de versões </a></li>
  </ol>
</details>


<!-- ===== COMMANDS ===== -->

## Lista todos os arquivos novos ou modificados
```bash
git status
```

<br>

## Visualizar alterações
###### *Visualizar as alterações que foram feitas, mas ainda não foram confirmadas*
```bash
git diff
```
###### *Mostra a diferença entre as branch*
```bash
git diff [primerio-branch]...[segundo-branch]
```

<br>

## Histórico de versões 
###### *Branch atual*
```bash
git log
```

###### Lista de forma resumida (SHA -> MSG)
```bash
git log --oneline
```

###### Lista os commit e as linhas alteradas
```bash
git log -p
```

```bash
git log --stat
```

###### Lista apartir de um commit especifico e seus anteriores
```bash
git log <SHA>
```


###### Retorna mudanças de metadata e conteúdo para o commit especificado
```bash
git show <SHA>
```

<br>

<p align="right">(<a href="https://github.com/RuanMiniguite/Git-Tutorial">back to Home</a>)</p>
