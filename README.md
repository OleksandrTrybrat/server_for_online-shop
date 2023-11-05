# server_for_online-shop

![](./online-shop.png)

### Server to run mongodb and bandle files online-shop

**MongoDB database connection server.**
To start the server you need to clone the project `git clone`:

- then install npm modules using the **command** `npm install`;
- to connect to the database you need to create an environment variable .env file, in which you need to specify two variables **PORT=3000 and API_URL** - in this variable you need to substitute a link for connection
  (example: mongodb+srv://\*`name`:`password`@onlineshop.ebn3oto.mongodb.net/`name-database`?retryWrites=true&w=majority), where instead of `name, password, name-database` you should substitute Name, Password and Name of the partition in the database;
- or use the provided .env file
- also data from the mongo.json file should be copied into the database for correct launch of the Online-Shop web application on the `localhost:3000` port.
- **run script** - `npm run start` in the code editor (to start the server and connect to the database);
- Online-Shop project files before bandle build can be viewed and copied at: <https://github.com/AleksandrTrybrat/angular-online-shop.git>
