# Summary
I work at a startup that is building a new and disruptive platform called Fintech Finder. Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As Fintech Finder’s lead developer, I have been tasked with integrating the Ethereum blockchain network into the application in order to enable my customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

In this Challenge, I will complete the code that enables my customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, I will assume the perspective of a Fintech Finder customer who is using the application to find a fintech professional and pay them for their work.

# What am I Creating
To complete this Challenge, I will use two Python files, both of which are contained in the starter folder.

The first file that I will use is called fintech_finder.py. It contains the code associated with the web interface of my application. The code included in this file is compatible with the Streamlit library. I will write all of my code for this Challenge in this file.

The second file that I will use is called crypto_wallet.py. This file contains the Ethereum transaction functions that I have created throughout this module’s lessons. By using import statements, I will integrate the crypto_wallet.py Python script into the Fintech Finder interface program that is found in the fintech_finder.py file.

Integrating these two files will allow I to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via a personal Ethereum blockchain called Ganache.

  * Specifically, I will assume the perspective of a Fintech Finder customer in order to do the following:

  * Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

  * Fetch and display the account balance associated with my Ethereum account address.

  * Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

  * Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

  * Review the transaction hash code associated with the validated blockchain transaction.

# Screenshot of workers

<img width="1148" alt="Screen Shot 2022-10-24 at 3 02 40 PM" src="https://user-images.githubusercontent.com/107083440/197618038-648cdb50-b6ff-4be3-9bb7-9b8be805dd07.png">
