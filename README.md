# fintech_finder
A prototype application that allows its customers to find fintech professionals, hire them, and pay them.

This project integrates two files that will generate a digital wallet, access Ethereum account balances, and sign and send transactions via a personal Ethereum blockchain called Ganache. A breakdown of the project code that will do the following:
* Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.
* Fetch and display the account balance associated with your Ethereum account address.
* Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.
* Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.
* Review the transaction hash code associated with the validated blockchain transaction.


### Technologies

This project uses the following libraries and dependencies:
+ [**Anaconda**](https://docs.anaconda.com/): an open source package and environment management system.
+ [**Python**](https://www.python.org/): is a programming language that offers a vast modules and libraries such as dataclass, typing, hashlib, datetime, and much more.
+ [**requests**](https://docs.python-requests.org/en/latest/user/install/#install): HTTP library for Python. 
+ [**web3**](https://web3py.readthedocs.io/en/stable/quickstart.html#installation): a Python library for interacting with Ethereum. Help with sending transactions, interacting with smart contracts, reading block data, and a variety of other use cases.
+ [**eth-tester**]
+ [**mnemonic**]
+ [**bip44**]
+ [**Ganache**](https://trufflesuite.com/docs/ganache/): a personal blockchain for repid Ethereum and Corda distributed application development. Used in development cycle. 
+ [**Streamlit**](https://docs.streamlit.io/library/get-started): a Python library that works only with Python files (.py files). It quickly turns Python scripts into shareable web apps. For this application we will create a user-friendly webpage interface for a blockchain. 


## Installation Guide

Set up missing Python modules and libraries click on any of the links associated above for its installation documentation. Activate your working environment and run the following commands in your terminal:

`pip install web3==5.17`

`pip install eth-tester==0.5.0b3`

`pip install mnemonic`

`pip install bip44`

[**Download page for Ganache**](https://trufflesuite.com/ganache/)



### Troubleshooting Installation
Troubles with installation? Try the following:


Install Microsoft Visual C++ Build Tools (for Windows users):
1. Go to https://visualstudio.microsoft.com/vs/older-downloads/. 
2. Scroll down the page, and click "Tools for Visual Studio 2019" to reveal the options.
3. Download the "Build Tools for Visual Studio 2019" package.
4. Run the package file and select the C++ Build Tools option. Then click install.

Update Conda Environment:
1. Quit any running applications. Then deactivate your current conda environment using `conda deactivate`
2. Update conda by using: `conda update conda`
3. Reactivate your environment and attempt the installations again.   

For more troubleshooting tips, click on link https://web3py.readthedocs.io/en/stable/troubleshooting.html.

