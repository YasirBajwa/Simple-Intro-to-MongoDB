# Simple-Intro-to-MongoDB
First install the mongoDB from their official page and open the mongoShell
#How you can create, edit and remove data from MongoDB through CLI?
#Step:1
Use command is used to create the new database.
like use Student_Record
#Step:2
#How you can create the collections inside the database?
createCollection command is used for it.
for example db.createCollection("Record");
#Step:3
#Now show collections is used to see the collections inside the database.
like show collections;
#Step:4
#How you can insert new record inside your databse?
for example  db.Record.insert({name:"Yasir Bajwa",age:22,edu:"BSCS"});
Record is inserted in json format like Javascript object
#Step:5
#How you can see the inserted record from database?
#find() is used for this purpose
db.Record.find() will show all the inserted record of your collection
OR
db.Record.find().pretty() is used to see the record more properly or in a proper format.
#Step:6
#How you can edit or remove the record?
Simply remove and update function are used for remove and update the record respectively
db.Record.update({name:"Yasir Bajwa"},$set:{name:"Yaxir"}});
db.Record.remove({name:"Yasir Bajwa"});
These are the simple steps to create the databse and store the data.
