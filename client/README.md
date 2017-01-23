# BlockChan Client
The BlockChan Client is a browser based JavaScript application. It enables the user to calculate the Bitcoin address representation of a file and browse the associated block chain messages. Alternatively, the user can enter the Bitcoin address directly or even enter a plaintext that is immediately converted to a Bitcoin address. The application attempts to decode all the transactions made to the specified Bitcoin address but only displays the ones that carry human-readable content. The client also includes light-weight functionality for the user to post their own block chain messages under the desired category (Bitcoin address). To push a new message on the block chain, the client makes a POST request to the BlockChan Server and provides the category (Bitcoin address) and content of the new block chain message. After that, it is up to the server and the agent to actually save the message on the block chain.