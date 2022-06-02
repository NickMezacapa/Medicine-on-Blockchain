# The journey of medicine on blockchain. :pill:
## An AI-based solution for improving the process of bringing raw drugs and materials from suppliers to processed medicine in pharmacies.

### Conflict :thinking:
Effective supply chain management is the biggest challenge in every industry. However, there is additional risk and complexity in healthcare as a compromised supply chain can affect the patient’s safety. Increased adoption of technology and globalization in an industry with multiple stakeholders has given rise to a complicated health supply chain.

Lack of transparency can spell disaster for consumers of pharmaceutical drugs. Counterfeit materials remain present, and tampering within the supply chain is difficult to investigate. Consumers deserve full knowledge and clarity of what they're putting in their body. 


### Solution :bulb: :brain:
My solution is an amalgamation of two powerful technologies - Blockchain and AI. Blockchain is an open, distributed ledger that can efficiently record transactions between two parties in a verifiable and permanent way. Blockchain technology is decentralized, distributed, transparent, and immutable; thus it proves to be an effective implementation for pin-pointing counterfeit medicine. AI in pharmacology can assist in matching patients to their optimal drug or combination of drugs, predicting drug-target or drug-drug interactions, and optimizing treatment protocols.

This project proposes a system that uses blockchain and AI for the safe supply of medical drugs throughout the supply chain. Each product within the chain can be transferred between authenticated entities of the chain using an event request-response mechanism. All transactions between entities are recorded into the blockchain using smart contracts with the help of which a product can be traced to its source. A Rasa chatbot is integrated to enable ordering, tracing medicine supply paths, and enhancing blockchain-based credit evaluation. A DApp was then developed using React Framework. The smart contracts were deployed on a local blockchain provided by Ganache. Using Web3.js and Truffle framework, DApp is connected to the blockchain. The experimental results show that our solution is feasible and comparatively more secure than existing systems.


### System Design :computer:
![pharma-sc](https://user-images.githubusercontent.com/89874146/171622227-101cf5ad-c90e-448e-8676-5571b22201da.png)


### To deploy the Smart Contract :moneybag:
1. Install Ganache and create a workspace.
2. Install Truffle npm package globally by running ```npm install -g truffle```.
3. In the `truffle-config.js` file update the `from:` address to an address from your Ganache workspace.
4. Run ```truffle migrate --reset``` from the command line to deploy the smart contract to the blockchain.
5. Download Metamask Chrome extension for the browser to help interaction between the application and the blockchain.

### To run React development server :hammer_and_wrench:
```bash
cd pharma
npm install
npm start
```

### To run Node.js server :hammer_and_wrench:
```bash
cd server
npm install
npm start
```

### Related Links / Information Sources :book:
- https://www.annualreviews.org/doi/abs/10.1146/annurev-pharmtox-010919-023746#:~:text=The%20most%20common%20applications%20of,interactions%2C%20and%20optimizing%20treatment%20protocols.
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7577280/
- https://www.ibm.com/blockchain/resources/transparent-supply/pharma/
- https://hbr.org/2020/05/why-big-pharma-is-betting-on-blockchain
- https://www.leewayhertz.com/blockchain-in-pharma-supply-chain/


### License :balance_scale:
MIT License
#### License Link
https://opensource.org/licenses/MIT
