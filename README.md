# Blockchain-Based Voting System

## Description
This project is a decentralized, transparent, and secure voting system based on blockchain technology. The goal of this project is to provide an alternative to traditional voting methods that can be prone to errors, fraud, and manipulation.

The system consists of a smart contract deployed on a public blockchain network Ethereum which manages the voting process and stores the voting results. The smart contract ensures that only authorized voters can participate in the election, that each voter can only vote once, and that the votes are tallied accurately and anonymously.

The project includes a user interface that allows voters to authenticate, and cast their votes securely from their devices. The user interface is designed to be user-friendly and accessible to all types of voters, including those who may not have technical expertise.

Overall, this project aims to leverage the benefits of blockchain technology, such as immutability, transparency, and decentralization, to create a more reliable and trustworthy voting system that can be used in various contexts, from local elections to global referendums. The project is open-source and welcomes contributions from the community to improve and expand its functionality.

## Steps to solve

### Step-1
Clone the project.

### Step-2
Install the dependencies. Type the following commands in the terminal:

cd election
npm install

### Connet Genache and Metamask
1.Open MetaMask wallet and Click on the Account Circle.
2.Below the account list, choose Import Account.
3.Pick one address from Ganache Desktop UI and copy the Private key from the Key symbol at the right end.
4.Paste your private key string to MetaMask.

### Compiling the contracts
$ truffle migrate --reset You must migrate the election smart contract each time your restart ganache.

### Run the frontend application
$ npm run dev Visit this URL in your browser: http://localhost:3000
