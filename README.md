# NodeJ: Financial API REST 🚀🚀🚀
API of a finance company that will follow the criteria described below.


### Necessary Commands 
---

#### ⚠️Should you want to create this project from zero, run all of the commands below, if not, just run **npm install --global yarn** and **yarn install** instead⚠️

<br>


> npm install --global yarn

> yarn init -y

> yarn add express

> yarn add uuid

> yarn add nodemon -D (nodemon will make the server "listen" for any changes and automatically recompile the project and "--save-dev" will make the lib only exist in a Dev environment)


### Genral Tips
- In package.json use for example **dev** (you choose the name of the word) inside **scripts** to inform which start command will be executed when typing **yarn dev**. In the example below we use **nodemon** which will observe the changes and automatically recompile the project. Example:

```json
"scripts": {
    "dev": "nodemon src/index.js",
},
```

---
### Requirements 📌

- [x] It must be possible to create an account
- [x] It must be possible to fetch the customer's bank statement
- [x] It must be possible to make a deposit
- [] It must be possible to make a withdrawal
- [] It must be possible to search the customer's bank statement by date
- [] It must be possible to update customer account data
- [] It must be possible to obtain customer account data
- [] It must be possible to delete an account

---
### Business rules 📌

- [x] It should not be possible to register an account with an existing CPF
- [x] It must not be possible to fetch a statement from a non-existing account
- [x] It must not be possible to make a deposit to a non-existing account
- [] It must not be possible to withdraw from a non-existing account
- [] It must not be possible to delete a non-existing account
- [] It must not be possible to withdraw when the balance is insufficient