# Error Handling Contract
This is a Solidity smart contract that demonstrates different error handling techniques using __assert__, __revert__, and __require__ functions.
# License
This contract is using the MIT License.
# Prerequisites
Solidity ^0.8.17
# Contract Details
The ErrorHandling contract provides the following functions:
### __testAssert(uint number)__
* This function demonstrates the usage of the assert function.
* It takes a num parameter and checks if it is not equal to zero using the assert statement.
* If the condition fails, it triggers an "Internal error" and aborts the execution.
### divide(uint _numerator, uint _denominator)__
* This function demonstrates the usage of the revert function.
* It takes _numerator and _denominator parameters and performs division.
* If the _numerator is less than _denominator, it reverts the transaction with a custom error message stating that the numerator should be greater than the denominator.
* If the condition is met, it returns the result of the division.
### __mult(uint a)__
This function demonstrates the usage of the require function.
* It takes an a parameter and performs multiplication with a predefined constant b.
* It first checks if a is greater than zero using the require statement.
* If the condition fails, it reverts the transaction with a custom error message stating that the value of a should not be zero.
* If the condition is met, it returns the result of the multiplication.
# Usage
- Make sure you have Solidity ^0.8.17 installed.
- Compile and deploy the ErrorHandling contract to a supported Ethereum network.
- Interact with the deployed contract by calling the available functions and providing the required parameters.
# Video Walkthrough
https://www.loom.com/share/05c6905edfdc44b6bb628d8d18d0e572?sid=0d9185da-5b55-42f7-87b0-823fdbb1548e
Feel free to explore and modify the contract according to your needs!
