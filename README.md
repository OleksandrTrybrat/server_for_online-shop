# server_for_online-shop
server to run mongodb and bandle files online-shop

MongoDB database connection server.
To start the server you need to clone the project (git clone);
- then install npm modules using the npm install command;
- to connect to the database you need to create an environment variable .env file, in which you need to specify two variables PORT=3000 and API_URL - in this variable you need to substitute a link for connection
  (example: mongodb+srv://********:******@onlineshop.ebn3oto.mongodb.net/*******?retryWrites=true&w=majority),
where instead of **** you should substitute Name, password and name of the partition in the database;
- also data from the mongo.json file should be copied into the database for correct launch of the Online-Shop web application on the localhost:3000 port.
- run script - npm run start in the code editor (to start the server and connect to the database);
- Online-Shop project files before bandle build can be viewed and copied at: https://github.com/AleksandrTrybrat/angular-online-shop.git
