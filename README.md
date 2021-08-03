# Auction-server

CO225 - Software Constructions
Project 02 (Group Projrct) - Auction Server
Group Number - 04
Members : E/16/068, E/16/069, E/16/070


## Compile and Run the server:

	javac MainClass.java
	java MainClass


## Connect as a client:

	nc localhost 2000	

### After connecting as a client,
	+ client should gives a user name
	+ then client is required to provide a symbol of a item that he wants to bid
	+ if client enter a invalid symbol he gets another another chance to enter a valid symbol
	+ the bid value entered by clien is accepted only if it is larger than current price
	+ client can logout using 'quit' word


## Server GUI details :
	+ the GUI displays the stock prices of FB, VRTU, MSFT, GOOGL, YHOO, XLNX, TSLA and TXN 
	+ it shows all previous bid details under the topic Bid history
	+ connection Details of each client is showed under the topic, client history
	+ can see all stock items by clicking on the view all items button

	* in this server many number of clients can connect at the same time but each client should have unique user names
	* after logged out a client from the server he can connect agin using nc command in the terminal and bid for previous stock or another stock
	
