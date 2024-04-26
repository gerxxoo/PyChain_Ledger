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

# Instructions

## Step 1: Create a Record Data Class
1. Define a new class named `Record`.

2. Add the `@dataclass` decorator immediately before the `Record` class definition.

3. Add an attribute named `sender` of type `str`.

4. Add an attribute named `receiver` of type `str`.

5. Add an attribute named `amount` of type `float`.

## Step 2: Modify the Existing Block Data Class to Store Record Data
1. In the `Block` class, rename the `data` attribute to `record`.

2. Set the data type of the `record` attribute to `Record`.

## Step 3: Add Relevant User Inputs to the Streamlit Interface
1. Delete the `input_data` variable from the Streamlit interface.

2. Add an input area where you can get a value for `sender` from the user.

3. Add an input area where you can get a value for `receiver` from the user.

4. Add an input area where you can get a value for `amount` from the user.

5. As part of the Add Block button functionality, update `new_block` so that `Block` consists of an attribute named `record`, which is set equal to a `Record` that contains the `sender`, `receiver`, and `amount` values. The updated `Block` should also include the attributes for `creator_id` and `prev_hash`.

## Step 4: Test the PyChain Ledger by Storing Records
1. In the terminal, navigate to the project folder where you've coded the Challenge.

2. In the terminal, run the Streamlit application by using `streamlit run pychain.py`.

3. Enter values for the sender, receiver, and amount, and then click the Add Block button. Do this several times to store several blocks in the ledger.

4. Verify the block contents and hashes in the Streamlit drop-down menu. Take a screenshot of the Streamlit application page, which should detail a blockchain that consists of multiple blocks. Include the screenshot in the `README.md` file for your Challenge repository.

5. Test the blockchain validation process by using the web interface. Take a screenshot of the Streamlit application page, which should indicate the validity of the blockchain. Include the screenshot in the `README.md` file for your Challenge repository.

## The Ledger
The ledger records all the transactions. This project includes ten transactions. Validating the blocks allow certainty of movement between two parties. 

<img width="665" alt="Screenshot 2024-04-24 at 9 45 52 PM" src="https://github.com/gerxxoo/PyChain_Ledger/assets/151468004/52666a65-80d0-433f-a028-0f652a685ca8">

<img width="666" alt="Screenshot 2024-04-24 at 9 46 20 PM" src="https://github.com/gerxxoo/PyChain_Ledger/assets/151468004/d526eb46-c034-486b-bfcf-f486069f3ccf">
