# Inventory Management
G-able Developer Test

## 📖 Description

- Web application for managing inventory of products

## 💡 Getting Start

### Install Backend and Frontend Libraries:
NPM:
### ``` npm run init ```
or YARN:
### ``` yarn init ```


## Initialize Database:

Change Password in config.json for access your mySQL
1. Open ./backend-maid-pro/config/config.json
2. Edit "password" in "development" to be your MySql's password
3. Edit "database" to be "cc4_maid_pro"
4. Add "salt_length": 12 into "development" object.

### 2. `cd backend-maid-pro && sequelize db:create && cd ..`

## ✔ Available Scripts

In the project directory, you can run:

### `npm start` or `yarn start`

Runs the app in the development mode.
Open [http://localhost:8080](http://localhost:8080) to view it in the browser. (Client side)
And [http://localhost:3333](http://localhost:3333) will be your server side.

Run seed for mocking data
### `npm run seed` or `yarn seed:y`

## 🛠 Built with...
### Frontend
- [Create React App](https://facebook.github.io/create-react-app/docs/getting-started) - Project creator
- [React](https://reactjs.org/) - Front-end framwork
- [Redux](https://redux.js.org/) - A predictable state container for JavaScript apps
<!--[styled-components](https://www.styled-components.com/) - A CSS framwork allows developer write actual CSS code to style React components -->
- [Ant Design](https://ant.design/) - A design system base react components

### Backend
- [NodeJS](https://nodejs.org/dist/latest-v12.x/docs/api) - Open source server environment for JavaScript
- [Sequelize](https://sequelize.org/v5/index.html) - Object Relational Mapping library
- [ExpressJS](https://reactjs.org/) - Server side framework
- [mySQL](https://www.mysql.com) - Database


## 🤘 Authors

Kittayot Pattanapara (mark)
