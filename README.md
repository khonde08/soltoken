## MINT AND BURN FUNCTION
This is the basic Solidity smart contract below!

## REPORT
This Solidity smart contract contains several features to manage a custom token. It includes two public variables: 
1. For the token's name.
2. For its abbreviation. 
The contract also has a variable that keeps track of the total token supply. To manage user balances, there is a mapping variable named "balances" that connects addresses with their corresponding token balances.
Here's another way to phrase your statement:

The contract contains two primary operations, known as "mint" and "burn." 
* The "mint" function enables the contract owner to increase the token balance of a specified address by a specified amount. 
* Conversely, the "burn" function allows the contract owner to decrease the token balance of a specified address by a certain number of tokens

## CODE COMPILER 
Use remixIDE 

## EXECUTING THE PROGRAM
* WE have to Create a new folder in remixIDE (Here i give a name as niktoken.sol).
* After writing a code we have to compile it with the help of side menu where we have to select "Compile and Run" option.
* Once the code has been compiled, we need to deploy the contract in order to obtain the account address.
* Copy the account address and deploy it.
* The contract has been deployed without any issues.
* The account balance is initially zero.
* To create new tokens, select the "Mint" button and input the account address where the tokens should be added. Then, enter the desired token quantity (e.g., 500) and click "Transact" to complete the transaction.It add the tokens to the account.
* To verify the current balance of a particular account, click on the "Balances" tab, paste the account address, and then select "Call" to obtain the current balance.
* To Burn the tokens, select the "Burn" button and input the account address where the tokens should be subtracted. Then, enter the desired token quantity (e.g., 200) and click "Transact" to complete the transaction.It subtract the tokens to the account.
* To again verify the current balance of a particular account, click on the "Balances" tab, paste the account address, and then select "Call" to obtain the current balance. It perform as (e.g ., 500-200=300) 
* These are the various stages which included  in the Project.

## Stand BY

Here the  guidance during the project was incredibly helpful also having a very supportive community!!

## AUTHORIZER
NIKHIL KHONDE

## LICENSE
This project is licensed under the [MIT] License - see the LICENSE.md file for details
