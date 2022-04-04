1. `npm init --yes`

2. `npm install --save-dev hardhat` 

3. add `node_modules` and `.env` to `.gitignore` file

4. `npx hardhat` -> sample project

5. in hardhat.config.js -> add mumbai network -> use alchemy rpc + metamask private key

6. `npx hardhat run scripts/sample-script.js` -> errors bc `ERR_INVALID_URL` (didn't save alchemy url string correctly) -> fix

6. `npx hardhat run scripts/sample-script.js` -> error due to `INSUFFICIENT_FUNDS` (no mumbai MATIC)

7. get mumbai testnet eth from https://mumbaifaucet.com/

8. `npx hardhat run scripts/sample-script.js` -> deploys successfully and logs the contract address to console

9. Check your address (0xa41B6af0e5a3611E3694eE14EcEFeA85AD0cCADD) on https://mumbai.polygonscan.com/

10. Write a script to interact with your contract.