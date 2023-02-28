# AI NFT Generator
It is a webapp where you can mint an AI generated NFT to your wallet.

### **Deployed Link:**
https://nft-ai.vercel.app/

### **Technology & Tools used:**
- Solidity + Hardhat 
- React
- Ethers.js
- NFT.Storage
- Hugging Face (for Stable Diffusion Model)

### **Workflow:**
1. Enter the Name and Description for NFT image you want to generate.
2. Stable Diffusion will generate an image from your prompt.
3. The image generated will be stored in IPFS.
4. This image can then minted into an NFT by approving the transaction by signing with your wallet.
5. You can see your NFT listed in NFT marketplaces (Testnet :smiley:).
