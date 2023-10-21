# Solana-NFT-Anchor

This project shows how to mint your first NFT on the Solana blockchain using Anchor and Metaplex. It is based on the [Calyptus Solana Track](calyptus.co)

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Common Issues](#common-issues)
- [License](#license)

## Installation

It is highly recommended that you start this project from scratch, following along with the [Calyptus Solana Track](calyptus.co). However, if you want to use this project as a starting point, you can fork and clone this repo, then run `yarn install` to install all the dependencies.

**NOTE:** You must use yarn to install the dependencies. If you use a different package manager, you will run into issues minting the NFT.

## Common Issues

### Program Id

If you use this project as a starting point, you will need to change the program id in the `anchor.toml` file and inside the `declare_id!` macro in the `lib.rs` file. To obtain the program id for your project, run `anchor keys list` in the terminal. You will see a list of all the keys associated with your project. The program id should look like this: `solana_nft_anchor: PROGRAM ID`.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

© [Your Name or Organization] - See [LICENSE](LICENSE) for details.
