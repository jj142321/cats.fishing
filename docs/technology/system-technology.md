# System Technology

## System Architecture

![](https://whitepaper.myneighboralice.com/\~gitbook/image?url=https:%2F%2F1239201526-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FxXeTlUadpyOyxw6Ks2L7%252Fuploads%252FTbkIOPRG5DylGbmzk1Pw%252Fimage.png%3Falt=media%26token=313c7c4c-0bdc-44f3-86d6-ac5cd0a2c2b6\&width=768\&dpr=4\&quality=100\&sign=0e3076a7f1e9e840e92428214be7ecc90ab43d4d9ff200faf960c8cc929421d9)

### Game Core <a href="#game-core" id="game-core"></a>

#### Backend: Solana <a href="#backend-chromia" id="backend-chromia"></a>

The first layer to this project is the game backend infrastructure. The project was created on the fundamental idea that it will operate exclusively on the Solana platform, with a few exceptions mentioned in this document.

The backend is a Solana relational blockchain database that is used in conjunction with Unity to operate accounts, token transfers, relational data and user progress, among many other things. It’s meant to follow the development of cross chain playability and interaction with NFT:s. The unique database aspects of Solana gives the ability to do complex backend logic directly on the blockchain without spending much development time.

#### Frontend: Unity <a href="#frontend-unity" id="frontend-unity"></a>

The second layer to the project is the client, developed in unity. The largest part is the procedural building system. It's essential that it is fun, feels great and is on par with other building games on the market.

Second biggest is the focus on gameplay loops and daily activities with player retention in consideration. We also work on connecting the backend with frontend, login-registration edge cases, and multiplayer scalability & stability.

### Game Economy <a href="#game-economy" id="game-economy"></a>

The third area in the project is the economic infrastructure. “Property/Plot” auctioning, asset trading, token transactions.

#### Backend: Solana <a href="#backend-chromia-1" id="backend-chromia-1"></a>

Gaming, marketplace and auction logic is done on the Solana blockchain

#### Frontend: Web and Unity <a href="#frontend-web-and-unity" id="frontend-web-and-unity"></a>

The frontend to marketplaces and auctions can be done as a web application embedded into the game. Parts of the UX might also be done directly in Unity.

#### Integrations: ERC20 and Steam <a href="#integrations-erc20-and-steam" id="integrations-erc20-and-steam"></a>

The BONE$ token will be transferable between ERC20 and native Solana token. The Steam marketplace and sales there will have an integration code connecting to web based game.

### Governance DAO <a href="#governance-dao" id="governance-dao"></a>

This project will not only create a game, but code for a decentralized autonomous organisation called Community Council.

The DAO implementation should be handed out to an external company, we identified TBD as the initial partner.

#### Backend: Solana <a href="#backend-chromia-2" id="backend-chromia-2"></a>

Voting and rules of governance can be implemented in Solana. Being a relational database, this is comparatively easier than with other blockchains.

#### Frontend: Web <a href="#frontend-web" id="frontend-web"></a>

The DAO interface will be a web application, outside of the Cats Fishing game.

#### &#x20;<a href="#integrations-chromunity" id="integrations-chromunity"></a>
