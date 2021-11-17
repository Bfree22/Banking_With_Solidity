# Banking_With_Solidity


In this repo, we will be developing a Personal Bank Account using Ethereum smart contracts. This contract will also let you deposit money, earn interest and even withdraw your returns! 

Start by selecting the appropriate compiler version, then name the contract.

We must then create a function that retrieves the contract balance. See below for reference.

![balance]()


There will be two mappings, one for the balances and one for the deposit timestamps. 

Next, another function is needed to initiate the deposit. We will do this by adding two uint variables principal and timeElapsed. 

![function]()

Now that the user can deposit funds into the contract, we need the funds to begin earning interest on the deposited amount. Do this by creating another function called 'getBalance' or any other name you like. 

![interest]()


Keep in mind the interest earned can't be coming out of nowhere, there needs to be funds into the smart contract so the interest can be earned from the deposited amount instead of from the depositor. Create another function that adds funds to the smart contract.


Lastly, there needs to be a withdraw function so we can take out the funds we deposited with the earned interest.


