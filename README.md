# FairCoin commit id tracker
To ensure that repositories can't be manipulated a commit id can be tracked on faircoin blockchain and allows it to compare the commits in the repository with the commits on blockchain.

### How it works

Every repository gets a public faircoin address.
Every developer gets a faircoin address.

When a developer has done changes he/she gets the commit id ( hexadecimal number ). 
This hex number will converted to decimal and results in a small faircoin amount where all 8 decimals can be used.
When he/she has sent this amount to the faircoin address of the repository then the id is stored within the blockchain timestamp.

By usage of a modified block explorer that can show hex instead decimals the list of commit ids can be checked.
