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

## Alterar mensagens de um ou mais commits
###### Verifique o <a href="">editor global</a>
```bash
git rebase -i HEAD~3
```
###### *Substitua pick por reword antes de cada mensagem, de commit que deseja alterar e salve o arquivo.*
###### *Substitua a mensgem antiga pela nova em cada arquivo e salve.*
```bash
git push --force 
```

<br>

## Desfazer merger
```bash
git reset --hard HEAD^
```




<br>

<p align="right">(<a href="https://github.com/RuanMiniguite/Git-Tutorial">back to Home</a>)</p>
