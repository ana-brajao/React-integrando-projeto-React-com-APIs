## Alfood

O projeto tem uma página inicial e ele diz uma lista de restaurante e, para cada restaurante, ele tem uma lista de pratos. Tem mais alguns outros, um restaurante chamado Agarikov e os pratos cadastrados, alguns restaurantes sem pratos.

E o estado inicial não tem nada preparado para aumentar esse número de pratos do restaurante. Então, ele estava estático no código, direto no código, direto na fonte. Ele tinha um array no componente no React.

E o que vamos fazer para poder transformar o site em algo mais dinâmico é trabalhar na área administrativa. Vamos remover toda a parte estática e dizer para o usuário como ele pode fazer para cadastrar novos restaurantes ou remover algum restaurante antigo e vamos dar para ele uma rotina de administração, ou seja, uma área administrativa.

Ele cadastra um restaurante e, automaticamente, aparece na vitrine do site. E como fazemos isso? Vamos colocar para rodar uma API que ela fica rodando, no nosso caso, num ambiente de desenvolvimento na porta 8000.

Então, é uma API pronta que está com o container do DOC que nós subimos para colocar ela para funcionar e temos todos os mecanismos, todos os endpoints necessários para produzir essa área administrativa.

Olhando no código, eu vou soltar um monte de spoiler. No nosso VS Code, vamos ter uma instância do Axios, por exemplo. O Axios vai ser a biblioteca que vamos utilizar para fazer essas requisições.

E o que vamos fazer com essa Lib mega conhecida e mega poderosa? Por exemplo, na administração de pratos, vamos ter um formulário que vamos ter que manipular uma imagem, pegar um input de imagem para enviar para o backend.

Vamos ter que listar restaurantes, enfim, vamos o tempo todo fazer coisas do tipo .get ou .post, também um ponto .delete. Então, vamos fazer várias operações HTTP utilizando o Axios.

Transformar um site, que antes era estático, num CMS, numa área administrativa. E vamos eliminar a necessidade de ter uma pessoa desenvolvedora atualizando ele.

Nós entregamos par ao usuário uma funcionalidade bem completa, onde ele pode pegar ele mesmo e cadastrar novos restaurantes e cadastrar novos pratos. 


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
