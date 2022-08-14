# Factory

#### By: Ryan Broadsword

#### Application that allows the user to add/edit/view a factory with Engineers and Machines. 

## Technologies Used

* C#
* .Net 5
* REPL
* CSS
* HTML
* SQL
* MySQL Workbench 
* Entity


## Description 

Dr. Sillystringz's Factory
You've been contracted by the factory of the famous Dr. Sillystringz to build an application to keep track of their machine repairs. You are to build an MVC web application to manage their engineers, and the machines they are licensed to fix. The factory manager should be able to add a list of engineers, a list of machines, and specify which engineers are licensed to repair which machines. There should be a many-to-many relationship between Engineers and Machines. An engineer can be licensed to repair (belong to) many machines (such as the Dreamweaver, the Bubblewrappinator, and the Laughbox) and a machine can have many engineers licensed to repair it.

User Stories
* As the factory manager, I need to be able to see a list of all engineers, and I need to be able to see a list of all machines.
* As the factory manager, I need to be able to select a engineer, see their details, and see a list of all machines that engineer is licensed to repair. I also need to be able to select a machine, see its details, and see a list of all engineers licensed to repair it.
* As the factory manager, I need to add new engineers to our system when they are hired. I also need to add new machines to our system when they are installed.
* As the factory manager, I should be able to add new machines even if no engineers are employed. I should also be able to add new engineers even if no machines are installed
* As the factory manager, I need to be able to add or remove machines that a specific engineer is licensed to repair. I also need to be able to modify this relationship from the other side, and add or remove engineers from a specific machine.
* I should be able to navigate to a splash page that lists all engineers and machines. Users should be able to click on an individual engineer or machine to see all the engineers/machines that belong to it.

## Setup/Installation Requirements

### Clone project
* clone repository
* open in vs code
* open terminal
* in terminal run "dotnet build" to make sure everything is up to date.
* in terminal run "dotnet test" to see test results for functionality. 
* in termianl run "dotnet run" to run the program and follow the prompts given in the console. 
* select localhost:5000/ to launch application in browser.

### Create your database schema and tables! 
* in terminal run "dotnet ef migrations add Initial"
* in terminal run "dotnet ef database update"
* check SQL Workbench and refresh schemas to check that factory db was successful. 

### Create appsettings.json
* navigate to project folder in terminal "cd Factory"
* In termianl add "touch appsettings.json" 
* in the appsettings.json file add "{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=hair_salon;uid=root;pwd=[YOUR PASSWORD HERE];"
  }
}
* add your password for SQL where it says pwd=[YOUR PASSWORD HERE] 


## Known Bugs

* Views pages WIP
* Styles not working! 


## License

Not currently licensed 

Copyright (c) August 14th 2022, by Ryan Broadsword rbroadsword@gmail.com 