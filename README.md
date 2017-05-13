# Item-Catalog-Website

The Item Catalog project consists of developing an application that provides a list of items within a variety of categories, as well as provide a user registration and authentication system. Users who are logged in are able to edit, delete and add thier own items.

![image](https://github.com/AnanyaSharma22/Item-Catalog-Website/blob/master/images/Restaurants.png)

# Table of Contents

- Quickstart
- Documentation
- Requirements
- Usage

# Quickstart

An item catalog application written in Flask and sqlite3. The application provides lists of items grouped into various categories, and provides user authentication with **google account** and user registeration system.

- Homepage of the application shows all the cuurent categories and selecting particular category shows you all the available items for that category. 

- The application also provides JSON API for any catalog, or any item.

- Any User:
    * can see all the items and item details.
    
- Authenticated User:
    * can make any changes to the items and item details such as edit, delete and update.
    
![image1](https://github.com/AnanyaSharma22/Item-Catalog-Website/blob/master/images/main_menu.png)

# Documentation

A RESTful web application using the Python framework Flask along with implementing third-party OAuth authentication. You will then learn when to properly use the various HTTP methods available to you and how these methods relate to CRUD (create, read, update and delete) operations.  In this project, you’ll combine your knowledge of building dynamic websites with persistent data storage to create a web application that provides a compelling service to your users.

# Requirements

- Python 2.7
- SQLite 3.9.2
- Flask 0.9
- SQLAlchemy 1.0.12
- Google Client Secrets(client_secrets.json)

- Install Python 

- Install all the required pakages:
     
    - apt-get -qqy update
    - apt-get -qqy install postgresql python-psycopg2
    - apt-get -qqy install python-sqlalchemy
    - apt-get -qqy install python-pip
    - pip install werkzeug==0.8.3
    - pip install flask==0.9
    - pip install Flask-Login==0.1.3
    - pip install oauth2client
    - pip install requests
    - pip install httplib2

# Usage

Run following commands on the terminal for following function to be performed:

- To create Database:
    
    `` python database_setup.py ``
    
- To populate database with restaurants and menu items:
    
    ``python lotsofmenus.py``
    
- To run the appilcation:

    ``python project.py``
    
- In your browser, visit [http://localhost:5000](http://localhost:5000/) to view, access and test the restaurant menu application. You should be able to view, add, edit, and delete menu items and restaurants.


     
