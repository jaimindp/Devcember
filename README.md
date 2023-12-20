# Devcember

## Advent Calendev

### WTF is the point of this repo?

Well, it's been a while since I've coded for fun... that's it really

Coming back from Devconnect in November, I saw a tonne of cool crypto tech being built and thought there's no better time for me to develop and explore it as the year ends. Crypto moves at the speed of light and the best way to keep up is to get invovled and get my hands dirty. This is my way of being close to the tech 🛠️

With most of my programming experience in python, focused on data science & ML, I used to be a Python maxi (lol) building ML models and data pipelines and 90% of my code was written in Jupyter Notebooks. Later built some frontend (JS & React) for Caddi and hackathons but never gone too deep with smart contract engineering and EVM. That is going to change this month, this is the point!

It's been a while since I've worked on new projects and coded for the hell of it so this is going to be fun,LFG 💪

Still building https://www.caddi.fi full time, expect to see overlaps with what I'm exploring here and what we build with Caddi 📈

If you are interested in having a chat with me about any of these repos, interested in collaborating, or want to find out more about Caddi, then reach out via TG https://t.me/jaimin_building 🫡

## Calendar

I'll log my progress daily in this repo and point to any repos I create during the sprint

### Dec 1st
Started on some Node Guardians quests to learn about EVM and gas, worked through Storage and Gas Optimizations quests

MEV - Searching Strategies using Blocknative docs
To get an understanding of how Mempools work and how to access transactions that I'm forwarding there.
- https://github.com/jaimindp/mev

---

### Dec 2nd
Gas monitoring Chrome extension, it uses the blocknative API to monitor gas prices and shows it from the icon on the broswer extension. It's Typescript and should be able to be deployed on both Chrome and Firefox

- https://github.com/jaimindp/gas_no_brakes

Set up a simple python flask server and client communicating through Heroku, Heroku is nice 👍
- https://github.com/jaimindp/flask-server

Using covalent's api and typescript to track portfolio balance, need to get a Zerion api
- https://github.com/jaimindp/portfolio

---

### Dec 3rd
Node Guardians - gas optimizing solidity contracts

Messing around with bridging using Socket's API
- https://github.com/jaimindp/bridgooor

Creating a general purpose dApp to use for testing
- https://github.com/jaimindp/starter_dapp

---

### Dec 4th
Started putting in socket's single tx quote and swap into the starter_dapp. Not quite working yet, will try to copy more code out the box and get it working there.
- https://github.com/jaimindp/starter_dapp

--- 

### Dec 5th
Got my starter dapp working with Wagmi and used Ethers to initiate briging USDC from Polygon to BNB chain for Socket, handling for approvals. Seems to be working fine :)
- https://github.com/jaimindp/bridgooor
- https://github.com/jaimindp/starter_dapp

---

### Dec 6th
Node Guardians - delegate call action: solved quest to prove if the function call was a delegate call or not by writing the immutable contract deployment address into the constructor

Messed around with a browser extension to inject objects into web frontends of browser extensions
- https://github.com/jaimindp/designr_injection

---

### Dec 7th
Minted an NFT using NiftyKit and their diamond contract. Got it working on the starter dapp. Doing some tweaks for Caddi
- https://github.com/jaimindp/minting_nft

Working on transaction simulation using Enso Temper. Simulated transactions on ETH Mainnet, now trying the same for Polygon
- https://github.com/jaimindp/temper_simulate_evm

--- 

### Dec 8th
NFT minting work, Caddi onboarding coming soon ⛳️ 👀 Ensuring mint works with Soulbound Tokens

Transcation simulation via API using Tenderly to simulate transations across multiple blockchains
- https://github.com/jaimindp/tenderly

--- 

### Dec 9th
Mostly Caddi coding for our new onboarding and NFT mint

Tenderly simulations working for approvals and swaps :)
- https://github.com/jaimindp/tenderly

--- 

### Dec 10th
Did a bit of work on the simulation framework for enso temper to simluate polygon transactions, gas units are hard 😅
- https://github.com/jaimindp/temper_simulate_evm

