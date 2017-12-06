Item-Catalog Application Project:

I have developed an application that provides a list of Restaurants. Each restaurant displays their menu items 
and also provides user authentication using Google. Registered users will have ability to edit and delete their own items.

I have used python module that creates a website and JSON API for a list of restaurants. I have used SQL Alchemy, Flask, 
jQuery, CSS, Javascript, and OAuth2 to create Item Catalog website.

Installations:
 1.virtualBox 
 2.Vagrant 
 3.python 2.7

For setting up OAuth 2.0:

User will need to signup for a google account and set up a client id and secret.
Visit http://console.developers.google.com for google setup.

To set up the Project Environment:

1. clone or download this repo into vagrant environment.
2. Type command vagrant up, vagrant ssh.
3. In VM, cd item-catalog-application
4. Run python database_setup.py to create the database.
5. Run Python lotsofmenus.py to add the menu items
6. Run python projectlogin.py
7. Open your web browser and visit http://localhost:8000/

