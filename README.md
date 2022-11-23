![](./hd-header.png)

### Git e Github | Atividade em dupla

<details>
<summary>Integrante 1 - Criando repositório</summary>

> Um dos integrantes da dupla, deve compartilhar a tela e criar um repositório com o seguinte nome `selecao-brasileira` na sua conta do github, ele deve está como `public`
</details>

<details>
<summary>Integrante 1 - Clonando e adicionando arquivo</summary>

> Após criar o repositório, você deve realizado o clone, feito isso, você deve aidionar um arquivo chamado `escalacao.txt` e adicionar o texto abaixo:

```txt

- Goleiros: Alisson (Liverpool-ING), Ederson (Manchester City-ING) e Weverton (Palmeiras) 
- Laterais-direitos: Daniel Alves (Pumas-MEX) e Danilo (Juventus-ITA) 
- Laterais-esquerdos: Alex Sandro (Juventus-ITA) e Alex Telles (Sevilla-ESP) 
- Zagueiros: Bremer (Juventus-ITA), Éder Militão (Real Madrid-ESP), Marquinhos (PSG-FRA) e Thiago Silva (Chelsea-ING)
```

> Após abrir o arquivo e adicionar a lista com a escalação da seleção brasileira, salve-o e depois envie tudo para o repositório remoto

> Depois você deve enviar o link do seu repositório para o outro integrante
</details>

<details>
<summary>Integrante 2 - Fazendo fork</summary>

> O outro integrante, deve acessar o repositório e realizar o fork, após ter feito o fork, clonar o repositório local
</details>

<details>
<summary>Integrante 2 - Alterando arquivo</summary>

> Após clonar, você deve abrir o arquivo e adicionar no final da lista o restante da escalação:

```txt
- Volantes: Bruno Guimarães (Newcastle-ING), Casemiro (Manchester United-ING), Fabinho (Liverpool-ING) e Fred (Manchester United-ING) 
- Meias: Everton Ribeiro (Flamengo) e Lucas Paquetá (West Ham-ING) 
- Atacantes: Antony (Manchester United-ING), Gabriel Jesus (Arsenal-ING), Gabriel Martinelli (Arsenal-ING), Neymar (PSG-FRA), Pedro (Flamengo)
```

> Salve-o e depois envie para o repositório remoto
</details>

<details>
<summary>Integrante 2 - Pull Request</summary>

> Deve acessar o repositório que foi feito o fork e realizar o pull request das alterações
</details>

<details>
<summary>Integrante 1 - Code Review e Merge</summary>

> Deve acessar os pull request do repositório, realizar o code review e depois fazer o merge
</details>

-------------------------------------------------------
<details>
<summary>Extra - Gerando Chave SSH e Vinculando com o Github</summary>


- Passo 1: Abrir o terminal do windows como administrador
- Passo 2: Executar o seguinte comando no terminal `ssh-keygen`
- Passo 3: Vai aparecer o local onde ficará salvo o par de chaves ssh, basta apertar `Enter`
- Passo 4: Depois será solicitado para digitar a senha, coloque a mesma senha de acesso do seu computador
- Passo 5: Repita a senha
- Passo 6: Acesse o diretório onde ficou salvo o par de chaves ssh e abra o arquivo `id_rsa.pub`
- Passo 7: Copie o conteúdo existente e feche o arquivo
- Passo 8: Acesse sua conta do github e depois acesso as configurações da conta
    > Para acessar as configurações, basta você clicar no ícone superior direito, onde tem a foto do perfil da conta, clique na seta ao lado e depois localize a opção `settings`
- Passo 9: Após acessar as configurações, localize no menu vertical esquerdo a opção `SSH and GPG Keys` e clique nela
- Passo 10: Clique na opção `New SSH Key`, vai aparecer o local para colocar um título (`title`) e uma chave (`key`)
- Passo 11: Coloque o no título `Windows` e na chave, você deve colar o conteúdo que você copiou lá no passo 7
- Passo 12: Clique o botão `Add SSH Key`
</details>

<details>
<summary>Extra - Extensões para <b>chrome</b></summary>


- [Blackbox](https://www.useblackbox.io/)
    > Use o Blackbox para selecionar o código que deseja copiar de qualquer vídeo que estiver assistindo e simplesmente cole-o em seu editor de texto…. Funciona como mágica!
- [Grepper](https://chrome.google.com/webstore/detail/grepper/amaaokahonnfjjemodnpmeenfpnnbkco)
    > Obtenha facilmente exemplos de código em toda a Web e acesse seus exemplos de código sem ter que pensar.

</details>

###### tags: `git` `github` `commit` `merge` `pull request` `fork`