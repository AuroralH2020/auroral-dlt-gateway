Hyperledger Fabric Smart Contract Gateway
=========================================

This repository provides an documentation of a configurable microservice that, in a nutshell, exposes functions of smart contracts that are deployed on an arbitrary Hyperledger Fabric channel as HTTP endpoints. The smart contract described in this section is based on the presupposition that the identifier of the AURORAL organization to which the invoking entity (human, or not) belongs is encoded in the invoker’s identity, i.e., as an attribute in her respective X.509 digital certificate. The smart contract’s handlers, by interfacing with HLF’s Client Identity Library, will be able to assert and retrieve the value of the invoker’s organization identifier. To ensure compliance with the off-chain infrastructure of AURORAL, the attribute will be named “cid”.

The example API specification used by this repository can be seen hosted at [https://https://auroralh2020.github.io/auroral-dlt-gateway/](https://https://auroralh2020.github.io/auroral-dlt-gateway/).

