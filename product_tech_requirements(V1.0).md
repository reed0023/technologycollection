# Product & Technical Requirements:

*Written and developed by @reed0023 & @tomtom87 for the Technology Collection DAO*

*Latest Update: 01.08.18*

*This document is meant to serve as a guide of V1 Product and Technical requirements proposed by TECO, as well as a timeline for deliverables. Services, delivery dates, and specifics are subject to change based on the immediate needs of the Organization. Please contact @reed0023 or @tomtom87 for questions related to deliverables.*


### Supported Platforms:
 1. Technology Collection Online Portal/Mobile-ready site
    - To be supported by latest versions of Chrome, Firefox, & Safari
    - Support for IE not considered at this time

### Databases/Services/Servers:

Below is a list of databases, services, and servers that the ETF Foundation plans on implementing. 

 1. Ethereum Virtual Machine
    - Created by Vitalik Buterin @VitalikButerin
 2. Aragon OS
    - DAO Architecture
    - ACL Permissions Framework
    - Dapps
    - Voting
    - Vault
    - Token Manager
 3. Technical Token Standard
    - ERC-20
 4. Open Zepplin
    - Open source platform for distributing tokens
 5. Truffle
    - Testing framework
    - Ganache
 6. Binance
    - Account responsible for holding all backing tokens
 7. React.js
    - Javascript library for UI
 8. Aragon UI
    - Aragon-native toolkit of UI components
 9. Aragon.js
    - Javascript library for interacting with AragonOS
    - Is this in conjunction with React? Or in place of?

### API:
 1. Documentation to be completed...
    - Voting
    - Vault
    - Token Management
    - Organizational Information/Structure
    - Community Board

### Aragon OS:
The Aragon One Team has developed a series of Dapps in support of their Project. TECO plans to use the following Dapps:

 1. Voting
 2. Vault
 3. Token Manager

The Dapps listed above may or may not possess the functionality or robustness needed by the Technology Collection, but they will serve as a jumping off point for development. The exact usage of these Dapps as developed by the Aragon One Team will be described in detail in the coming days. Documentation for these Dapps may not be fully available at time of development. 

### V1 Feature Set

 1. Voting (deprecated in v1 MVP)
    - Proposal Creation
      - Text based title & body
      - PDF Upload
      - Permission-based (likely the Org. Creator -> CEO
    - Y/N Vote Option for Token Holders on Open Proposals
    - Token-to-vote ratio is 1:1; Y/N vote from Token Holder applies as many votes as Tokens currently in their Vault
    - Votes not submitted by end of the Proposal Period are 'abstained' and not included in vote total
    - Proposals require 51% majority to pass
    - In the event of a tie, proposal is null & void
   
 2. Vault
    - Incoming Transfers
       - Accept Transfers from valid Ethereum Addresses
       - Reject Ethereum Addresses from the following countries:
     - Outgoing Transfers
     - WIP...
      
 3. Token Manager
     - WIP...
 4. Community Board
     - WIP...


### Assumptions:
 1. Limited exposure to outside token holders; internal at first to identify bugs/issues 

### Constraints:
 1. Cannot be purchased by individuals in the US or the UK

### Deployment Timeline:

#### Week of:
7/30
  - Rough Draft of Business & Tech Planning Document V1 completed
  - Github Repository Created

8/6
 - Review, edits, approval of Business & Tech Planning Document V1
 - Development Begins

8/13
 - API Documentation Finalized
 - Unit Testing Documentation Finalized
 - Edge Case Documentation Finalized

8/20
 - Unit Test development begins
 - Test-DAO Deployed to Rinkeby Test Net
 - Invite Launch Team to Rinkeby Test Net DAO
 
8/27
 - Proposal development completed
 - Test proposal contract deployed with PDF

9/3
 - Vault development completed
 - Accept ETH on Rinkeby Test Net

...
