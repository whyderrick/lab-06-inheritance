# Modelling Bank Accounts

As a second programming exercise, we're going to model different bank accounts. This project is in the same repository as our Orchard problem. Create a new NetBeans project called **BankAccount** in the folder where you've cloned this repo. Then copy write the code necessary to complete this program.


## Bank Account

- Create a generic/abstract class called **BankAccount**
  - Give it an instance variable `balance`.
- Then write two new classes, **CheckingAccount** and **SavingAccount**, that extend the **BankAccount** class.
## Checking Account
- **CheckingAccount** should have a new instance variable `monthlyFee`
- **CheckingAccount** should have a new instance method `getMonthlyFee()`
- **CheckingAccount** should have a new instance variable `applyMonthlyFee()` which subtracts the `monthlyFee` from the `balance`
  
## Savings Account
- **SavingAccount** should have a new instance variable, `interestRate`
- **SavingAccount** should have a new instance method, `getInterestRate()`
- **SavingAccount** should have a new instance variable, `applyInterestRate()`

For both subclasses, define constructor methods that call the super constructors of BankAccount class.

## Extra Challenge
Define a method in **BankAccount**, `transferTo()`, that transfers balance from one account to another
```
account1.transferTo(account2, 10)
```
