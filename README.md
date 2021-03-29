# Basic-Database-Management-Application

This application is solely coded in Python. This app will allow users to CREATE, EDIT, SEARCH, & DELETE data stored within the local database.

To run this program, you must have WSL2 installed and running on your PC. I have chosen Visual Studio Code as my choice of IDE. 
A side note, make sure your python3 is installed and up to date.
After having all the software setup and running, you can download the repository into the directory of your workspace for WSL.
To start the application, type in "python3 bdma" or "python3 (and the name of which you named the application)".
This will initiate a menu prompt to choose from: 1. CREATE 2. EDIT 3. SEARCH 4. DELETE 5. EXIT
1. Create will allow you to create an entry to input First Name, Last Name, Gender, Address 1, Address 2, Apt, City, State, Country, Phone Type, and Phone Number
2. Edit allows the user to edit an entry previously made. You can choose from Contact, Address, or Phone and this will allow the user to see the entries to edit from
3. Search is a function that allows you to enter First Name, Last Name, and Gender and will display the Address and Phone information if the person is found
4. Delete will remove an entry from the list of contacts that are listed. The list will also include Address and Phone to verify that this is the exact person you'd like to remove.
5. Exit will end and close the application.

Create will create 3  csv files: contact.csv, address.csv, and phone.csv to store data within them.
Edit and Delete creates a temporary file called temp.csv to store the modified data and then rewrite it into either of the 3 original files.

There are no restrictions on entering information into any of the fields just yet, but will be working on it in the near future.
If there are any questions or found a bug, please email me at: shareonthelove@gmail.com
