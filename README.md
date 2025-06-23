# STEEL Team

The STEEL team is a team funded the Ethereum Foundation (EF) which develops and
maintains the execution specs, and execution spec tests.

## Links

- [Contacts](https://carsons-eels.github.io/steel_site_demo/contact)
- [Blog](https://carsons-eels.github.io/steel_site_demo/blog)

## Ethereum Execution Layer Specification (EELS)

The [EELS](https://github.com/ethereum/execution-specs) project aims to
be a faithful, up to date, highly readable, implementation of the Ethereum
execution layer. It functions as a standalone client, with the intention to act
as a common point of reference for the efficiency focused production clients
such as geth, reth, besu, nethermind, etc. The client is _not_ intended to be
used in a production environment, and code comprehensibility is the primary
metric driving our development.

## Ethereum Execution Specification Tests (EEST)

The [EEST](https://github.com/ethereum/execution-spec-tests) project is a
sibling initiative, developed for production execution clients so that they
have a standardized set of tests in a common format (JSON), that allow the EF
to detect differences and potential regressions between clients. Production
clients download, consume (translate JSON objects into ethereum transaction
blocks), execute, and verify (using block hashes) the results. Clients must
pass all tests up to and including the current chain fork to be considered in
spec. Production client teams work with us to develop new tests.
