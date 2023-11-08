# Hughub 

## Setup

1. If you don’t have Node.js installed, [install it from here](https://nodejs.org/en/) (Node.js version >= 14.6.0 required)

2. You need to have Metamask wallet to interact with this application: [install it from here](https://metamask.io/download/)

3. Add Hardhat local network to your Metamask Wallet [Add Network](https://medium.com/@kaishinaw/connecting-metamask-with-a-local-hardhat-network-7d8cea604dc6)

4. Clone or download this repository

5. Navigate into the project directory

   ```bash
   $ cd Hughub
   ```

6. Install the requirements

   ```bash
   $ npm install
   ```

7. Install the requirements in frontend folder

   ```bash
   $ cd frontend
   $ npm install
   ```

8. run local hardhat server

   ```bash
   $ npx hardhat node
   ```
 
9. in other terminal tab, deploy the contract localy

   ```bash
   $ npx hardhat run scripts/deploy.js --network localhost
   ```

10. Run the frontend

   ```bash
   $ npm run frontend
   ```

