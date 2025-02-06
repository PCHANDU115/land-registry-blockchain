# Land Registry Blockchain
A decentralized land registry system built on the Ethereum blockchain using Solidity, Truffle, Ganache, Web3.py, and Streamlit. 💡🔗

This project empowers users to register land, transfer ownership, and verify land details securely on the blockchain, ensuring transparency and tamper-proof records! 🔐📜

# Key Features
✅ Register new land parcels securely 
✅ Transfer ownership with blockchain verification 
✅ Fetch land details instantly 
✅ Decentralized & tamper-proof record system 

# 🛠 Tech Stack
Blockchain: Ethereum, Solidity, Web3.js, Truffle, Ganache
Backend: Python, Web3.py
Frontend: Streamlit
# 📦 Installation & Setup
1️⃣ Install Dependencies
Make sure you have Node.js, Python, and Ganache installed.

Install Truffle globally
npm install -g truffle
Install Python dependencies
pip install web3 streamlit
Blockchain-Based Land Registry
# 🏗 Setup Guide
1️⃣ Start Ganache
Run Ganache on:

http://127.0.0.1:7545
2️⃣ Compile & Deploy Smart Contract
Run the following command to compile and deploy the smart contract:

truffle migrate --reset
3️⃣ Run the Streamlit App
Start the frontend by running:

streamlit run app.py
# 📜 Usage Guide
➤ Register a New Land Parcel
Select an Ethereum account (from Ganache).
Enter the Land ID, Location, and Area.
Click "Register Land" to store it on the blockchain.
➤ Transfer Land Ownership
Enter the Land ID to transfer.
Select a new owner from the available Ethereum accounts.
Click "Transfer Ownership" to update blockchain records.
➤ View Land Details
Enter the Land ID to check details.
Click "Fetch Details" to view registered information.
# 🛠 Troubleshooting
❌ Web3 is not connected
✔ Ensure Ganache is running on port 7545.

❌ Smart contract not deployed
✔ Run truffle migrate --reset and restart the app.

❌ Transaction failed (gas issue)
✔ Increase the gas limit in backend.py to 500000.

# 🔗 References
Ethereum & Web3
Solidity Documentation
Truffle Suite
Streamlit
