# MERN: aplicativo de bate-papo

#### Introdução

A aplicação MERN, que consiste em **Mongo DB**, **Express.js**, **Node.js** e **React.js**, é uma aplicação popular para criar aplicativos baseados na web de aplicação completa devido à sua simplicidade e facilidade de uso. Nos últimos anos, com a popularidade explosiva e a crescente maturidade do ecossistema JavaScript, a aplicação MERN tem sido a aplicação goto para um grande número de aplicações web. 
<br/><br/>
Este repositório consiste em um **aplicativo de bate-papo** criado com a aplicação MERN. Eu construí isso algum tempo atrás quando estava tentando aprender a aplicação e deixei aqui para qualquer um novo na aplicação para que eles possam usar este repositório como um guia.
<br/><br/>
Este é um aplicativo de bate-papo completo que pode ser instalado e executado com apenas algumas etapas.
Seu front-end é construído com [Material UI](https://material-ui.com/) rodando sobre React.
O back-end é construído com Express.js e Node.js.
A transmissão de mensagens em tempo real é desenvolvida usando [Socket.IO](https://socket.io/).

### Características

Este aplicativo fornece aos usuários os seguintes recursos
<br/>
* Autenticação usando **Tokens JWT**
* Um **Global Chat** que pode ser usado por qualquer pessoa usando o aplicativo para transmitir mensagens para todos os outros.
* Uma funcionalidade de **Bate-papo privado** onde os usuários podem conversar com outros usuários em particular.
* Atualizações em tempo real na lista de usuários, lista de conversas e mensagens de conversas

#### Capturas de tela

##### Bate-papo global
![Bate-papo global](https://i.imgur.com/VkdwAme.png)
<br/><br/>
##### Conversa privada
![Chat Privado](https://i.imgur.com/jdCBYu4.png)
<br/><br/>
##### Conecte-se
![Login](https://i.imgur.com/6iobucn.png)
<br/><br/>
##### Registro
![Cadastre-se](https://i.imgur.com/AMkpl9C.png)

### Como usar

Você pode ter este aplicativo instalado e funcionando com apenas alguns passos porque ele tem o front-end e o back-end em um único repositório. Siga as etapas abaixo para fazer isso.

1. Clone este repositório
2. Depois de ter o repositório, você precisa instalar suas dependências. Então, usando um terminal, vá para o diretório raiz do projeto e execute `npm install` para instalar as dependências do servidor Node.js e depois execute `npm run client-install` para instalar as dependências do frontend. O segundo comando é um comando personalizado que escrevi para simplificar o processo de instalação.
3. Este aplicativo usa o MongoDB como banco de dados. Portanto, certifique-se de tê-lo instalado. Você pode encontrar guias detalhados sobre como fazer isso [aqui](https://docs.mongodb.com/manual/administration/install-community/). Depois de instalado, certifique-se de que seu servidor MongoDB local não esteja protegido por nenhum tipo de autenticação. Se houver autenticação envolvida, certifique-se de editar o `mongoURI` no arquivo `config/keys.js`.
4. Finalmente, tudo o que você precisa fazer é simplesmente executar `npm run dev`. Se este comando falhar, tente instalar o pacote [simultaneamente](https://www.npmjs.com/package/concurrently) globalmente executando `npm install -g simultaneamente` e, em seguida, executando o comando `dev`.
5. O front-end do aplicativo será aberto automaticamente em seu navegador da Web e você poderá testá-lo.


### Coisas a observar

* O frontend é criado usando [create-react-app](https://github.com/facebook/create-react-app)
* As conexões de banco de dados no back-end são tratadas usando o [Mongoose ORM](https://mongoosejs.com/)
* A qualidade do código é garantida usando (ESLint)[https://eslint.org/]

# Chat-BOT 💻 🍺 🔥 🙌
