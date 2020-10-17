<h1 align="center">
  <img align="center" src="./src/images/Logo.png" alt="logo">
</h1>

<H3 align="center">
  Um projeto desenvolvido durante a terceira edição da Next_Level_Week(NLW) um evento gratuito promovido pela Rocketseat <br>
</h3>

<br >

<p align="center">
  <a style="color:#ffd666" href="#computer-tecnologias-usadas-neste-projeto">tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a style="color:#ffd666" href="#rocket-como-rodar">Como usar</a>
</p>


<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/AlexBitar80/NLW-03-happy-web.svg">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/AlexBitar80/NLW-03-happy-web.svg">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/AlexBitar80/NLW-03-happy-web.svg">
  <a href="https://github.com/AlexBitar80/NLW-03-happy-web/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/AlexBitar80/NLW-03-happy-web.svg">
  </a>

  <a href="https://github.com/AlexBitar80/NLW-03-happy-web/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/AlexBitar80/NLW-03-happy-web.svg">
  </a>
</p>


<h3 style="font-size: 16px; font-weight: 400">Em homenagem ao dia 12 de outubro (dia das criaças) este é um projeto para aproximar pessoas a criaças que estão em orfanatos e precisando de sua visita.</h3>

<br>
<br>

<p align="center" style="font-size: 20px; font-weight: 800">Tela inicial</p>

![Captura de tela de 2020-10-13 12-51-34](https://user-images.githubusercontent.com/56983783/95884755-dd86a400-0d52-11eb-9509-ec93325ea285.png)

<p align="center" style="font-size: 20px; font-weight: 800">Vizualizar orfanatos próximos</p>

![Captura de tela de 2020-10-17 00-07-17](https://user-images.githubusercontent.com/56983783/96327089-ca9ef880-100c-11eb-8dcf-55ac088f03d2.png)

<p align="center" style="font-size: 20px; font-weight: 800">Novo cadastro de orfanato</p>

![Captura de tela de 2020-10-16 23-45-36](https://user-images.githubusercontent.com/56983783/96326774-ece34700-1009-11eb-9dbf-4e5ead64ebf9.png)

![Captura de tela de 2020-10-16 23-45-43](https://user-images.githubusercontent.com/56983783/96326793-100df680-100a-11eb-97b0-cdedba1310f2.png)

![Captura de tela de 2020-10-16 23-45-48](https://user-images.githubusercontent.com/56983783/96326813-5d8a6380-100a-11eb-898d-f8b1184baf1e.png)

<p align="center" style="font-size: 20px; font-weight: 800">Tela de vizualização de orfanato</p>

![Captura de tela de 2020-10-16 23-43-27](https://user-images.githubusercontent.com/56983783/96326801-316ee280-100a-11eb-9dd2-9ad62cea7831.png)

![Captura de tela de 2020-10-16 23-43-49](https://user-images.githubusercontent.com/56983783/96326810-4481b280-100a-11eb-9650-98848a7d582f.png)


## :computer: Tecnologias usadas neste projeto

O projeto está sendo desenvolvido utilizando as seguintes tecnologias:

-  [TypeScript](https://www.typescriptlang.org/)
-  [ReactJS](https://pt-br.reactjs.org/)
-  [React-Leaflet](https://react-leaflet.js.org/)
-  [Axios](https://github.com/axios/axios)
-  [Eslint](https://eslint.org/)
-  [Prettier](https://prettier.io/)
-  [React-Router-DOM](https://reactrouter.com/web/guides/quick-start)


## :rocket: Como rodar

 Para clonar e rodar esse projeto você vai precisar do [Yarn](https://yarnpkg.com/) do [Npm](https://www.npmjs.com/get-npm) e do [Git](https://git-scm.com/) instalado na rua máquina

```bash
# Faça o clone deste repositório para qualquer pasta de sua preferencia
$ git clone https://github.com/AlexBitar80/NLW-03-happy-web

# Vá até essa pasta
$ cd (pasta que foi clonada)

# rode esses comandos para instalar as dependências
$ yarn ou npm install

# na raiz do projeto crie um arquivo chamado (.env) e nele coloque o seguinte comando
REACT_APP_MAPBOX_TOKEN=(Seu token usada no MapBox que será usado para gerar o mapa)

# use esses comandos para rodar o projeto em seu navegador
$ yarn start ou npm start
