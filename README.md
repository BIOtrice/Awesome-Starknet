# Awesome-Starknet
Alll you need about Starknet

Starknet, a scalable Layer-2 solution on Ethereum, offers a unique platform for developers to create and deploy smart contracts. This guide provides a step-by-step walkthrough on how to get started with Starknet smart contract development using the Cairo programming language.

**Setting Up Your Development Environment**

The first step in creating smart contracts in Starknet is setting up your development environment. We recommend using the Starknet Remix Plugin, a tool that allows you to compile, deploy, and interact with your smart contracts. To activate the plugin, visit The Remix Project, navigate to the ‘Plugins’ section, and enable the “Starknet” plugin. Once activated, the Starknet logo will appear on the left sidebar, allowing you to interact with your Cairo files.

**Understanding Starknet Smart Contracts**

Starknet smart contracts are written in Cairo, a language specifically designed for creating STARK-based smart contracts. A typical Starknet smart contract includes an ownership system, a method to transfer ownership, a method to check the current owner, and an event notification for ownership changes.

**Compiling Your Smart Contract**

After writing your smart contract, the next step is to compile it. In the "Starknet" tab of the Remix Project, select "Compile Ownable.cairo". After the compilation, an "artifacts" folder will appear containing the compiled contract in two formats: Sierra (JSON file) and CASM. For Starknet deployment, the Sierra file will be used.

**Deploying Your Smart Contract**

To deploy your smart contract, you need to define an initial owner. This information is required by the Constructor function. To deploy your contract on the development network, select the "Remote Devnet" under the Environment selection tab, choose a devnet account, and input the copied address into the init_owner variable. Click on "Deploy ownable.cairo" to deploy your contract.

**Interacting with Your Contract**

Once your contract is deployed, you can interact with it. To do this, navigate to the "Starknet" tab and select the "Interact" option. You can then call the get_owner function to retrieve the current owner's details or invoke the transfer_ownership function to transfer ownership to a new owner.

**Deploying on Starknet Testnet**

After testing your smart contract on a development network, you can deploy it to the Starknet Testnet, a public platform ideal for testing smart contracts and collaborating with fellow developers. To do this, you need to set up a Starknet account using a smart wallet such as Braavos or Argent, fund your account using the Starknet Faucet, and then follow the previous deployment steps.

**Monitoring Your Transactions**

You can monitor your transactions and contract state alterations using Starknet block explorers like Starkscan or Voyager. These tools provide a visual representation of transactions and contract state alterations, making it easy to track contract events.

**Next Steps**

After successfully deploying your first Starknet smart contract, you can choose to deepen your knowledge of Starknet by delving into the Starknet Book or dive into Cairo by navigating through the Cairo Book. Both resources provide extensive information and guidance on Starknet and Cairo, helping you to further enhance your smart contract development skills.

Here are the links that could help you to the first steps in the Starknet ecosystem:
-  https://book.starknet.io/
- https://www.starknet.io/
- https://www.starknet.io/en/developers
- https://starknet-by-example.voyager.online/
