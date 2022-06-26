# E-Commerce-Back-End-David-Ryan
Bootcamp HW 13 - building the back-end for an ecommerce app

## Table of Contents
* [Description](#general-description)
* [Deplyment](#deployment)
* [License](#license)
* [Contributing](#contributing)
* [Tests](#tests)
* [Questions](#questions)
    
    
## Description
This was a project for my coding bootcamp.  We had to build thet back-end for an ecommerce app.  I built the sql db schema, the models, the routes, and parts of the server.  Simply put, this app is meant to be run through an api testing app like Insomnia.  The user can use thte different routes to view the data on the database pertaining to products, their categories, and their tags.  To set up the app, simply follow the steps I'll outline right now.  First, load the schema into your MySQL Workbench (or whatever you use in its place).  Then open the app in your command line and 'npm run seed'.  This will seed the database.  Then run 'npm run start'.  This will turn on the local server.  Then go to your Insomnia (or similar program) and use this starting route: "http://localhost:3001/api/".  This is the root route.  It doesn't have anything attached to it though.  Use GET route "/categories" to see all categories.  Use GET route "/tags" to see all tags.  Use GET route "/products" to see all products.  Enter an id number after any of these to view a specific category, tag, or id, based on that id number.  You can use a POST route with "/categories", "/tags", or "/products" to create a new category, tag, or route.  Categories require a "category_name" in the body.  Tags require a "tag_name".  Products require "product_name", "price", "stock", and "tagIds" (the last one is an integer array and can be empty).  Entering an id after the route and using a PUT and the same body requirements allows for updating categories, tags, and products.  ID after the route and using a DELETE will allow for deleting categories, tags, and products by their id.


## Deployment
Not deployed.  See walkthrough video at https://drive.google.com/file/d/1NNQaXUlEWvfkCyFBKEC9BAefdh4Ym2Gd/view.

## License
This repository is not licensed.


## Contributing
This is just a bootcamp assignment.  No contributions.


## Tests
No tests were created for this project.


## Questions
Any questions?  Contact me on GitHub @ https://github.com/Kadika38 or email dryan10101@gmail.com.