<div id="top"></div>

<br />
<div align="center">
  <a href="https://reactnative.dev/">
    <img src="https://d33wubrfki0l68.cloudfront.net/554c3b0e09cf167f0281fda839a5433f2040b349/ecfc9/img/header_logo.svg" alt="Logo React Native" width="80" height="80">
  </a>

<h3 align="center">Serratec Classes</h3>

  <p align="center">
    Projeto feito para aulas em React Native, o mesmo aplicativo foi feito no Expo e no Cli. Um slide para acompanhamento foi criado.
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Tabela de Conteúdos</summary>
  <ol>
    <li>
      <a href="#about-the-project">Sobre o projeto</a>
      <ul>
        <li><a href="#built-with">Feito com</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Iniciando o Projeto</a>
      <ul>
        <li><a href="#prerequisites">Prerequisitos</a></li>
        <li><a href="#installation">Instalação</a></li>
      </ul>
    </li>
    <li>
      <a href="#usage">Uso</a></li>
    <ul>
      <li><a href="#content">Conteúdo</a></li>
      <ul>
        <li><a href="#exercicio-1">Exercicio 1</a></li>
        <li><a href="#exercicio-2">Exercicio 2</a></li>
        <li><a href="#exercicio-3">Exercicio 3</a></li>
        <li><a href="#exercicio-4">Exercicio 4</a></li>
        <li><a href="#exercicio-5">Exercicio 5</a></li>
        <li><a href="#exercicio-6">Exercicio 6</a></li>
      </ul>
    </ul>
    <li><a href="#contribuidores">Contribuidores</a></li>
    <li><a href="#contato">Contato</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## Sobre o Projeto

<div style={{ display: flex, flex-direction: row }}>
  <p>Projeto em react native, usando typescript, onde foi realizado, uma tela que lista os sonhos em cards ordenandos por data e mostra as fases da lua através de uma api, um modal para cadastro de novos sonhos, uma tela que mostra detalhes sonhos, e uma tela mostrando apenas os Sonhos favoritados. Cada card contém um botão de favoritar.</p>

  <!-- TODO: Ter screenshots maneiros -->
  <img src="https://github.com/BragaMPedro/ReactNative_2023-2/blob/main/images/Splashscreen.png?raw=true" alt="Tela Placeholder" width="200" height="500">
 </div>

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

