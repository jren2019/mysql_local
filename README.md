# Set up MySQL database with Docker for local development
Multiple Databases <-- docker-compose.yml

login via: http://localhost:8080


This repo is trying to spin up a local database with Docker. This makes it easy to test your code and write data without installing and configuring a lot of tools. It explains how you can customize your Docker database via scripts, create database and tables. While this repo is for MySQL, it’s the same for PostgreSQL!
Follow along and let’s create a custom MySQL which contains your desired tables and data.


connect mongo with mongo shell:

mongo $MONGO_SERVER/$MONGO_INITDB_DATABASE -u $MONGO_INITDB_ROOT_USERNAME -p $MONGO_INITDB_ROOT_PASSWORD

mongo --port 27017 -u "admin" -p "admin" --authenticationDatabase "admin"


Reference:

- https://zgadzaj.com/development/docker/docker-compose/containers/mongodb
