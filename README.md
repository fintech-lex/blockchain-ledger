# Blockchain Ledger

Blockchain-based ledger system deployed with user-friendly web interface. This ledger will allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

![Blockchain Screenshot](https://github.com/fintech-lex/blockchain-ledger/blob/main/PyChain%20Blockchain.png)

### Libraries
- OS (pre-loaded with Python)
- Requests (pre-loaded with Python)
- PythonIO (pre-loaded with Python)
- Streamlit

## Usage and Installation

This application is hosted locally through the Streamlit library which allows us to deploy the ledger User Interference via Webpagem using our Python3 based code. In order to launch this application locally, Please follow the steps below.

### Prerequisites

1. Install required libraries listed above

```
pip install os requests web3 python-io streamlit
```

### Running the Streamlit Application

1. Download/import `pychain.py`

2. Change directory or 'cd' in your favorite terminal application into the same directory as `pychain.py`, then run the following command
  ```
  Streamlit run pychain.py
  ```

  The output will look like:

  ```
    You can now view your Streamlit app in your browser.

    Local URL: http://localhost:8501
    Network URL: http://192.168.5.3:8501
  ```


#### *FAQ:*

Test your complete `PyChain` ledger and user interface by running your Streamlit application and storing some mined blocks in your `PyChain` ledger. Then test the blockchain validation process by using your `PyChain` ledger.

To do so, complete the following steps:

1. In the terminal, run the Streamlit application by using `streamlit run pychain.py`.

2. Enter values for the sender, receiver, and amount, and then click the "Add Block" button. Do this several times to store several blocks in the ledger.

3. Verify the block contents and hashes in the Streamlit drop-down menu. Review the Streamlit application page, which should detail a blockchain that consists of multiple blocks.

4. Test the blockchain validation process by using the web interface.