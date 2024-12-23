# FE Web3 E2E Test 2024

**Description:**
1. Create a Next.js application using typescript, Next.js's app router plus any additional libraries and frameworks of your choice.
2. The App should have a single Button with the label "Connect Wallet" which should allow you to connect an (EVM) web3 wallet.
3. After a successful wallet connection, the Button should be relaced with a very simple UI that shows your wallet's Ether balance plus another button with the label "Sign".
4. When clicked, this sign button should prompt the user's wallet provider to sign the message "Hello".
5. Add to the repo a simple E2E suite can be run locally, using your choice of:
- Vanilla Cypress
- Vanilla Playwright 
- Synpress + Playwright or Cypress
6. The E2E suite should have at least the following 3 tests:
  
   a) User connects a wallet
  
   b) Sign button is rendered on Screen
  
   c) Clicking on Sign button successfully creates a valid signature. 

Notes:
- Please create this repo inside your own github profile, and give me access to it. 
- I'll use Metamask on Mainnet or Arbitrum to test wallet connection. 
