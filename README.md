***
## Install

To install all dependencies you need only to run:
```sh
npm install
```
However, if you plan on editing data you may find it helpful to install Nodemon running: 
```
npm install --save-dev nodemon
```
Please review <a href ="https://www.npmjs.com/package/nodemon">Nodemon</a> documentation if you are unfamiliar with the package.

***
## Usage
Run the following command at the root of your project starting with:
```
mysql -u root -p
``` 
Next, enter your password for MySQL. Once you are in your server run: 
```
SOURCE db/schema.sql
quit
``` 
Then run:
```
npm run seed
```
Finally, choose between running: 
```
nodemon server.js
OR
npm start
```
You can download <a href="https://insomnia.rest/download">Insomnia</a> to manipulate/test the data with the GET, POST, PUT, DELETE request.

***
