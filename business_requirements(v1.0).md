## Business Requirements:
*Written and developed by @reed0023 & @tomtom87 for the Technology Collection DAO*

Latest Update: *6.19.21*

*This document is meant to serve as a guide of V1 business requirements proposed by TechCollect. Features, delivery dates, 
and specifics are subject to change based on the immediate needs of the Organization. Please contact @reed0023 or @tomtom87 for questions
related to deliverables.*

### Summary: 
Developing the V1 framework for the Technology Collection - a Decentralized Autonomous Organization

### Purpose:
Provide a token to crypto enthusiasts that is backed by the best blockchain technologies, as voted on by the Community of Token Holders

### Objectives: 

- [ ] 1. Deploy a DAO using the Aragon One Project to the Ethereum Virtual Machine
- [ ] 2. Accept 1 ETH from Launch Team 
    - .2 ETH from each individual 
- [ ] 3. Distribute One TECO Token each individual on the Launch Team
    - CEO
    - CTO
    - CFO
    - COO
    - Community Leader
- [ ] 4. Hold an inaugural vote for Launch Team
    - Launch Team Proposal for positions

### Scope
 1. V1 to include:
    - Voting
      - Yes/No Voting for Token Holders on Proposals
    - Proposals
      - Create Proposal
        - Text-based Title & Body
        - Upload PDF Capability
        - "Create Proposal" Permission-based
          - Single Token Holder has permission to create proposals
          - Permission can be transferred to new Token Holder
        - Token ownership necessary to View & Vote on proposals
      - Table to view all past and ongoing Proposals
        - Columns: | Status | Title | % Voted | Result | Actions |
          - Actions: Vote if Token Holder has not Voted, View if Token Holder has voted
            - View & Vote both link to the Proposal, but Token Holders who haven't voted will have the option at the bottom to
            answer Yes or No
        - Rows: Past Proposals in Chronological Order
        
    - Vault
      - Accept/Transfer ETH on behalf of the DAO
        - Limit to 1 ETH per transaction
        - This does not include other alt-coins, cryptocurrency, or other blockchain technologies at this time
      - Dashboard
        - Backing Token Balances
          - Backing Token Percentages
        - Table of incoming/outgoing transfers

    - Token Management
      - Set Outstanding Token Amount
        - Permission-based
          - Similar to Proposal Creation - single Token Holder has permission which can be transferred
        - Add new Tokens
      - Distribute Token to new Address
      
    - Community Board
      - Discussion Thread
        - Create Discussion
          - Text-based Title & Body
          - Comment section
           - Text-based reply
        - Archive Discussions
        - Add/delete "Avatar" picture
        
 2. V2 to include:
    - Vault
      - Accept two different Tokens
        - Tokens TBD
    - ACL
    - Radspec (Human-readable Transactions)
    - TECO Token Waitlist
