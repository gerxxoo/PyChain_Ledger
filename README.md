# PyChain_Ledger

## Background
You’re a fintech engineer who’s working at one of the five largest banks in the world. You were recently promoted to act as the lead developer on their decentralized finance team. Your task is to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.
You’ll make the following updates to the provided Python file for this assignment, which already contains the basic `PyChain` ledger structure that you created throughout the module:


## Project
1. Create a new data class named `Record`. This class will serve as the blueprint for the financial transaction records that the blocks of the ledger will store. This creates the `Sender`, `Receiver`, and `Amount` data class. 

2. Modify the existing `Block` data class to store `Record` data. 

3. Add Relevant User Inputs to the Streamlit interface. This creates the `Sender`, `Receiver`, and `Amount` input boxes. 

4. Test the PyChain Ledger by Storing Records.

This project creates a blockchain ledger that a records transactinos between two users (`Sender` and `Receiver`). An important function of this system is the ability to verify said transactions. 

## The Ledger
The ledger records all the transactions. This project includes ten transactions. Validating the blocks allow certainty of movement between two parties. 

<img width="665" alt="Screenshot 2024-04-24 at 9 45 52 PM" src="https://github.com/gerxxoo/PyChain_Ledger/assets/151468004/52666a65-80d0-433f-a028-0f652a685ca8">

<img width="666" alt="Screenshot 2024-04-24 at 9 46 20 PM" src="https://github.com/gerxxoo/PyChain_Ledger/assets/151468004/d526eb46-c034-486b-bfcf-f486069f3ccf">
