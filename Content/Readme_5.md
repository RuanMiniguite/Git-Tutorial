<div align="center" id="home">
  
  # Tagging/Branching/Merging
  
</div>


<!-- ===== INDEX ===== -->
<details>
  <summary>Index</summary>
  <ol>
    <li><a href="#tagging">Tagging</a></li>
    <li><a href="#branching">Branching</a></li>
    <li><a href="#merging">Merging</a></li>
  </ol>
</details>


<!-- ===== COMMANDS ===== -->

## Tagging

###### Exibir as TAG existentes 
```bash
git tag
```

###### Criar uma TAG
```bash
git tag -a <Name-TAG> -m "<Mensagem>"
```

###### TAG no commit expecifico
```bash
git tag -a <Name-TAG> <SHA>
```

###### Remove uma TAG
```bash
git tag -d <Name-TAG>
```

<br>

## Branching

###### Listar as branch | Branch ativa é precedida por "*"
```bash
git branch
```

###### Criar uma nova branch
```bash
git branch <Name-branch>
```

###### Criar e alterar as branch automaticamente
```bash
git checkout -b <Name-nova-branch> <Name-branch-copiada>
```

###### Alterar entre branch
```bash
git checkout <Name-branch>
```

###### Deletar uma branch
```bash
git branch -d <Name-branch>
```

###### *Força a exclusão de uma branch mesmo ela tendo commits que não houveram merger
```bash
git branch -D <Name-branch>
```

<br>

## Merging
###### Combina o histórico do branch específico com o branch atual
```bash
git merge <Name-branch>
```

<br>

<p align="right">(<a href="https://github.com/RuanMiniguite/Git-Tutorial">back to Home</a>)</p>
