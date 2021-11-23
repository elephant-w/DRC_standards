# DRC20: Fungible Token Standard
A standard interface for Dfinity tokens
 
## Abstract
A standard interface for Dfinity tokens. The standard complies with ERC20 interface specification, and has some improvements to match IC network features.

## Improvements

* Compatible with Principal and Account-id as Address

* Using the pub/sub model for message notifications

* Improving transaction atomicity with a lock/execute two-phase commit structure

* Scalability of transaction records storage, temporary storage in token canister and permanent storage in external canisters

## Features

* Immutability

* Scalability

* Internal Atomicity

* Governability


## Resources

Standard: [https://github.com/iclighthouse/DRC_standards/tree/main/DRC20/DRC20.md](https://github.com/iclighthouse/DRC_standards/tree/main/DRC20/DRC20.md)  
Example: [https://github.com/iclighthouse/DRC_standards/tree/main/DRC20/examples/ICLighthouse](https://github.com/iclighthouse/DRC_standards/tree/main/DRC20/examples/ICLighthouse)  
Comments: [https://github.com/iclighthouse/DRC_standards/issues/1](https://github.com/iclighthouse/DRC_standards/issues/1);