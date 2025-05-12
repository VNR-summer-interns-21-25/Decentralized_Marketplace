This project contains the decentralized marketplace code part. It is not completely finished as you can see some functionalities donot perform optimally. Also, we were able to execute only orders smart contract, login was initiated, but couldnt be completed. But the blockchain implementation is done successfully. We have also used mongodb for some data storage, it would be great if you can try and eliminate it completely.

Use this code for learning purposes and we hope this code will be your base for the future endeavours. 

The things to be changed to run this project :
1) Install ganache, truffle, mongodb add metamask extension and install all the other dependencies. Connect the truffle-config file in this folder while setting env in ganache. Setup the mongodb database by understanding api folder using db1.products.json file.
2) You have to log in to 2 or 3 accounts in metamask using import->using private key, which is available in ganache.
3) In line 16 in contracts/Orders2.sol, change the address to any of your address of your ganache. 
4) First run truffle compile, then truffle migrate. Now you will find your smart contract deployed in ganache and you will get change in content in build/contract files.
5) you have a file called ans.json in src/components, replace all the content present in that with the content in build/contracts/Orders.json. 
6) There is a file called backend.json in src/components. Change the contractAddress to your ganache deployed address. check in ganache and change it. 
Thats it, you are ready. Make sure ganache,mongodb database is always started when you run this project. 
To run, npm start and nodemon server in two different terminals.


