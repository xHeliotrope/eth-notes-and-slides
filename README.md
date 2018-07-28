# eth-notes-and-slides
Notes and Slidedeck for Smart Contract Talk

# Planning
* web3
* solidity
* docker (web3 / geth(solidity))
* docker-compose.yml (a little too much maybe? better get to work)

# Daily Question
from here on out, i'm going to ask myself a daily question about ethereum, and then attempt to answer that question here. 

4 + 31 + 11 = 46 questions.

* Git-Related Questions
    - what are the similarities between git and blockchain?
    - is git a merkle tree? ( do git hashes mean anything )
    - can you 'hack' a git commit (change authorship)
    - does changing a prior commit 'spoil' the repo ( is this a feasible thing? )
  
* Ethereum-Related Questions
    - when was ethereum created?
    - how many people use ethereum-related services/run nodes/mine eth?
  
* Cryptography-Related Questions
    - what are the variables in the modular arthimetic of Diffie-Helman?
    - which are public/which are private?
    - does Ethereum use Diffie-Helman in its protocol?
    - why does Ethereum have 3 merkle headers?
  
* Node-Related Questions
    - how expensive is it to run a node?
    - are there different types of nodes?
    - what are the actual benefits of running an ethereum node?
  
* Mining-Related Questions
    - how do miners download the latest chain?
    - how do miners interact with the chain?
  
* Contract-Related Questions
    - do/can nodes execute contracts?
    - are contracts actually 'open-source'? 
    - where can i find the 'source'? 
    - can we choose to run or not run contracts?
    - what happens to obviously malicious contracts?
    - do i need to run a node to deploy a contract?

* geth-Related Questions
    - is geth the most popular application for running a node?
    - why?
    - is that all that geth does?
  
* Protocol-Related Questions
    - why is http a 'thin client'?
    - why is the ethereum protocol a 'fat client'?
    - does ethereum actually have a protocol, or is it essentially running on something else?
    - rcp?
    - what is rcp?

* Solidity-Related Questions
    - what are addresses?
    - what are structs and how are they related to javascript 
  
* In The Wild-Related Questions
    - any successful uses of the technology


i've got this design in my head where you use IPFS + web3.js to interact with a local node running on a server. you execute your web3js 'site' by yourself, and use web3js to get updates via websocket or whatnot, and the site essentially becomes local to you. 

Is this a legit model for a 'new web'? or a 'new site'?

# Repository Planning

- README.md:
    * for seeing my thought process
    * my progress over the next month or so
    * describing all the directories/files in this repo

- Dockerfile:
    * i kinda wanna have more docker-stuff in my life
    * containers for (geth, web3js)

- Contract:
    * geth and contract related code
    * contest-related application?

- Web3JS:
    * vue application
    * express backend


Current Weekly Goal:
- 3 services up on Docker:
    * geth (F)
    * express/web3js application (W)
    * nginx (M)