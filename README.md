
# TT Restaurant E-Commerce Platform

TT Restaurant E-Commerce Platform is a modern e-commerce platform for a trendy restaurant developed by Thabiseak, allowing users to browse and order items such as Pizza, Pasta, Avocado Toast, Sushi Burritos, Acai Bowls, Quinoa Bowls, Laksa, Tacos, Burgers, Fries, and drinks (Coffee, Matcha Lattes, Kombucha, Smoothies, Fruit Infused Water, Coconut Water, Teas, Vegetable Juices, Sparkling Water, Milk), online.


## Installation and Usage

To install and run TT Restaurant E-Commerce Platform, you need to have the following prerequisites:

- A web server that supports PHP, such as Apache or Nginx.
- A MySQL database server, version 5.x or higher.
- A web browser that supports JavaScript, such as Chrome or Firefox.

To install and run TT Restaurant E-Commerce Platform, follow these steps:

- Clone or download this repository to your web server’s document root directory, such as /var/www/html or /htdocs.

- Create a MySQL database named trendy_restaurant, and a MySQL user named trendy_user with the password trendy_pass. Grant all privileges to the user on the database.

- Run the SQL script trendy_restaurant.sql in the database to create and populate the tables. You can use a tool like MySQL Workbench or phpMyAdmin to run the script, or use the command line:

```bash
  mysql -u tt_user -p tt_restaurant < tt_restaurant.sql

```
    
- Edit the file config.php in the project directory, and change the values of the constants DB_HOST, DB_NAME, DB_USER, and DB_PASS to match your database server, database name, database user, and database password, respectively.

- Open your web browser, and navigate to the URL of your project, such as http://localhost/tt_restaurant or http://example.com/tt_restaurant.

- Enjoy browsing and ordering online!
## Features and Demo

TT Restaurant E-Commerce Platform has 
the following features:

- Users can view the available items by category, level, or instructor.
- Users can search for items by keyword, title, or description.
- Users can register and log in to the website using their email and password.
- Users can order items and view their orders in their profile page.
- Users can rate and review the items they have ordered.
- Users can contact the website administrator by filling out a contact form.

You can see a live demo of TT Restaurant E-Commerce Platform.

## Features and Demo

TT Restaurant E-Commerce Platform has 
the following features:

- Users can view the available items by category, level, or instructor.
- Users can search for items by keyword, title, or description.
- Users can register and log in to the website using their email and password.
- Users can order items and view their orders in their profile page.
- Users can rate and review the items they have ordered.
- Users can contact the website administrator by filling out a contact form.

You can see a live demo of TT Restaurant E-Commerce Platform at [this link], or watch a video tutorial at [this link].


## Contact and Acknowledgements

TT Restaurant E-Commerce Platform is created by Your Name. You can contact me by email at your.email@example.com.

I would like to thank the following sources, authors, and collaborators for their help and inspiration:

 - Build a Restaurant Ecommerce Website with Shopify by Shopify
- How to Design a Restaurant Website by Lightspeed
- How to Build an Ecommerce Website in 7 Simple Steps by Ecommerce CEO

Note : 
This README is created only for the assignment purpose