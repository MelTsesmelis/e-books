# e-books

#WevDev e-library
	I created an online librady with options to add or search books
        I used windows system, sublime/vs editor, firefox/chrome, windows terminal,sqlite3

##Installation
   you have to install cors,express,sqlite3. A way for each is to run those:
   I recommend you to create a new folder in a directory and put them all in it.

For cors:
   npm install --save cors
For express:
   npm install --save express
For sqlite3:
   npm install --save sqlite3

For sqlite3 you have to follow this schema for best experience and better compatibility:
 CREATE TABLE books(id integer not null primary key,author varchar(25) not null, title varchar(40) not null,genre varchar(20) not null,price float not null );

###Server Connection
   You have to run this:
     node app.js 

Be carefull you have to be in folder/directory. 

####Results
   System listen on port: 
		2001

   System listen on those URL:
	POST: http://localhost:2001/books
	GET: http://localhost:2001/books/<keyword>        
   replace "<keyword>" with your own letter/word of a title to see the results.




