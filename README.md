# NomadBnB

Welcome to NomadBnB; a AirBnB inspired website that allows users to post house listings as well as book available listings. This website allows users to be split into two types: Landlords and tenants. Tenants can only search for and book available listings, whereas landlords are able to search for and book available listings as well as post new listings.

- - - -

![alt text](images/GitScreens/NomadHome.png?raw=true "Home")

- - - -

### Built using
* [Javascript](https://www.javascript.com/) - Frontend and backend
* [NodeJs](https://nodejs.org/en/) - FrontEnd and BackEnd
* [Express](https://expressjs.com/) - FrontEnd
* [Express Handlebars](https://www.npmjs.com/package/express-handlebars) - FrontEnd
* [MongoDB](https://www.mongodb.com/3) - Database
* [SendGrid](https://sendgrid.com/) - Emailing API
* [BCryptJs](https://www.npmjs.com/package/bcrypt) - Password Hashing
* HTML/CSS - Frontend
* ... And many more...

- - - -

## You will need the following:
### _Prerequisites:_
You need to have installed [NodeJs](https://nodejs.org/en/), [MongoDB](https://www.mongodb.com/3)

### _Modifying the configs:_
*app.js* contains all the information needed by [MongoDB](https://www.mongodb.com/3) to connect NomadBnB to its database. The following lines control the connection
```
mongoose.connect('mongodb://localhost/NomadBNBv2');
mongoose.connect('mongodb+srv://Nomad0:Nomad0@cluster0-y2gv8.azure.mongodb.net/nomad?retryWrites=true');
```
The first line allows for local connections, make sure this line is not commented out.
The second line allows for the project server which sits behind campus firewalls. This will not work unless run locally on campus computers. As such it is recommended that you comment this second line out.

### Launch the server
As this is built in node, and is utlising Nodemon, your options are to either kick it off in the terminal using ```npm start``` or ```nodemon```. Both will work. This will start the node server on port 3000.

### Create the database
Launch your browser and head on over to: [http://localhost:3000](http://localhost:3000) . This will automatically set up the database in your local server. and automatically redirect you to the home page. 

- - - -

## Here are some screens:
Home: 
![alt text](images/GitScreens/NomadHome.png?raw=true "Home")

Listings:
![alt text](images/GitScreens/NomadListings.png?raw=true "Listings")

Register:
![alt text](images/GitScreens/NomadRegister.png?raw=true "Register")

Login:
![alt text](images/GitScreens/NomadLogin.png?raw=true "Login")

My Account:
![alt text](images/GitScreens/NomadMyAccount.png?raw=true "My Account")


## Author
* **Laune Treu** - *Frontend and Backend* - [LTreu](https://github.com/ltreu), [Skyla Darkthorn](https://github.com/SkylaDarkthorn)