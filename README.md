# GoBarber

<h3 align="center">
   APP utilizado para agendar o corte na barbearia.<br>Clientes podem escolher o barbero, a data e o horário do serviço desejado. Após o agendamento todos agendamentos são listados.
   <br><br>Na versão Web as barbearias tem controle de seus serviços, listando os clientes agendados por horário e por data para cada prestador de serviço.
   <br><br>
</h3>


<img src="https://github.com/cleberbonifacio/gobarber/blob/master/assets/barbeiro.png" width="290"><img src="https://github.com/cleberbonifacio/gobarber/blob/master/assets/horario.png" width="290"><img src="https://github.com/cleberbonifacio/gobarber/blob/master/assets/agendamentos.png" width="290">



<img src="https://github.com/cleberbonifacio/gobarber/blob/master/assets/login.png">
<img src="https://github.com/cleberbonifacio/gobarber/blob/master/assets/profile.png">

<img src="https://github.com/cleberbonifacio/gobarber/blob/master/assets/dashboard.PNG">
<img src="https://github.com/cleberbonifacio/gobarber/blob/master/assets/perfil.png">


## Tecnologias

Para o desenvolvimento da aplicação foi utilizada a stack: Node.JS, ReactJS e React Native para o backend, front-end e mobile(android) respectivamente.

### FRONT-END
-   [ReactJS](https://reactjs.org/)
-   [Redux](https://redux.js.org/)
-   [Redux-Saga](https://redux-saga.js.org/)
-   [React Router v4](https://github.com/ReactTraining/react-router)
-   [styled-components](https://www.styled-components.com/)
-   [Axios](https://github.com/axios/axios)
-   [History](https://www.npmjs.com/package/history)
-   [Immer](https://github.com/immerjs/immer)
-   [Polished](https://polished.js.org/)
-   [React-Toastify](https://fkhadra.github.io/react-toastify/)
-   [React-Icons](http://react-icons.github.io/react-icons/)
-   [react-perfect-scrollbar](https://github.com/OpusCapita/react-perfect-scrollbar)
-   [Unform](https://github.com/Rocketseat/unform)
-   [Yup](https://www.npmjs.com/package/yup)
-   [date-fns](https://date-fns.org/)
-   [Reactotron](https://infinite.red/reactotron)
-   [VS Code][vc] with [EditorConfig][vceditconfig] and [ESLint][vceslint]

### MOBILE
-   [ReactJS](https://reactjs.org/)
-   [React Native](https://facebook.github.io/react-native/)
-   [styled-components](https://www.styled-components.com/)
-   [Axios](https://github.com/axios/axios)
-   [Polished](https://polished.js.org/)
-   [React-Icons](http://react-icons.github.io/react-icons/)
-   [react-perfect-scrollbar](https://github.com/OpusCapita/react-perfect-scrollbar)
-   [Unform](https://github.com/Rocketseat/unform)
-   [Yup](https://www.npmjs.com/package/yup)
-   [date-fns](https://date-fns.org/)
-   [Reactotron](https://infinite.red/reactotron)
-   [VS Code][vc] with [EditorConfig][vceditconfig] and [ESLint][vceslint]

### BACK-END
-   [Node.js][nodejs]
-   [Express](https://expressjs.com/)
-   [nodemon](https://nodemon.io/)
-   [Sucrase](https://github.com/alangpierce/sucrase)
-   [Docker](https://www.docker.com/docker-community)
-   [Sequelize](http://docs.sequelizejs.com/)
-   [PostgreSQL](https://www.postgresql.org/)
-   [node-postgres](https://www.npmjs.com/package/pg)
-   [Redis](https://redis.io/)
-   [MongoDB](https://www.mongodb.com/)
-   [Mongoose](https://mongoosejs.com/)
-   [JWT](https://jwt.io/)
-   [Multer](https://github.com/expressjs/multer)
-   [Bcrypt](https://www.npmjs.com/package/bcrypt)
-   [Youch](https://www.npmjs.com/package/youch)
-   [Yup](https://www.npmjs.com/package/yup)
-   [Bee Queue](https://www.npmjs.com/package/bcrypt)
-   [Nodemailer](https://nodemailer.com/about/)
-   [date-fns](https://date-fns.org/)
-   [Sentry](https://sentry.io/)
-   [DotEnv](https://www.npmjs.com/package/dotenv)
-   [VS Code][vc] with [ESLint][vceslint]

## Instalação

Postgres - Banco de dados principal  
  `docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres`

MongoDB - Banco de dados para notificações 
  `docker run --name mongobarber -p 27017:27017 -d -t mongo`

Redis - Banco de dados para filas  
  `docker run --name redisbarber -p 6379:6379 -d -t redis:alpine`

Sequelize  
  `yarn sequelize db:migrate`  

## **Backend**

`yarn dev`
`yarn queue`

## **Frontend**

`yarn start`

## **Mobile(android)**

`react-native run-android`
