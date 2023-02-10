<div align="center" id="home">
  
  # Desfazer alterações
  
</div>


<!-- ===== INDEX ===== -->
<details>
  <summary>Index</summary>
  <ol>
    <li><a href="#desfazer-adição">Desfazer adição</a></li>
    <li><a href="#desfazer-commit">Desfazer commit</a></li>
    <li><a href="#desfazer-merger">Desfazer merger</a></li>
  </ol>
</details>


<!-- ===== COMMANDS ===== -->

## Desfazer adição
```bash
git reset <Nome-arquivo>
```

###### Remove o arquivo do controle de versão mas preserva o arquivo localmente
```bash
git rm --cached <Nome-arquivo>
```

<br>

## Desfazer commit
```bash
git reset <SHA>
```

###### Descarta todo histórico e mudanças para o commit especificado
```bash
git reset --hard [commit]
```

###### Alterar o commit mais recente 
```bash
git commit --amend 
```

<br>

## Desfazer merger
```bash
git reset --hard HEAD^
```




<br>

<p align="right">(<a href="https://github.com/RuanMiniguite/Git-Tutorial">back to Home</a>)</p>
