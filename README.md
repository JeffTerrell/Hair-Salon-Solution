# Eau Claire's Salon Stylist Portal
A website that allows users to enter stylists and associated clients.

#### By Jeff Terrell

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)

## Technologies Used
* C#
* ASP.Net.Core
* .Net5
* HTML
* CSS
* Bootstrap
* Entity Framework Core
* MySql
* LINQ

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)

## Description

A web application that allows a user to create stylists and add their corresponding clients. This information is saved so that a user can access a specific stylist and view all of that stylist's clients. The user has the ability to edit and delete both stylists and clients.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)

## Setup/Installation Requirements
* If needed, download and install .NET 5 here: https://dotnet.microsoft.com/en-us/download/dotnet/5.0
* From a terminal, navigate to a directory of your choosing and use the "Git clone" command to copy the repository from this address (https://github.com/JeffTerrell/Hair-Salon-Solution).
Navigate to the sub directory "HairSalon" of the cloned main directory on your local machine.
* From the same directory "HairSalon", enter the following commands individually:
  - _dotnet add package Microsoft.EntityFrameworkCore -v 5.0.0_ 
  - _dotnet add package Pomelo.EntityFrameworkCore.MySql -v 5.0.0-alpha.2_
  - _dotnet add package Microsoft.EntityFrameworkCore.Proxies -v 5.0.0_	
* From the same directory "HairSalon", create a new file called .appsettings.json.		
* Open this file with a code editor and add the following:

  ```
  {
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=[data_base_name];uid=root;pwd=[password];"
    }
  }
  ```
* Delete the [] from database and pwd and include correct database name and password.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)


## Database Setup/Installation Requirments 

After completing the Setup/Installation requirements these next steps will show how to open the database dump file(jeff_terrell) in MySQL Workbench:
* Open MySQL Workbench and start/create a local instance with localhost:3306.
* From the left pane Navigator menu click the "Administration" tab and click the "Data Import/Restore" link. 
* From the "Import from disk" tab select the radio button "Import from Self-Contained File" and navigate to the root "HairSalon.Solution" directory and choose the "jeff_terrell.sql" database file. Next, click the "New..." button next to "Default Target Schema" and enter a new name for the database.
* Select the "Import Progress" tab and click the "Start Import" button in the bottom right corner.
* To view the imported database, click the "Schemas" tab from the Navigator Menu, right click in the pane and select "Refresh All".


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)


## Run the Application 
  * From a terminal, navigate to the sub directory "HairSalon".
  * Enter the following command, "dotnet restore" to create necessary folders and files.
  * Next enter the following command, "dotnet run". This will launch the application in your terminal. Enter "Ctrl c" to exit the application at any point.
  * To access the application, load a web browser and in the URL bar insert the specific URL(s) listed in your terminal (ex: Now listening on: http://localhost:5000).

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)

## Known Bugs
* None

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)


## License

[MIT](https://opensource.org/licenses/MIT)

Please contact Jeff Terrell via email with any issues, questions, or ideas.

Copyright (c) 2021 Jeff Terrell