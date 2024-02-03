# Bank-Account-Project

This is a mini project created during the online training course by "Meta" at "Coursera". The course was "Programming fundamentals of Kotlin" and the project is all about to explore the fundamental concepts of kotlin programming.

**#Introduction**
The project is based on the basic operations of a Bank like deposit or withdrawn money or checking the bank ballance. In the interface there are 6 statements that were printed which asks the user that what kind of bank account he wants to open. Then according to the user's input the other operations like deposit money or withdrawn money will be performed. All the code of this project was written using the Kotlin Playgraound - An online platform for Kotlin programming.

****#NOTE:-** The code was written using Kotlin playground therefore for user input we use random() function because Kotlin playground doesn't support user input directly.**

**#Functions and loops Used**
The first while loop is used for the type of account user wants to create. We use random() function for the user input and we set the range from 1 to 5 and out of 5 options only three are valid. Therefore, for the input 4 and 5 it just iterate again for the valid input.

**debitWithdraw function**:- This function is for the debit account which determines whether the user can withdraw the amount or not. It first checks if the account balance is equal to 0 if true it shows an error. Then it will check for the amount is greater than the current balance if so then again it return error else it proceed further.

**transfer function**:- The function handles the operation according the account type. It first chaeck the type of account and then proceed for the further operations and calls the withdraw or debit functions.

And lastly there are more options for the user including the option to close the system.
