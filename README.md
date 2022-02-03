# NFT-BiddingEvent
NFT site for Charity Events. Users can donate NFTs and bid the event's NFTs.

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify

About https://demetergift.com/

The site is for Charity Event Hold. The site is using TERRA COIN as base coin.
So, the first thing for you is to install Terra Station Wallet Extension to your browser and Sign Up and Sign In to your account. 
And for Terra Station Wallet, you can refer to https://chrome.google.com/webstore/detail/terra-station-wallet/aiifbnbfobpmeekipheeijimdpnlpgpp
Ok, are you ready now to hit our site?

1.	What is our aim?
We’re aimed to the create huge crowd of Charity based on NFT blockchain. What if someone hosts a charity event and other users bid the event.
2.	What features do we recommend?
As most of NFT sites do, we support the Swap, Realtime Crypto Currency, Volume of the paired Coins.
And last but not least, the most important part of our site , like I said before, creating Charity events for bidding.
1)	Swap
Users could exchange crypto assets with each other directly with the help of token swaps. You can just enter the amount you need to exchange alongside the desired trading pair for the swapping process. The token swap smart contract would process the transaction instantly, followed by conversion of the coin.
Users have to connect to their coin wallet like Terra Wallet.
Then, select the tokens that you’re going to swap with.
For that, you have to import those tokens that you’re going to swap to the wallet.
And of course, the balance of the *From Coin* should be bigger than number of token
If Swap successfully is done, then you can check the swapped coins’ information and balance in your wallet.
2)	Tokens
In this page users can have a look at the list of all tokens our site supports containing their own. It is something that you can see in the https://coinmarketcap.com 
3)	Pairs
How Do Crypto Trading Pairs Work? Cryptocurrency pairs allow you to compare costs between different cryptocurrencies. These pairings help illustrate the relative worth of coins — for example, how much Bitcoin (BTC) equals in Ethereum (ETH) and how much ETH equals in Bitcoin Cash (BCH).
You can see all trading pair of tokens that our site supports there.
4)	Donation
This is the page where user can donate new NFT or Cryptopunk to the existing Charity Event and can bid there.
All the NFT or Cryptopunk has options for its name, description, price, image url, NFT address.
If you submit all information for the NFT, you can see your NFT in the Event.
Then go to Auction page where users can bid.
When bid, user can use two type of coins, LUNA and UST.
For deep understanding, here’s small explanation about TERRA LUNA.
The aim of the Terra blockchain is to create stablecoins, tokens designed to combine the decentralised freedom of cryptocurrencies with the stability of fiat money. LUNA is a key piece to this system and is described as a staking or protocol token.
The blockchain has implemented a dual token system between the stablecoin terraUSD (UST) and LUNA to achieve this aim. USTs are minted by burning LUNA and can also be swapped for LUNA. 
For example, if the UST value goes above $1, the equivalent value of LUNA would be burned, which mints more UST, making it less valuable. Whereas, if the UST price drops below $1, they are swapped for LUNA which in turn makes UST more valuable.

For the events for TERRA wallet, users should select the bidding wallet type, LUNA or UST. 
For the TERRA Station Wallet extension, there are two tokens as default, LUNA (Native Token), UST(Stable Coin),  that users can vote with.
Basically all the transaction in TERRA Network is handled by UST.
Then input the bid amount in UST which is bigger than the current maximum bid amount. 
If LUNA is selected, we get the current LUNA coin’s real-time price comparing to UST from the free api from the coinbase and the system automatically calculates the bid amount in LUNA and submit to the wallet the LUNA amount as a bid amount. 
So for example, if the user wants to bid with 10 UST and selects the LUNA as wallet type, then the LUNA bid amount is 10UST/ LUNA currency and it will be lost from the LUNA balance in your TERRA Wallet if transaction is successful.

And also there’s category list for bidders to know where their money goes to.
These categories are created when event holder creates new event.  
Users can select one or more category and press *Bid NFT* or *Bid Cryptopunk*.
This will direct user to the browser’s wallet extension.  
On the pop up, user deny or accept the transaction.
If the transaction goes successful, then the max bid amount will be yours.
Also the category the user selected would be updated as reducing its amount by one.
For example, if there was 5000 pieces for Category 1, it would be 4999 pieces if the transaction is done.
5)	Create Events
Here users can create a new event and hold it.
Every event has the options for Event title, Event End Date, Event Wallet Address, Event Goal, Category for Support, Event Logo Link.
Event title describes the title of Event.
Event End Date is the last date when the event closes.
Event Wallet Address is the wallet address of event holder.
Event Goal is the total amount that the event holder aimed for the event.
Category for support is the list of categories that the bidders will bid to.
Event Logo Link is the image link of what describes the event’s logo.

Here’s the relationship between Event Goal and Category for support.
All the Category has the parameter of Title, Amount of pieces, Price of each piece, category image link.
Amount of pieces is the total amounts that the category has.
Price of each piece is the cost of each pieces.
So the total price of the category is Amount of pieces * Price of each piece.
And Event’s Goal is the sum of the total prices from the category.
For example, if category1’s amount is 1000pieces, and the price of each piece is 50 UST, then the total price is 5000UST. And if the Event’s Goal is larger than the total price of categories, then the rest of Event’s goal is assigned to Other Category.
So if Event’s Goal is 10000UST, there could be two categories – Category 1 and Other Support Category (costs 10000ust – 5000ust = 5000ust).



