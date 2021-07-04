# Robotic-arm-Base
Just like the previous task we are using Python for this task were we are going to create the base's UI and also its database.

# Base-UI
After importing the tkinter library from we choose the size of the window, background color and title. After this i created the button which are supposed to direct the base movement in all 4 directions and a fifth button to stop it from moving. Currently the button have no function because we haven’t connected it with the database.  

# Base-Database
i connected mySQL using the mysql.connector function and defined the host, username and password. After that i created my database after defining the connection with MySQL as mycursor and i named the database BaseDB. I then commented the creation command and went back to the connection and added the database and its name there. I added a command to show me the database to ensure its existence after that I commented the command so it won’t overlap So now mycursor also has the database defined in it and we can create a table and place it inside the database which we did and named the table Base and added 2 columns inside of it "ID" for the number of the command that we are giving, and "Status" to indicate the direction the base is moving in. lastly in order to ensure out work is complete i gave the "SHOW TABLES" Command to ensure the table was correctly created. i included a picture of the database inside the file but since i havent connected it with the UI it is empty.
