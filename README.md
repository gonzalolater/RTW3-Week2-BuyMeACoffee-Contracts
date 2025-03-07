# BuyMeACoffee solidity contract

This repo contains a contract that implements tipping functionality.

Install dependencies with `npm install`.

Set up by creating a `.env` file, and filling out these variables:

```
GOERLI_URL="your Alchemy RPC URL"
GOERLI_API_KEY="your Alchemy API key"
PRIVATE_KEY="your wallet private key"
```

You can get an Alchemy RPC URL for free [here](https://alchemy.com/?a=roadtoweb3weektwo).

## !!! Be very careful with exporting your private key !!!

You can get your Private Key from MetaMask [like this](https://metamask.zendesk.com/hc/en-us/articles/360015289632-How-to-Export-an-Account-Private-Key).
If you have any questions or concerns about this, please find someone you trust to sanity check you! 

## !!! Be very careful with exporting your private key !!!

Deploy your contract with:

```
npx hardhat run scripts/deploy.js
```

Run an example buy coffee flow locally with:

```
npx hardhat run scripts/buy-coffee.js
```

Once you have a contract deployed to Goerli testnet, grab the contract address and update the `contractAddress` variable in `scripts/withdraw.js`, then:

```
npx hardhat run scripts/withdraw.js
```

will allow you to withdraw any tips stored on the contract.

--------------------------------------------------------------------------------
1. Deploy 
![image](https://user-images.githubusercontent.com/42863568/201966580-50b389eb-0196-4379-8484-2dae817a5745.png)

------------------------------------------------------------------------------------------------------------------------------
2. Alchemy interaction
![image](https://user-images.githubusercontent.com/42863568/201966921-f97e6b0d-2a4d-48e7-86bd-64c78ef1e65a.png)

------------------------------------------------------------------------------------------------------------------------------
3. Using my own wallet in metamask, to make transaccions and withdraw the assets.
![image](https://user-images.githubusercontent.com/42863568/201967843-f5ffddf1-2fbb-4779-ab8a-117db3ea1e50.png)

------------------------------------------------------------------------------------------------------------------------------
4. Mint Kudos 
![image](https://user-images.githubusercontent.com/42863568/201975782-4db99e93-47fb-4b38-939e-8457bfff837b.png)

------------------------------------------------------------------------------------------------------------------------------
5. NFT 

https://user-images.githubusercontent.com/42863568/236946425-85ce6c47-d307-473e-9128-cd13c1ee807b.mp4
