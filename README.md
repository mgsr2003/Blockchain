Objective
Using the blockchain you built in Activity 1, extend it with:
• Stronger Proof-of-Work,
• Richer transaction handling,
• Documentation & reflection.
This will give you a full working blockchain simulation that demonstrates immutability
and consensus basics.
Requirements
1. Proof-of-Work (Mining)
• Keep the mineBlock(difficulty) method, but:
o Set difficulty = 3 minimum.
o Show in the console that hashes begin with at least 000.
• Print the number of attempts (nonce) it took to mine each block.
2. Transactions
• Transactions should be represented as objects, e.g.:
{ from: 'Alice', to: 'Bob', amount: 50 }
• Each block must hold one or more transactions (array).
• Add at least 5 transactions total across your chain.
3. Blockchain Validation
• Confirm your isChainValid() method detects tampering.
• In your demo:
o Print Is chain valid? true for the untampered chain.
o Manually modify a transaction in Block #1.
o Print Is chain valid? false afterward.
4. Documentation & Reflection
• README.md (in your project folder):
o How to run your code (node blockchain.js).
o Screenshot of mining output & validation check.
o Short reflection (~300 words):
▪ What did you learn about hashing & immutability?
▪ Why does Proof-of-Work make blockchains secure?
▪ What surprised you while coding this?
Deliverables
Submit a GitHub repo containing:
1. blockchain.js (your code).
2. README.md with explanation + screenshot.
3. Console screenshot showing:
a. Mining of 3–4 blocks.
b. Valid chain = true.
c. Tampered chain = false
