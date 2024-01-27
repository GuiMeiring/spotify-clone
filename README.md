# Spotify Clone

Este é um projeto desenvolvido durante a Imersão Front-End da Alura, com o objetivo de criar um clone do visual do Spotify.

## Sobre o Projeto

O projeto consiste em criar um site inspirado no design do Spotify, utilizando HTML, CSS e JavaScript. Durante a imersão, foram abordados conceitos como CSS Grid, media queries e manipulação do DOM via JavaScript.

O site possui uma barra de navegação lateral, onde é possível acessar as páginas de Início e Buscar. Na página de Início, são exibidas playlists fictícias. Já na página de Buscar, é possível pesquisar por artistas e exibir suas informações.

## Como Executar

1. Clone o repositório para a sua máquina local:
   
  ```bash
    git clone https://github.com/GuiMeiring/spotify-clone.git
  ````
2. Navegue até o diretório do projeto:

  ```bash
    cd spotify-clone
   ````
3. Abra o arquivo `index.html` no seu navegador de preferência.

## Configurção JSON Server (Back-end Fake)

### Pré-requisitos

Antes de começar, certifique-se de que você tenha o Node.js e o NPM (Node Package Manager) instalados em sua máquina. Você pode baixá-los e instalá-los a partir do site oficial: [Node.js](https://nodejs.org/).

### Executando o JSON Server

1. Instale o pacote utilizando o npm:
   
   ```bash
     npm install -g json-server@0.17.4
   ```
   Obs.: Digita json-server --version se a versão que tiver lá for maior ou igual a 1.0 quer dizer que você está usando uma versão alfa.
   Então, usa o comando npm uninstall -g json-server desinstalar e depois npm install -g json-server@0.17.4 para instalar uma versão especifica que não está na versão alfa

2. Suba o servidor:
   
   ```bash
     npx json-server --watch api-artists/artists.json --port 3000
   ```
## Tecnologias Utilizadas

- HTML
- CSS
- JavaScript

## Contribuição

Contribuições são sempre bem-vindas! Se você encontrou algum bug, tem alguma sugestão de melhoria ou deseja adicionar uma nova funcionalidade, fique à vontade para abrir uma issue ou enviar um pull request.
