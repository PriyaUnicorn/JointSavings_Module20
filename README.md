# JointSavings_Module20

## Project steps 

    ###Step 1: Create a Joint Savings Account Contract in Solidity
   

* From the provided starter code, open the Solidity file named joint_savings.sol in the Remix IDE.

* Define a new contract named JointSavings.
* Define the following variables in the new contract
* Define a function named withdraw that accepts two arguments: amount of type uint and recipient of type payable address. In this function, code the following
* Define a require statements
* Add an if statement to check if lastToWithdraw is not equal (!=) to recipient. If it’s not equal, set it to the current value of recipient.
* Call the transfer function of the recipient, and pass it the amount to transfer as an argument. Set lastWithdrawAmount equal to amount. Set the contractBalance variable 
* Define a public payable function named deposit. In this function, code the following: Set the contractBalance variable, Define a public function, set the values of accountOne and accountTwo
* Add a fallback function so that your contract can store ether that’s sent from outside the deposit function.

Step 2: Compile and Deploy Your Contract in the JavaScript VM

Step 3: Interact with Your Deployed Smart Contract

To interact with your deployed smart contract, complete the following steps:

* Use the setAccounts function to define the authorized Ethereum address that will be able to withdraw funds from your contract.

![](Execution_Results/1st_Screen Shot 2022-11-20 at 1.26.07 PM.png)

* Test the deposit functionality of your smart contract by sending the following amounts of ether. After each transaction, use the contractBalance function to verify that the funds were added to your contract:

![](Execution_Results/2nd_Screen Shot 2022-11-20 at 1.42.39 PM.png)

##### Transaction 1: Send 1 ether as wei.

![](Execution_Results/3rd_Screen Shot 2022-11-20 at 2.11.56 PM.png)

##### Transaction 1: Send 10 ether as wei.

![](Execution_Results/4th_Screen Shot 2022-11-20 at 2.16.14 PM.png)

##### Transaction 1: Send 5 ether as wei.

![](Execution_Results/5th_Screen Shot 2022-11-20 at 2.20.29 PM.png)

##### Once you’ve successfully deposited funds into your contract, test the contract’s withdrawal functionality by withdrawing 5 ether into accountOne and 10 ether into accountTwo. After each transaction, use the contractBalance function to verify that the funds were withdrawn from your contract. 


![](Execution_Results/Withdrawl10_Screen Shot 2022-11-20 at 2.55.27 PM.png)


##### Use the lastToWithdraw and lastWithdrawAmount functions to verify that the address and amount were correct.


![](Execution_Results/Withdrawl5_Screen Shot 2022-11-20 at 2.50.43 PM.png)


