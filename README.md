# Avax-1

### README: Deploying and Interacting with Your EVM Subnet on Avalanche

Welcome to the setup guide for deploying your EVM subnet on Avalanche using the Avalanche CLI and interacting with it using Remix and Metamask. This guide will walk you through the necessary steps to get your environment set up and start deploying and testing smart contracts.

#### Step 1: Deploy Your EVM Subnet Using the Avalanche CLI

1. **Install Avalanche CLI**: If you haven't already, install the Avalanche CLI following the official documentation.

2. **Deploy EVM Subnet**: Use the Avalanche CLI to deploy your EVM subnet. Refer to Avalanche documentation for specific commands and parameters.

#### Step 2: Add Your Subnet to Metamask

1. **Open Metamask**: Open your Metamask extension or app.

2. **Network Selection**: 
   - Click on the network selection dropdown (top of the extension or app).
   - Choose "Custom RPC" to add a custom network.

3. **Add Custom Network**:
   - Enter the network details (RPC URL, ChainID, Symbol, and Block Explorer URL) provided by Avalanche after deploying your EVM subnet.
   - Save the network.

#### Step 3: Connect Remix to Your Metamask

1. **Open Remix**: Go to the Remix IDE (https://remix.ethereum.org/).

2. **Select Injected Web3 Provider**:
   - In Remix, select the environment dropdown (top right).
   - Choose "Injected Web3" to connect to Metamask.

#### Step 4: Deploy Smart Contracts

1. **Compile Contracts**: 
   - Write or import your Solidity smart contracts into Remix.
   - Compile the contracts using the Remix Solidity compiler.

2. **Deploy Contracts**:
   - Navigate to the "Deploy & Run Transactions" tab in Remix.
   - Select the contract you want to deploy.
   - Choose the account from Metamask that will deploy the contract.
   - Deploy the contract.

#### Step 5: Test Your Application

1. **Interact with Contracts**: 
   - Use the Remix IDE to interact with your deployed smart contracts.
   - Test functionalities such as token deployment, creating pools, and executing transactions.

2. **Debug and Iterate**:
   - Use Remix's debugging tools to verify contract behavior.
   - Make adjustments to your contracts as necessary based on testing outcomes.

### Additional Resources

- Refer to Avalanche and Remix documentation for more detailed instructions and troubleshooting tips.
- Join community forums and discussions for support and collaboration.

### Conclusion

You are now set up to deploy and interact with your EVM subnet on Avalanche using Remix and Metamask. Start building and testing your decentralized applications (dApps) with confidence! If you encounter any issues, refer back to this README or seek assistance from the community. Happy coding!
