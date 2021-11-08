# cardano-wallet-api-setup

This project provides instructions on how to run a cardano wallet API server process that points at a testnet

### Why is this useful?


### Key Details
- The private testnet consists of three block-producing node processes.
- The `cardano-db-sync` process syncs blockchain data to a highly normalized database schema. This enables blockchain data to be queried with SQL.

### Medium article
For an additional overview of this project, please check out this [medium article](https://medium.com/@extramileit/how-to-set-up-a-private-cardano-testnet-5e5afaa22d0b)

## Usage Instructions

1. **Building cardano-wallet and running**

    * Install the following executables: `cardano-node`, `cardano-cli`, `cardano-db-sync`, `cardano-db-sync-extended`
    * Please refer to the [Build and run guide](1-BUILD_RUN.md) for instructions.

2. **Using the API

## Contributors

This project is provided free of charge to the Cardano community. The author of this project is a fan of Cardano, as well as a Cardano stake pool operator.
I am not affiliated with IOHK in any official capacity.

If you want to support the continued development of this project, you can delegate or recommend my staking pool:

- [**WOOF Cardano Staking Pool**](https://woofpool.github.io/)

## Contributing

If you'd like to help maintain this project, please feel free to submit a pull request. Please ensure that any script changes have been tested and verified.

## License

This project is licensed under the terms of the [MIT License](LICENSE).