## Quick overview

- Anyone can create a proposal to vote on
- A proposal is a shared object, so anyone can vote
- To ensure each voter is unique, we add every new voter through Dynamic Fields
- We use Dynamic Fields to bypass the object size limit. With Dynamic Fields, each voter is stored in a separate object, which is slightly more expensive but scalable. In this model, the number of voters is unlimited
- Transactions are sponsored through Enoki to demonstrate a unique feature of Sui. Note that in this project it’s implemented in an insecure way for easier demonstration
