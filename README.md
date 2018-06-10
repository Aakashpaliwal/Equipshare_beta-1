# AuctionApp
This is the Auctioning platform.

For running the code locally, setup database first using steps given below. (in Linux, in this directory)
1. Install mysql, open it in terminal with a username using ``` mysql -u 'user' -p ``` then enter your password. default use root.
2. Make a new database named eqsAuction using ``` CREATE DATABASE eqsAuction; ``` 
3. Perform ``` USE eqsAuction; ```
4. ``` source config/database.sql; ```

This will set your database in the machine locally. Now,

5. Exit from mysql terminal and change the database config on "config/database.js" (if any).
6. Also make corresponding changes in the file config.js.
7. Perform  ``` npm install ``` first and then setup the database accordingly.
8. Run ``` node server.js ``` to run the application.

P.S. you may change database name, but makesure the changes are reflected in the above mentioned files.
P.P.S. while uploading code to server check that the configs are changed to that of server's database.
