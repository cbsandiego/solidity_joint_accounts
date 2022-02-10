# Joint Account with Solidity

![savings](images/savings.jpg)

This is a joint savings accounts created with a Solidity smart contract accepting two user addresses.  It will use ether management functions to implement a financial institution's requirements for providing features of the joint savings account.  Users will be able to deposit and withdraw funds from the account.

---

## Technologies

Open Remix IDE website (https://remix.ethereum.org/) and run `joint_savings.sol` file.

---

## Remix - Solidity

To interact with the Joint Account smart contract, compile as shown:

![compile](execution_results/compile.jpg)

Deploy and run as displayed:

![deploy](execution_results/deploynrun.jpg)

After generating addresses through [Ganache](https://www.trufflesuite.com/ganache), set up account1 and account2:

![setaccounts](execution_results/setaccounts.jpg)

Let's test the **deposit** functionality!

- Transaction 1:  Sending 1 ether as wei.

![1eth](execution_results/transaction1ether.jpg)\
 \
![1eth](execution_results/contractbalance1eth.jpg)\
 \
![1eth](execution_results/1ethexecution.jpg)

- Transaction 2:  Sending 10 ether as wei.

![10eth](execution_results/10ether.jpg)\
 \
![10eth](execution_results/contractbalance10eth.jpg)\
 \
![10eth](execution_results/10ethexecution.jpg)

- Transaction 3:  Sending 5 ether.

![5eth](execution_results/5eth.jpg)\
 \
![5eth](execution_results/contractbalance5eth.jpg)\
 \
![5eth](execution_results/5ethexecution.jpg)

Let's now test the **withdrawal** function!

- Withdraw 5 ether into `accountOne`.

![5eth](execution_results/withdraw5eth.jpg)

- Withdraw 10 ether into `accountTwo`.

![10eth](execution_results/withdraw10eth.jpg)

---

## Contributors
Christina San Diego