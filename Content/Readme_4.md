<div align="center" id="home">
  
  # Adicionar Commit
  
</div>


<!-- ===== INDEX ===== -->
<details>
  <summary>Index</summary>
  <ol>
    <li><a href="#preparar-para-versionamento">Preparar para versionamento</a></li>
    <li><a href="#realizar-commit">Realizar commit</a></li>
    <li><a href="#sincronizar-mudanças">Sincronizar mudanças</a></li>
  </ol>
</details>


<!-- ===== COMMANDS ===== -->

## Preparar para versionamento
```bash
git add <Arquivo>
```

###### Todos os arquivo do diretorio atual
```bash
git add .
```

<br>

## Realizar commit
###### Caso esteja configurado o editor irá abrir uma janela para escrever a mensagem.
```bash
git commit 
```

###### Comando obtém arquivos do Staging Index e os salva no repositório.
```bash
git commit -m "<Mensagem>"
```

<br>

## Sincronizar mudanças

###### Enviar commits para o repositório remoto
```bash
git push
```

###### Baixar commits do repositório remoto
```bash
git pull
```

###### Baixar commits do repositório remoto mas não incorpora as mudanças
```bash
git fetch
```

<br>

<p align="right">(<a href="https://github.com/RuanMiniguite/Git-Tutorial">back to Home</a>)</p>