-  [ReactNative](https://reactnative.dev/)
-  React Native Cli
-  [Expo](https://docs.expo.dev/)
-  JavaScript
-  TypeScript
-  [Axios](https://github.com/axios/axios)
-  [react-navigation](https://reactnavigation.org/docs/getting-started/)
-  [React Native SVG](https://github.com/software-mansion/react-native-svg)
-  [React Native Async Storage](https://react-native-async-storage.github.io/async-storage/)
-  [Moon Phases API](http://www.wdisseny.com/lluna/?lang=en)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Iniciando o projeto

Para conseguir rodar o projeto são nescessário alguns pre-requisitos e a instalação do projeto.

### Prerequisites

Todos os pre-requisitos são explicados em aula e o passo a passo também. Seguindo a documentação https://reactnative.dev/docs/environment-setup.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/BragaMPedro/ReactNative_2023-2/
   ```
2. Vá para pasta do exercício que deseja fazer
   ```sh
   cd ReactNative_2023-2/Exercicio_1
   ```
3. Instale os pacotes
   ```sh
   npm install;
   ```
   ou
   ```sh
   yarn install;
   ```
4. Inicie o projeto
   ```sh
   npx expo start;
   ```
   ou (caso de emuladores)
   ```sh
   yarn android;
   ```
   ou
   ```sh
   npm android;
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Uso

Esse é um projeto de ensino e feito para isso. Criado para ensinar a criação de componentes, estilização, utilização de contextos, utilização de banco de dados embarcado, utilização de requisições para API e navegação, utilizando typescrypt para todas as etapas.
Cada pasta contém a etapa anterior completa, e dever ser utilizada para continuar o desenvolvimento do app de acordo com a seção "Conteúdo" deste material.

### Exercícios

#### Exercicio 1
<div style={{ display: flex, flex-direction: row }}>
  <p>
    No Exercício 1 o objetivo é criar o projeto e fazer um clone visual da tela abaixo. Não é necessário que existam funções atreladas aos botões e aos Input
  </p>

  <img src="https://github.com/BragaMPedro/ReactNative_2023-2/blob/main/images/Exercício_2-Ref/Exercício_2-Ref.jpeg?raw=true" alt="Tela Inicial clone visual" width="200" height="500">
 </div>

#### Exercicio 2
<div style={{ display: flex, flex-direction: row }}>
  <p>
    No Exercício 2 o objetivo será componentizar a tela anteriormente criada, agora dando funções às partes necessárias. Sendo possível cadastrar e adicionar um sonho a uma lista que será mostrada na página inicial.
    <h5> Requisitos </h5>
    <ul>
      <li> cadastro feito através dos inputs </li>
      <li> os sonhos devem ser exibidos em cards </li>
      <li> o container dos cards deve conter scroll </li>
      <li> caso necessário usar o componente KeyboardAvoidView </li>
    </ul>
  </p>

  <div>
    <img src="https://github.com/BragaMPedro/ReactNative_2023-2/blob/main/images/WhatsApp Image 2023-11-07 at 12.46.54 (4).jpeg?raw=true" alt="Tela Inicial sem dados" width="200" height="500">
<img src="https://github.com/BragaMPedro/ReactNative_2023-2/blob/main/images/Exercício_2-Ref/Exercício_2-Ref.jpeg?raw=true" alt="Tela Inicial clone visual" width="200" height="500">
  </div>
</div>

#### Exercicio 3
<div style={{ display: flex, flex-direction: row }}>
  <p>
    No Exercício 3 deverá ser feita uma navegação até uma uma tela de Detalhes dos sonhos, e uma tela de Favoritos onde posteriormente serão inseridos a lista de sonhos "favoritados".
    <h5> Requisitos </h5>
    <ul>
      <li> a navegação para a páginas de detalhes deve ser feita através de um onPress, ou onLongPress, no Card de Sonho </li>
      <li> navegação para tela de favoritos </li>
      <li> na tela de Detalhes de sonhos deve haver botão "Editar" </li>
      <li> na tela de Detalhes deve existir um botão de "voltar" </li>
    </ul>
  </p>

  <img src="https://github.com/BragaMPedro/ReactNative_2023-2/blob/main/images/WhatsApp Image 2023-11-07 at 12.46.54 (2).jpeg?raw=true" alt="Tela inicial sem dados" width="200" height="500">
  <img src="https://github.com/BragaMPedro/ReactNative_2023-2/blob/main/images/WhatsApp Image 2023-11-07 at 12.46.54 (1).jpeg?raw=true" alt="Tela inicial com dados" width="200" height="500">
  <img src="https://github.com/BragaMPedro/ReactNative_2023-2/blob/main/images/WhatsApp Image 2023-11-07 at 12.46.54 (3).jpeg?raw=true" alt="Tela Detalhes" width="200" height="500">
  <img src="https://github.com/BragaMPedro/ReactNative_2023-2/blob/main/images/Exercicio_4-Ref/Tela_3-favoritos.jpeg?raw=true" alt="Tela Favoritos sem dados" width="200" height="500">
 </div>

#### Exercicio 4
<div style={{ display: flex, flex-direction: row }}>
  <p>
    No Exercício 4 deverá ser criado um service para requisições utilizando a <a href="http://www.wdisseny.com/lluna/?lang=en">MoonPhaseAPI</a>. na tela inicial, acima do botão "Adicionar Sonho" deverá ser exibida fase da lua do dia atual, juntamente com o ano, mês, dia do mês e da semana.
    O form de cadastro será refatorado em um modal que também será usado na páfina de detalhes para editar o sonho. E o tipo sonho terá propriedades adicionais
    <h5> Requisitos </h5>
    <ul>
      <li> deverá ser utilizada a biblioteca <a href="https://github.com/software-mansion/react-native-svg">React Native SVG</a> para a exibição da imagem mostrando a fase atual da Lua </li>
      <li> atualizar tipo sonho com as propriedades Data, e Tags. </li>
      <li> refatorar card de sonho, e tela detalhes, para incluir as novas propriedades </li>
      <li> cadastro agors deverá ser feito através de um modal </li>
      <li> data deve sempre iniciar com a data atual </li>
      <li> adicionar e retirar Tags durante o cadastro, tendo um máximo de 3 tags por sonho </li>
      <li> ao serem adicionada deve ser possível ver as tags já cadastradas </li>
    </ul> 
  </p>

  <img src="https://github.com/BragaMPedro/ReactNative_2023-2/blob/main/images/Exercicio_5-Ref/FasesDaLuaAPI.jpeg?raw=true" alt="modal-1" width="200" height="500">
  <img src="https://github.com/BragaMPedro/ReactNative_2023-2/blob/main/images/Exercicio_6-Ref/Tela_1-FavoritosImplemented.jpeg?raw=true" alt="modal-3" width="200" height="500">
  <img src="https://github.com/BragaMPedro/ReactNative_2023-2/blob/main/images/Exercicio_3-Ref/modal-1.jpeg?raw=true" alt="Tela Inicial com API" width="200" height="500">
   <img src="https://github.com/BragaMPedro/ReactNative_2023-2/blob/main/images/Exercicio_3-Ref/modal-2.jpeg?raw=true" alt="modal-2" width="200" height="500">
   <img src="https://github.com/BragaMPedro/ReactNative_2023-2/blob/main/images/Exercicio_3-Ref/modal-3.jpeg?raw=true" alt="modal-3" width="200" height="500">
  <img src="https://github.com/BragaMPedro/ReactNative_2023-2/blob/main/images/Exercicio_4-Ref/Tela_2-Detalhes.jpeg?raw=true" alt="modal-3" width="200" height="500">
   </div>

#### Exercicio 5
<div style={{ display: flex, flex-direction: row }}>
  <p>
    No Exercício 5 deverá ser criado um Contexto que contenha os métodos relacionados às operações com a lista de sonhos. Esses métodos deverão ser implementados nos componentes nosnecessários já existentes.
    Os sonhos favoritados deverão ser exibidos na tela anteriormente criada para eles.(<a href="#exercicio-3"> ver Exercício 3 </a>)
    <h5> Requisitos </h5>
    <ul>
      <li> o state contendo a Lista de Sonhos deverá ser instanciado no Contexto </li>
      <li> o contexto deverá conter um método para adicionar Sonho </li>
      <li> o contexto deverá conter um método para editar </li>
      <li> o contexto deverá conter um método para atualizar a propriedade "favorito" dos sonhos </li>
      <li> a tela de Favoritos agora deverá mostrar uma lista contendo apenas os sonhos Favoritados </li>
      <li> deverá ser implementado um método que ordene as listas de sonhos, e sonhos favoritos, de acordo com a sua data </li>
      <li> caso a propriedade "favorito" de um sonho seja alterada ele deve ser retirado da lista de favoritos </li>
      <li> o compoente(s) responsável por editar e adicionar sonhos deverá ser refatorado para utilizar os métodos do contexto </li>
    </ul> 
  </p>
  </p>

  <img src="https://github.com/BragaMPedro/ReactNative_2023-2/blob/main/images/Exercicio_6-Ref/Tela_1-FavoritosImplemented.jpeg?raw=true" alt="Tela Inicial com favoritos" width="200" height="500">
  <img src="https://github.com/BragaMPedro/ReactNative_2023-2/blob/main/images/Exercicio_6-Ref/Tela_3-favoritosTrue.jpeg?raw=true" alt="Tela Favoritos" width="200" height="500">
 </div>

#### Exercicio 6
<div style={{ display: flex, flex-direction: row }}>
  <p>
    Por fim Exercício 6 será feita a integração com o banco de dados embarcado. Deverá ser utilizado o <a href="https://react-native-async-storage.github.io/async-storage/docs/install/">React Native Async Storage</a> para guardar sonhos criados, e suas possíveis alterações.
    <h5> Requisitos </h5>
    <ul>
      <li> os métodos do contexto que alteram o estado da lista de sonho ou suas propriedades terão que salvar as mudanças no Async Storage </li>
      <li> deverá existir um método para trazer os dados salvos no Async Storage para serem exibidos em tela</li>
    </ul>
  </p>
 </div>

<p align="right">(<a href="#top">back to top</a>)</p>

## Contribuidores
<table>
  <tr>
    <td align="center">
      <a href="https://www.linkedin.com/in/frederico-sheremetieff-0a6759190/">
        <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/82114311?v=4" width="100px;" alt=""/>
        <br />
        <sub><b>Frederico Sheremetieff</b></sub>
      </a>
      <br />
       <br />
      <a href="https://www.linkedin.com/in/frederico-sheremetieff-0a6759190/" title="LindedIn">
        <img src="https://img.shields.io/badge/-Frederico-blue?style=flat-square&logo=Linkedin&logoColor=white" />
      </a>
    </td>
    <td align="center">
      <a href="https://www.linkedin.com/in/pedrobragaresume/">
        <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/111090976?v=4" width="100px;" alt=""/>
        <br />
        <sub><b>Pedro Braga</b></sub>
      </a>
      <br />
       <br />
      <a href="https://www.linkedin.com/in/pedrobragaresume/" title="LindedIn">
        <img src="https://img.shields.io/badge/-Pedro-blue?style=flat-square&logo=Linkedin&logoColor=white" />
      </a>
    </td>
  </tr>
</table>

<!-- CONTACT -->

## Contato

Frederico Henrichs Sheremetieff - frederico.shere@gmail.com

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
