# McBurgs - Create your own burger, or choose one from our delicious menu and get ready to eat!

### Overview
A Node, Express, Handlebars, and MySQL burger app that lets users input the names of burgers they'd like to eat... and then devour them!
Please check out the launched app on Heroku [here](http://eat-da-burgerz.herokuapp.com/)!


### Functionality
Using an home-grown ORM, the app has 3 basic CRUD functions...
  1. READ all entries from the MySQL database and display them to the DOM using Handlebars.
  2. UPDATE a selected burger by clicking "Devour It", which...
    * hits an `/burger/eat/:id` route in Express to change its "devoured" status in the MySQL database
    * re-routes the webpage back to the index, where the burger is now in the devoured column (via Handlebars)
  3. CREATE a new burger using the "Place Order" form, which...
    * hits a `/burger/create` route in Express to insert a new burger into the MySQL database
    * re-routes the webpage back to the index, where the burger is now ready to be eaten column (via Handlebars)

# Technology Used
1. Javascript
2. jQuery
3. NodeJS
4. Express.js
5. HTML
6. Bootstrap
7. Handlebars
8. MySQL

# Live Link

https://radiant-ridge-66111.herokuapp.com/

# Screenshot


<img width="1438" alt="Screen Shot 2019-07-11 at 4 31 47 PM" src="https://user-images.githubusercontent.com/44654955/61092045-6c429d80-a3f9-11e9-8b51-2c1bd8eb0b00.png">
