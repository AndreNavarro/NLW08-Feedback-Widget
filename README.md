<h1 align="center">
  Feedback Widget
</h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-conceitos">Conceitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar">Como executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

<br>

<p align="center">
  <img alt="Imagem da aplicação web e mobile funcionando" src="assets/presentation-full.png" width="100%">
</p>

## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

### Front-end:
- [React.js](https://pt-br.reactjs.org/)
- [Typescript](https://www.typescriptlang.org/)
- [HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [Tailwind CSS](https://tailwindcss.com/)

### Back-end:
- [Node.js](https://nodejs.org/en/)
- [Prisma](https://www.prisma.io/)
- [Express](https://expressjs.com/pt-br/)

### Mobile
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)


## 💻 Projeto

Este projeto foi desenvolvido durante o evento **NLW Return**, tendo como objetivo o envio de feedbacks do site, podendo ser um registro de bug, uma nova ideia ou então outro assunto.

Utilizado cada uma destas categorias, é possível inserir uma mensagem de texto e também uma screenshot para o registro e envio do feedback. Ao clicar em enviar, uma funcionalidade de e-mail fará o envio à uma caixa de e-mails cadastrada.

O projeto está separado em desenvolvimento Front-end utilizando React, desenvolvimento Back-end utilizando NodeJS e desenvolvimento mobile utilizando React Native.


## 📚 Conceitos

### <u>Tailwind</u>
Framework de CSS para utilização diretamente como classe. Ao definir uma tag HTML, é possível que sejam acrescentadas classes que representem uma estilização CSS, sem que haja a necessidade de (re)definição de suas configurações.

Por padrão, o Tailwind possui alguns valores, porém, é possível que estes valores sejam redefinidos, bem como é possível também que outros valores sejam criados para que possam ser utilziados como classes.

### <u>SOLID</u>
<b>Single Responsibility Principle</b>
* Cada classe tem uma responsabilidade única.

<b>Open/Close Principle</b>
* As classes da aplicação devem ser abertas para extensão mas fechadas para modificação.

<b>Liskov Substitution Principle</b>
* Deverá ser possível substituir uma classe pai por uma herança dela e tudo suas funções funcionando normalmente.

<b>Interface Segregation Principle</b>
* Separar o máximo possível as interfaces que a classe deverá implementar.

<b>Dependency Inversion Principle</b>
* Ao invés da classe buscar quais dependências ela precisa, o contexto externo à ela indicar quais dependências ela vai usar.


### <u>Testes unitários</u>
Consistem no desenvolvimento de testes para a menor parte testável de um código. Ou seja, o teste pode ser desenvolvido com a finalidade de testar apenas uma função por vez, sem que hajam chamadas externas a ela, ou persistências em banco ou até mesmo conexão com outras APIs. Este teste é realizado a fim de validar os dados e retornos tanto para dados válidos quanto para dados inválidos, testando a execução do código como verdadeiro e também testando a execução com a geração de exceções.


## 🔖 Layout

Você pode visualizar o layout do projeto, tanto a versão web quanto a versão mobile, através [desse link](https://www.figma.com/file/34AG4OcNVekDv6K79HUcot/NLW%2308---Feedback-Widget---NLW-Return?node-id=7%3A3). É necessário ter conta no [Figma](https://figma.com) para acessá-lo.

## 🚀 Como Executar

* 🌐 **Conectando-se à aplicação online**
    * Para acessar ao projeto em execução no ambiente da Vercel, acesse um dos seguintes links:

        [Link 1](https://feedback-widget-roan.vercel.app) / [Link 2](https://feedback-widget-git-main-andrenavarro.vercel.app) / [Link 3](https://feedback-widget-andrenavarro.vercel.app)

    * Feito isso, a página aparecerá sem nenhum conteúdo além do ícone no canto inferior direito. Clicando sobre ele, será possível visualizar as opções de feedback.

<br>

* 🧑‍💻 **Conectando-se à aplicação localmente**
    * No [Github](https://github.com/AndreNavarro/NLW08-Feedback-Widget), faça um clone deste projeto em sua máquina com o seguinte comando:
        ```
        git clone https://github.com/AndreNavarro/NLW08-Feedback-Widget.git
        ```
    * Verá que há três pastas, uma referente à aplicação web, uma à mobile e uma referente à api back-end, que é utilizada tanto para web quanto mobile.
    * Faça uma cópia dos arquivos .env.local (pasta web) e .env (pasta server) e renomeie ambos removendo o nome "-sample". É necessário que sejam preenchidos os dados dentro destes arquivos.

  * 🖥️ **Aplicação web**  
    * Execute ```npm run dev``` tanto no diretório da api back-end quanto no projeto front-end para iniciar a aplicação.
    * A aplicação estará disponível em http://localhost:3000

  * 📱 **Aplicação mobile**
    * Execute ```expo start``` e com seu emulador ou smartphone com app do Expo instalado, acesse via QR Code a aplicação.


## 📝 Licença

Projeto desenvolvido pela Rocketseat e apresentado na **Next Level Week - Return** (nlw #08).