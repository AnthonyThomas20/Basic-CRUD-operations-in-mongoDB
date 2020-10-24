# Basic-CRUD-operations-in-mongoDB #

Install mongoDB community from https://www.mongodb.com/try/download/community 

Run the installer and then verify installation by going into the bin folder of the installed mongoDB location in command prompt and then executing command “mongo.exe”. The following output indicates successful installation of mongoDB.

![mongo1](https://user-images.githubusercontent.com/54772502/97082378-d4d18000-1626-11eb-8d43-a58700fb9390.PNG)

## Performing CRUD Operations ##

### *Create:* ###

By default mongoDB has three databases: admin, config and local. We can view them using the “show” command. The “use db_name” command is to create our own database and the “db.createCollection” command is to create a collection in the database which is a grouping of one or more documents in a database.
