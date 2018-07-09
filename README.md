# FlakeChain Core v0.2.0

Copyright (c) 2018 FlakeChain Team.
Copyright (c) 2014-2018 The Monero Project.   
Portions Copyright (c) 2012-2013 The Cryptonote developers.

## Development resources

- Mail: [cryptofoundry@icloud.com](mailto:cryptofoundry@icloud.com)
- GitHub: [https://github.com/flakechain/flake-core](https://github.com/flakechain/flake-core)


## Introduction

FlakeChain is a private, secure, untraceable, decentralised digital currency. You are your bank, you control your funds, and nobody can trace your transfers unless you allow them to do so.

**Privacy:** Snowflake uses a cryptographically sound system to allow you to send and receive funds without your transactions being easily revealed on the blockchain (the ledger of transactions that everyone has). This ensures that your purchases, receipts, and all transfers remain absolutely private by default.

**Security:** Using the power of a distributed peer-to-peer consensus network, every transaction on the network is cryptographically secured. Individual wallets have a 25 word mnemonic seed that is only displayed once, and can be written down to backup the wallet. Wallet files are encrypted with a passphrase to ensure they are useless if stolen.

**Untraceability:** By taking advantage of ring signatures, a special property of a certain type of cryptography, Snowflake is able to ensure that transactions are not only untraceable, but have an optional measure of ambiguity that ensures that transactions cannot easily be tied back to an individual user or computer.

# **Getting started**



## Windows CLI wallet:

  

Download latest wallet binaries. Create .bat or .cmd file containing following text

      snowflaked --data-dir ./blockchain

  

Wait for daemon to sync. As it is done, start `snowflake-wallet-cli.exe` and follow instructions.

  

## Windows GUI wallet:

  

Start it and wait for it to sync.

  

  

## Linux CLI wallet:

  

Download latest wallet binaries. Create shell script file with following content

  

    ./snowflaked --data-dir ./blockchain
  

Open terminal window in Snowflake binaries folder and run

  

    sudo chmod +x ./SHELL_SCRIPT_FILENAME
    
    ./SHELL_SCRIPT_FILENAME

  

Wait for daemon to sync. As it is done, open another terminal window and run

  

`./snowflake-wallet-cli` and follow instructions

## About this project

This is the core implementation of Snowflake. It is open source and completely free to use without restrictions, except for those specified in the license agreement below. There are no restrictions on anyone creating an alternative implementation of Snowflake that uses the protocol and network in a compatible manner.

As with many development projects, the repository on Github is considered to be the "staging" area for the latest changes. Before changes are merged into that branch on the main repository, they are tested by individual developers in their own branches, submitted as a pull request, and then subsequently tested by contributors who focus on testing and code reviews. That having been said, the repository should be carefully considered before using it in a production environment, unless there is a patch in the repository for a particular show-stopping issue you are experiencing. It is generally a better idea to use a tagged release for stability.

**Anyone is welcome to contribute to Snowflake's codebase!** If you have a fix or code change, feel free to submit it as a pull request directly to the "master" branch. In cases where the change is relatively small or does not affect other parts of the codebase it may be merged in immediately by any one of the collaborators. On the other hand, if the change is particularly large or complex, it is expected that it will be discussed at length either well in advance of the pull request being submitted, or even directly on the pull request.

## Supporting the project

Snowflake is a 100% community-sponsored endeavor. If you want to join our efforts, the easiest thing you can do is support the project financially. Both Snowflake and Bitcoin donations can be made at **snowflake.cf**. 

The Snowflake donation addresses are: `4C7b1NzfZWyYjmRN4Q7JUeMciuMaboeG1PgCCHRKpnbHYnCQfxcJNy37TS1gqdnm7M2EypLPFJ7gpDAVJzn8GkzF5wmeWuMrUikK64nXTk` for XMR donations.

 `1BraHuZ94KeuWNLGoh3rjZg8FRrMzqZwRZ` for BTC donations.

`0x6937fffc49001b75ab18efced5444163c615f44c` for ETH donations.

`LUYqMEraNP9rETFM4sEiGozLbbECHmz3qs` for LTC donations.


## License

See [LICENSE](LICENSE).

## Contributing

If you want to help out, see [CONTRIBUTING](CONTRIBUTING.md) for a set of guidelines.



