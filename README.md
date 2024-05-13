# Wallet API Documentation


The most important services that any bank provides to the clients is the ability to deposit and withdraw money,
In this demo App there is an implementation of these two functions using :
- Java 17
- Spring Web
- Spring Data JPA
- Lombok
- MySQL Workbench

by using the demoApp you can :
- Add new Bank Account
- Deposit money
- Withdraw money
- Delete Bank Account
- Get All Accounts
- Get Account By Id

## API's endpoints:



▪ Add new bank account: POST http://localhost:8080/api/accounts


▪ Get all accounts    : GET http://localhost:8080/api/accounts


▪ Get account by id   : GET http://localhost:8080/api/accounts/{accountId}



▪ Deposit             : PUT http://localhost:8080/api/accounts/{accountId}/deposit



▪ Withdraw            : PUT http://localhost:8080/api/accounts/{accountId}/withdraw



▪ Delete              : DELETE http://localhost:8080/api/accounts/{accountId}


##Features
* Transfer money to other users of the application.
* Request money from other users of the application.
* Generate a virtual visa card for bill payment and online shopping.

