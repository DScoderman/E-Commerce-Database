# E-Commerce-Database

## Description 

A database designed to connect and store retail products! This was built using the power of Javascript, express, mySQL and Insomnia. By using Javascript, I was able to connect the models and schema together and check
the results via insomnia. 

## Installation

While the JSON packages come with the code created, you'll need to download insomnia. Click here for a link to insomnia. 

To install the JSON packages, right click on the server.js file on the very bottom of the file explorer and click "open in integrated terminal". From there, click inside the terminal and run the command "npm i". This will install 
all packages used in the code.

You will also need to set up a mySQL account and have that software installed on your computer. To do that, best refer to their documentaiton. 

## Usage. 

To begin, open up the integrated terminal in the server.js file at the very bottom of the file explorer. From there, make sure you enter the command "npm i" to install everything. Assuming you are set up with mySQL, run the 
following command in the terminal: "MYSQL -u root -p". This command will have you log in via the terminal to your mysql account. Once in, enter this command: "SOURCE db/schema.sql". This gets us to use the database properly. 
Next step is to quit out of mySQL by running the "QUIT" command in the terminal. You will know you did it as the terminal will say "BYE" once done. From there, run the command "node seeds/index.js" (this will populate the database with data to use), 
followed by the command "node server.js" (to get the local port listening). To see how it works in Insomnia, check out the video below:


[Link for the video](https://drive.google.com/file/d/1V2YU98TcQDWtBQCmTcjFI0U9jp6bfWS6/view)

## License

Using the MIT license, so go for it!



