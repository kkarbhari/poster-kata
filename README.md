# Create source db of a salesDB containing tables relevant to customer/sales. 
# dw will contain the loaded transformation of data between the fake customer/sales data and the starship & other data from SWAPI.

Interacting with the Star Wars API

![swlogo](/swlogo.png)

Do you want to have a Star Wars Database inside a Docker Postgres Container in your computer?
Then look no further!
-------------------
To make it work simply clone the repo and run:
docker-compose up -d --build



It will run 2 containers, one with a postgres Database and another with a python script that will scrappe the SWAPI.
------------------

In this sample-project I wanted to get all information from the Star Wars API.
The program will start to get all his connections to Customer/Sales information etc.
Then for each connection I will get their connections and so on and so forth.
This way I will end up with all the elements and their details from the Star Wars API with needing to know them beforehand.

To connect to the Database use the following credentials:
----------------------------
PASSWORD: "mysecretpassword"

USER: postgres

DBNAME: source

HOSTD: localhost:5432
