# Building a blockexplorer in React

## 1. Create a unique Alchemy API key

For the purposes of this project we'll use Ethereum Mainnet.

If you have not already done so, create a unique Alchemy API Mainnet key\
for your project as [described here](https://docs.alchemy.com/reference/api-overview).

## 2. Add your API key to an environment variable
Create an empty `.env` file in the base directory of this project.

Add the following line to the `.env` file replacing `YOUR_ALCHEMY_API_KEY`\
with your api key.
```sh
REACT_APP_ALCHEMY_API_KEY=YOUR_ALCHEMY_API_KEY
```

Do not remove the `REACT_APP_` prefix. React uses that to import env variables.

**⚠️ Note**
> Your Alchemy API Mainnet Key is a sensitive piece of data. If we were\
> building an enterprise app to conquer the world we would never place\
> this sensitive data in the client code of our blockexplorer project that\
> could potentially be read by anyone.
>
> But hey, we're just learning this stuff right now, not conquering anything\
> yet! :-) It won't be the end of the world to put the Alchemy API key in our\
> front-end code for this project.

## 3. Start the webserver
`npm start`

Running the command above will run the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

## 4. Display information about the Ethereum network

## 5. Display the following information
* What are the details of a given block?
  * eg: block number, block hash, timestamp,\
    number of transactions in the block
* List of transactions are included in a block?
* What are the details of a given transaction?

## 6. AlchemySDK bonus questions
* Did a pending transaction get mined?
* What NFTs and tokens does an address own?
* What transfers did an address receive this year?
* What is the floor price of an NFT right now?

## Additional Alchemy SDK Docs
[API Quickstart](https://docs.alchemy.com/reference/alchemy-sdk-quickstart)
[API Overview](https://docs.alchemy.com/reference/api-overview)



