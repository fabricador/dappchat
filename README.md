# DappChat
DappChat, as its name suggests, is a chat dapp, where users can create their own chat "rooms", and put a price for the entry, this way, the user who wants to participate in the chat, both reading and sending messages, must transfer the money to the owner of the chat room.
demo page: https://fabricador.github.io/dappchat/

# Methods
createChat: Passing the arguments of title, description and price, the user can create a new chat, so people can access it and start to participate

getChat: Returns the data of a chat by his index

getChatsLength: Returns the number of chats

getMessage: Returns the message creator, and content by his index

getMessages: Returns the list of indexes of messages by the post index

getMessagesLength: Return the number of messages created

joinChat: Adds the user to the list of participants and transfers the price to the owner of the chat

sendMessage: Adds a message to the map of messages, and also, adds the index of the message to the chat list of messages

# Install

```

npm install

```

or 

```

yarn install

```

# Start

```

npm run dev

```

# Build

```

npm run build

```
# Usage
1. Install the [CeloExtensionWallet](https://chrome.google.com/webstore/detail/celoextensionwallet/kkilomkmpmkbdnfelcpgckmpcaemjcdh?hl=en) from the google chrome store.
2. Create a wallet.
3. Go to [https://celo.org/developers/faucet](https://celo.org/developers/faucet) and get tokens for the alfajores testnet.
4. Switch to the alfajores testnet in the CeloExtensionWallet.
