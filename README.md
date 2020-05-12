# [ExpenseTrackerApp](https://mernexpensetracker.herokuapp.com/)

### In this App, we need 5 dependencies below:

- Express.js
- React.js
- Axios
- MongoDB
- concurrently
- dotenv  
- morgan
- colors


### Usage
```
change config.env file in config folder
```

``` 
 npm install
 cd client npm install
 cd ..
 
 # Run front and backend
 npm run dev
 
 # Backend only
 npm run server
 
 # Frontend only
 npm run client
 
 # Build client
 cd client
 npm run build
 
 # Production
 npm start

```

### Test the APIs Using Postman

### ADD Transaction
#### Request POST: http://localhost:8000/api/v1/transactions

  ![alt text](https://github.com/khairul-abdi/ExpenseTrackerApp/blob/master/client/public/img/screenshot/add-transaction.png)

### GET All Transactions 
#### Request GET: http://localhost:8000/api/v1/transactions

  ![alt text](https://github.com/khairul-abdi/ExpenseTrackerApp/blob/master/client/public/img/screenshot/get-all-transactions.png)


### DELETE Transaction 
#### Request DELETE: http://localhost:8000/api/v1/transactions/:id

  ![alt text](https://github.com/khairul-abdi/ExpenseTrackerApp/blob/master/client/public/img/screenshot/delete-transaction.png)


### [Demo](https://mernexpensetracker.herokuapp.com/)

### ADD Transaction

  ![alt text](https://github.com/khairul-abdi/ExpenseTrackerApp/blob/master/client/public/img/screenshot/add-transaction.png)


### VIEW Transactions

  ![alt text](https://github.com/khairul-abdi/ExpenseTrackerApp/blob/master/client/public/img/screenshot/view.png)


### VIEW Transactions

  ![alt text](https://github.com/khairul-abdi/ExpenseTrackerApp/blob/master/client/public/img/screenshot/delete.png)
