"# MongoDB-installation-and-Basic-commands." 
******************MongoDB Installation (Windows)******************
1.	Go to the web site https://www.mongodb.com/download-center#community and download .msi file.

2.	Click on downloaded file to install database, you can select any one option from either Custom or Advanced.

3.	If you are not able to install MongoDB then Uncheck the Compass option while installation and install again. Now to install compass we need to again install same .msi file and select first option ie.Repare.

4.	Now we need to set Environment variables for our MongoDB, to do this follow the steps
   i.	 Simply search for Environment variables and select
Or
   i.	Right Click on My Computer and select Properties option.
   
   ii.	In System Properties Pop-Up select Environment variables in advanced tab.
   
   iii.	New Environment variables Pop-Up will appear. Double click on PATH variable.
   
   iv.	 There may be other paths set already we need to paste our path at the end of all paths, all paths are separated by Comma (;).
   
   v.	To copy MongoDB Path go to the folder where your MongoDB is installed and copy the path of file mongo.exe till the bin folder. In My case it is “C:\Program Files\MongoDB\Server\3.6\bin”.
   
   vi.	We are done with setting the environment path for MongoDB.
   
5.	Now to run MongoDB run the mongod.exe file, it will open with command line window.

6.	Now to run MongoDB run the mongo.exe file, it also opens command line, we have to run our commands here.

******************Some use full MongoDB commands****************
   1.	To List Databases  
      •	show bds
      
   2.	To display database we are using.
      •	db
      
   3.	To use particular database or create new database 
      •	use <database_name>
      
   4.	To create collection under current database or create new collection.
      •	db.<collection_name>.insertOne( { x: 1 } );
   Here the parameters to the insertOne() method “{ x: 1 }” is data to be inserted.
   
   5.	There are many methods you can refer https://docs.mongodb.com/manual/mongo/ page for more details.
 

