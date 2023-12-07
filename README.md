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
MEV - Searching Strategies
Did some NodeGuardians quests to learn about storage and Gas Optimizations

Using Blocknative docs
To get an understanding of how Mempools work and how to access transactions that I'm forwarding there.
- https://github.com/jaiminbuilds/mev

---

### Dec 2nd
Gas monitoring Chrome extension, it uses the blocknative API to monitor gas prices and shows it from the icon on the broswer extension. It's Typescript and should be able to be deployed on both Chrome and Firefox

- https://github.com/jaiminbuilds/gas_no_brakes

Set up a simple python flask server and client communicating through Heroku, Heroku is nice 👍
- https://github.com/jaiminbuilds/flask-server

Using covalent's api and typescript to track portfolio balance, need to get a Zerion api
- https://github.com/jaiminbuilds/portfolio

---

### Dec 3rd
Node Guardians - gas optimizing solidity contracts

Messing around with bridging using Socket's API
- https://github.com/jaiminbuilds/bridgooor

Creating a general purpose dApp to use for testing
- https://github.com/jaiminbuilds/starter_dapp

---

### Dec 4th
Started putting in socket's single tx quote and swap into the starter_dapp. Not quite working yet, will try to copy more code out the box and get it working there.
- https://github.com/jaiminbuilds/starter_dapp

--- 

### Dec 5th
Got my starter dapp working with Wagmi and used Ethers to initiate briging USDC from Polygon to BNB chain for Socket, handling for approvals. Seems to be working fine :)
- https://github.com/jaiminbuilds/bridgooor
- https://github.com/jaiminbuilds/starter_dapp

---

### Dec 6th
Node Guardians - delegate call action: solved quest to prove if the function call was a delegate call or not by writing the immutable contract deployment address into the constructor

Messed around with a browser extension to inject objects into web frontends of browser extensions
- https://github.com/jaimindp/designr_injection

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
- Tokenbound accounts 6551
  - Create a Marketplace
  - Fractionalise the NFT for this marketplace
- Create a NFT collection
- Build an interface for Ambient DEX
- Do some Caddi integrations 👀
- Interface for perp dexes and aggregators (Hyperliquid, MUX, LogX, RageTrade)
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
- Build a good portfolio tracker
  - Using APIs (Coingecko, De.fi, covalent, defillama, coinmarketcap, debank, Portals)
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
