# PyChain Ledger

![alt=""](Images/application-image.png)

You’re a fintech engineer who’s working at one of the five largest banks in the world. You were recently promoted to act as the lead developer on their decentralized finance team. Your task is to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

You’ll make the following updates to the provided Python file for this assignment, which already contains the basic `PyChain` ledger structure that you created throughout the module:

1. Create a new data class named `Record`. This class will serve as the blueprint for the financial transaction records that the blocks of the ledger will store.

2. Modify the existing `Block` data class to store `Record` data.

3. Add Relevant User Inputs to the Streamlit interface.

4. Test the PyChain Ledger by Storing Records.

---

    
<span style="color:white;font-weight:100;font-size:15px">
    <b>Run Streamlit App:</b>
</span>

    streamlit run pychain.py

---

## Screenshot Streamlit PyChain Application 
![alt=""](Images/Streamlit_Screenshot.png)
![alt=""](Images/Streamlit_Screenshotc.png)

PyChain Streamlit Application is a user friendly web interface which serve as a blockchain-based ledger system, allowing partner banks to conduct financial transactions (transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

#### How To Use this Application

To fully make use of the application, the user has to enter the sender's address, reciver's address and the amount crypto to transfer. The block difficulty gives insight into the time it took to mine a block. The `PyChain Ledger` stores the transaction records with the help of the block inspector. To validate the block contents and hashes a `Validate Chain` button is provide to analyze the previous hash to the current.  

---