---
### Dec 11th
Working on the portfolio tracker, quick setup with portals API to track multichain portfolio and summarize in charts, also using Alchemy for token balances, no $ price with Alchemy though
- https://github.com/jaimindp/portfolio

---
### Dec 12th
Testing out on-chain perp trading API's Hyperliquid and Aevo, using python to place trade, was able to get Aevo on testnet with API Keys, Secrets and generate a signer but was hitting errors (in Python) with placing orders
- https://github.com/jaimindp/perps

Also started to use Brownie, getting working wtih Ganache
- https://github.com/jaimindp/brownie

---
### Dec 13th
Upgraded my AI coding stack with cursor.so, also started to use modal to make any function serverless, and run remotely. Super easy to set up and cursor (VSCode fork with better integrated GPT) looks like alpha. Did some work on the new Caddi onboarding flow
- https://github.com/jaimindp/modal

--- 
### Dec 14th
Caddi changes to our onboarding flow

Started on a blog post about Devcember

Trying Mev Frontrunning repo: 
- https://github.com/jaimindp/mev

---
### Dec 15th
Bridging arc restarted, diving into across and how the contracts work as well as their frontend. Will try ot replace these contracts with another bridge
- https://github.com/jaimindp/across-frontend-v2

---
### Dec 16th
Testing deBridge and Across SDKs, integrating cross chains swaps to starter dApp
- https://github.com/jaimindp/across-frontend-v2
- https://github.com/jaimindp/bridgooor
- https://github.com/jaimindp/starter_dapp

---
### Dec 17th
For support for bridging, using LiFi's API to get the support bridge tokens across 19 chains
- https://github.com/jaimindp/portfolio

Some frontend injections for gas price extension
- https://github.com/jaimindp/gas_no_brakes

---
### Dec 18th
Working on some fun stuff for Caddi, had to take a repo private. It's going to be a degen 2024

---
### Dec 19th
Got back into smart contracting with Node Guardians, did proxy the proxy contract quest

---

### Ideas
I probably won't get round to half of these ideas but here are some of the things I intend to explore.

- Node Guardians Tutorials for a more fundamental understanding of EVM
- Build boilerplate code for testing out new repos and trying out new projects from the smart contract and frontend side
- CoWswap
  - Programmatic Order Framework
  - DCA/TWAP
  - Conditional orders
  - CoWswap Hooks
- Uniswap
  - Deploy an LP pool with Hooks
  - Explore V4
- AA 4337 wallets
  - SAFE wallet SDK
  - Biconomy with Rhinestone
  - Session key management
- Tokenbound accounts 6551
  - Create a Marketplace
  - Fractionalise the NFT for this marketplace
- Create a NFT collection
- Build an interface for Ambient DEX
- Do some Caddi integrations 👀
- Interface for perp dexes and aggregators (Hyperliquid, Aevo, Vertex, MUX, LogX, RageTrade)
- Build a GPT interface to execute smart contracts from natual language
- On chain notifications 
  - From scratch
  - With Hal
  - Push
- Integrate Oracles
- Integrate different bridges and bridge aggregators
- MEV
  - Run searching strategies (frontrunning and sandwich analysis)
  - Get familiar with mempools
  - Frontrunning searching strategies
- Intent architectures
  - 1inch Fusion API exploration
  - Suave
- Browser extensions 😀 
  - Connect wallet with both Metamask and Walletconnect
  - Landing page of extension
  - Interactive injections to a webpage
  - Browser icon add flavour
- Build a good portfolio tracker
  - Using APIs (Coingecko, De.fi, covalent, defillama, coinmarketcap, debank, Portals, Alchemy RPC)
  - Using Blockchain data directly
- Simulate any EVM transaction
  - Enso Temper
  - Tenderly
  - Json RPC calls
- Rapidly build server/client websockets connections and APIs
- TG Miniapp to send payments from CEX accounts
- Write a simple TON app using funC
- MetaMask snap
  - To report recent transactions of the same token
  - To look at frontrunnable value
- Perp Aggs
- Build a bridge
