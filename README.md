# RES4 Dapp Activity

![Blockchain](https://img.shields.io/badge/Blockchain-Ethereum-blue)
![Smart Contract](https://img.shields.io/badge/Smart%20Contract-Solidity-orange)
![Frontend](https://img.shields.io/badge/Frontend-React-9cf)
![Tools](https://img.shields.io/badge/Tools-Ganache%2C%20Truffle%2C%20MetaMask-lightgrey)

---

## 📖 Overview

The **RES4 Dapp Activity** is a hands-on project designed to provide practical experience in deploying and interacting with a **Decentralized Application (DApp)**. This project covers the entire workflow of a DApp, from deploying a smart contract to interacting with it through a frontend interface. It is an excellent resource for understanding blockchain development, smart contracts, and DApp interactions.

This project is part of a course activity and serves as a prerequisite for more advanced blockchain projects.

---

## 🎯 Objectives

The main objectives of this project are:

1. **Understand DApp Workflow**: Learn the end-to-end process of deploying and interacting with a DApp.
2. **Explore Smart Contracts**: Gain hands-on experience in deploying and interacting with a smart contract using Solidity.
3. **Interact with Blockchain**: Use tools like Ganache, MetaMask, and Truffle to simulate a blockchain environment.
4. **Role-Based Interactions**: Experiment with different roles (e.g., supervisor, assessor, owner) and their functionalities within the DApp.

---

## 🛠️ Prerequisites

Before starting, ensure you have the following installed:

1. **MetaMask Wallet**: A browser extension for managing Ethereum accounts.  
   [Download MetaMask](https://metamask.io/).

2. **Node.js and NPM**: Required for running the frontend and deploying the smart contract.  
   [Download Node.js](https://nodejs.org/).

3. **Ganache**: A personal blockchain for Ethereum development.  
   [Download Ganache](https://trufflesuite.com/ganache/).

4. **Truffle**: A development framework for Ethereum. Install it globally using:
   ```bash
   npm install -g truffle
   ```

---

## 📂 Project Structure

The project is divided into two main folders:

1. **RES4-contract**: Contains the Solidity smart contract and deployment scripts.
2. **RES4-app**: Contains the React frontend for interacting with the smart contract.

---

## 🚀 Getting Started

Follow these steps to set up and run the project:

### Step 1: Clone the Repository
Clone this repository to your local machine:
```bash
git clone https://github.com/your-username/res4-dapp-activity.git
cd res4-dapp-activity
```

### Step 2: Install Ganache
1. Download and install Ganache from the [official website](https://trufflesuite.com/ganache/).
2. Launch Ganache and create a new workspace using the "Quickstart Ethereum" option.

### Step 3: Connect MetaMask to Ganache
1. Open MetaMask and click on the network selection dropdown.
2. Select "Add Network" and fill in the following details:
   - **Network Name**: Ganache
   - **New RPC URL**: `http://127.0.0.1:7545`
   - **Chain ID**: `1337`
   - **Currency Symbol**: ETH
   - **Block Explorer URL**: Leave empty
3. Save the network and switch to it.

### Step 4: Import Accounts into MetaMask
1. In Ganache, click the key icon next to the first address (index 0) to reveal the private key.
2. Copy the private key.
3. In MetaMask, click the account icon, select "Add Account or Hardware Wallet", then choose "Import Account".
4. Paste the private key and click "Import".
5. Repeat the process for the second, third, and fourth addresses (index 1, 2, and 3).

### Step 5: Deploy the Smart Contract
1. Navigate to the `RES4-contract` folder:
   ```bash
   cd RES4-contract
   ```
2. Compile and deploy the smart contract:
   ```bash
   truffle migrate --reset
   ```

### Step 6: Run the Frontend
1. Navigate to the `RES4-app` folder:
   ```bash
   cd ../RES4-app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend:
   ```bash
   npm start
   ```
4. Open your browser and navigate to `http://localhost:3000`.

---

## 🧩 Key Features
![Cuplikan layar 2025-01-19 200808](https://github.com/user-attachments/assets/b2e9c043-7a3c-4874-bf77-0e01e82af84c)
![image](https://github.com/user-attachments/assets/ee09255d-eecd-432e-a3a8-e3ec7a5b6a43)

### 1. **Add Assets**
- The supervisor can add new assets to the DApp, specifying the price and owner.

### 2. **Assess Assets**
- The supervisor can assess the value of an asset, increasing its price.

### 3. **Build on Assets**
- Asset owners can build on their assets, increasing their value.

### 4. **Approve and Buy Assets**
- Asset owners can approve other users to buy their assets, and buyers can complete the purchase.

---

## 📊 Workflow Diagram

```
        |                           |                           |
        | 1. Start Ganache          | 2. Connect MetaMask       |
        |-------------------------->|-------------------------->|
        |                           |                           |
        | 4. Run Frontend           | 3. Deploy Contract        |
        |<--------------------------|<--------------------------|
        |                           |                           |
        | 4. Import Accounts        | 6. Interact with DApp     |
        |-------------------------->|-------------------------->|
        |                           |                           |
```

---

## 🧠 Learning Outcomes

By completing this project, you will:
- Understand the basics of blockchain and smart contracts.
- Gain experience in deploying and interacting with a DApp.
- Learn how to use tools like Ganache, MetaMask, and Truffle.
- Explore role-based interactions within a DApp.

---

## 📚 Resources

- [Solidity Documentation](https://soliditylang.org/docs/)
- [Truffle Documentation](https://trufflesuite.com/docs/)
- [MetaMask Documentation](https://docs.metamask.io/)
- [Ganache Documentation](https://trufflesuite.com/docs/ganache/)

---

## 🤝 Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Special thanks to the course instructors for providing the resources and guidance for this project.
- Inspired by the growing ecosystem of decentralized applications and blockchain technology.

---

Happy coding! 🚀
```
