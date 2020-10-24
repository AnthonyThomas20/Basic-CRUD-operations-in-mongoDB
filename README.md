# Basic-CRUD-operations-in-mongoDB #

Install mongoDB community from https://www.mongodb.com/try/download/community 

Run the installer and then verify installation by going into the bin folder of the installed mongoDB location in command prompt and then executing command “mongo.exe”. The following output indicates successful installation of mongoDB.

![mongo1](https://user-images.githubusercontent.com/54772502/97082378-d4d18000-1626-11eb-8d43-a58700fb9390.PNG)

## Performing CRUD Operations ##

### *Create:* ###

By default mongoDB has three databases: admin, config and local. We can view them using the “show” command. The “use db_name” command is to create our own database and the “db.createCollection” command is to create a collection in the database which is a grouping of one or more documents in a database.

![mongo2](https://user-images.githubusercontent.com/54772502/97082490-c9328900-1627-11eb-9013-27555d3a3323.PNG)

The “db.collection_name.insertOne” command is used to create a single document within the collection_name of the database. While the “db.collection_name.insertMany” command is used to create multiple documents within the collection_name of the database.

![mongo3](https://user-images.githubusercontent.com/54772502/97082527-0a2a9d80-1628-11eb-8865-b20eb1c808d3.PNG)
![mongo4](https://user-images.githubusercontent.com/54772502/97082531-0e56bb00-1628-11eb-91bc-f8f2ff053fa3.PNG)
![mongo5](https://user-images.githubusercontent.com/54772502/97082532-0eef5180-1628-11eb-8854-306afc037091.PNG)

### *Read:* ###

The “db.collection_name.find()” command is used to display all the documents in the given collection of a database. We can also search for a particular document by passing the desired parameter in the “db.collection_name.find()” command.

### *Update:* ###

The “db.collection_name.updateOne” command is used to update a single document within the collection_name of the database based on a specific condition. While the “db.collection_name.updateMany” command is used to update multiple documents within the collection_name of the database based on a given condition. To verify that updation takes place, check that the value of “matchedCount” and “modifiedCount” is the same and greater than 0. The results can also be verified by using the find() command to display all updated documents.

![mongo6](https://user-images.githubusercontent.com/54772502/97082579-6a214400-1628-11eb-97d6-d84e4dfc4f5d.PNG)

### *Delete:* ###

The “db.collection_name.deleteOne” command is used to delete a single document within the collection_name of the database based on a specific condition. While the “db.collection_name.deleteMany” command is used to delete multiple documents within the collection_name of the database based on a given condition. The results can be verified by using the “db.collection_name.find()” command to display all the current documents in the collection.
