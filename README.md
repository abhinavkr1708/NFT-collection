# NFT (Non-Fungible Token) Collection

Enables whitelisted users to mint a collection of NFTs named `Brahmaputra NFTs` on the Sepolia testnet. 
The project can be viewed [here](https://nft-collection-swart-two.vercel.app/). <br />
The contract can be accessed [here](https://sepolia.etherscan.io/address/0xE68EFffB7caD10C0AdD9522055c4c9F2ee0e2393). <br />
The collection can be viewed [here](https://sepolia.etherscan.io/token/0xe68efffb7cad10c0add9522055c4c9f2ee0e2393).

## More Details

The dApp has been deployed on Sepolia Testnet of Ethereum. The backend of the dApp has been created using [Hardhat](https://hardhat.org/) and is available in the [hardhat-tutorial](https://github.com/Tanmay-Bhatnagar-03/NFT-Collection/tree/main/hardhat-tutorial) directory. Smart contract for the project is available in [hardhat-tutorial/contracts](https://github.com/Tanmay-Bhatnagar-03/NFT-Collection/tree/main/hardhat-tutorial/contracts) directory and it is written in [Solidity](https://soliditylang.org/). The deployment script for the smart contract is written in [JavaScript](https://developer.mozilla.org/en-US/docs/Web/javascript). <br />

The frontend of the website has been created by [Next.js](https://nextjs.org/) and deployed on [Vercel](https://vercel.com/). The website automatically sends a prompt to connect your wallet ([MetaMask](https://metamask.io/)) and you are then required to approve the request in the wallet.<br />

If you are a whitelisted user, you will be allowed to mint an NFT in the collection by clicking the `Public Mint 🚀` button. Be sure to change your network to [Sepolia](https://sepolia.dev/) in the wallet. You can now cross-check that you have received the NFT by going to contract address on [Sepolia Blockchain Explorer](https://sepolia.etherscan.io/address/0xE68EFffB7caD10C0AdD9522055c4c9F2ee0e2393).<br />

The website is built such that if we want to launch a new collection, the old contract address can be replaced by the newer one and the subsequent steps such as `Start Presale`, `Presale Mint` and `Public Mint`, can be taken on the site itself with a single click. 

## Features (Current and Upcoming)

- [x] The dApp connects to the wallet automatically and checks whether the user is whitelisted.
- [x] Only whitelisted users can mint NFTs for the collection.
- [x] Project has been deployed on Sepolia and hence, users have to change their network to Sepolia before site can be accessed.
- [x] The total supply of NFTs has been set to 1 but can be changed according to owner's discretion.
- [x] On clicking one button, an NFT can be minted to your wallet address.
- [x] NFT holders have to be given special privileges such as in gaming, future NFTs of the collection, future decisions in NFT Collection, etc.
- [ ] Host the NFT metadata on a decentralized platform such as [IPFS](https://ipfs.tech/).

## Contribution

Feel free to contribute to this project to make it better!

## License

This project has an MIT License.

## Made by love

- [StarterTemplates](https://twitter.com/startertemp)
- [LearnWeb3DAO](https://learnweb3.io)
