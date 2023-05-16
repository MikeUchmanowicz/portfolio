# My Portfolio / Bigger Projects

Portfolio Repository. Provides links to other repositories.

___

- [Neat is Neat Senior Project](https://github.com/MikeUchmanowicz/Neat-is-Neat-Senior-Project/) - *Python, Pygame, Django, NEAT AI, MySQL*  

  Currently designing and creating a simple "endless scroller" game within python with an implemented evolutionary Artificial Intelligence in order to play the game. The project's purpose is to explore the concepts of NEAT. The game will upload AI info/results to a database post-game which an included full-stack django webapp will retrieve from an SQL database and display both in a list and in a graph. The django webapp also features user registration and authentication. The django webapp has been containerized and is hosted using AWS' Elastic Container Service within an EC2 instance. The MySQL database is hosted within AWS' RDS


- [Inventory Store CRUD Springboot](https://github.com/MikeUchmanowicz/Inventory-Store-CRUD-Springboot/) - *Java, Springboot, Thymeleaf, JavaScript, MySQL*  

  Designed and created (collaboratory team of 2) a crud webapp that supports polymorphism and different items. Users are able to register, login, view their own inventory, view the "store" inventory, purchase items from the "store", and add each other as friends. An Admin user can create, edit, and delete products within the "store". An SQL database stores products, users, and friendships. Utilizes: IoC, SoC, & N-Layer architecture. Application was later containerized using docker and an image was uploaded to AWS's ECS. Production level logging, tracing, ptime monitoring, and a pipeline built in Github Actions are used. The MySQL database is hosted within AWS' RDS

- [Items API / Static HTML Webapp](https://github.com/MikeUchmanowicz/itemsAPIpythonStatic/) - *Python, FastAPI , Static Html + JavaScript, MongoDB* 

  Created an Items API back end written in Python (FastAPI) which allows for the creating, reading, updating, and deleting of items. Items are stored within a Mongo DB. The front end has been built using HTML and javascript. The application is served from AWS Cloud9.

- [Contacts API / Full Stack CRUD Webapp](https://github.com/MikeUchmanowicz/ContactsAPI) - *JS Express, JS Angular, JS React, MySQL*  

  Created a Contacts API back end using express which allows for the creating, reading, updating, and deleting of contacts and notes associated with them. Contacts and notes are stored in a MySQL database. Two front ends using both angular and react were then added to the application which provides users with a seamless UI.


- [Springboot Cloud "Lift n' Shift w DevOps"](https://github.com/MikeUchmanowicz/SpringBootLiftNShiftDevOps) - *Springboot stack, AWS, Google Cloud, Azure, Heroku, MySQL*  

  I created a springboot application and hosted it within several clouds: AWS, Google Cloud, Azure, and Heroku. The cloud hosted springboot Application features a home page and a "pseudo-login", allowing for any input which will take the user to an orders page. The user can see all orders which are retrieved from a MySQL database hosted by the same cloud host. Production level logging, tracing, uptime monitoring and a pipeline built in AWS codePipeline are used.


- Inventory Client & Admin Services Console App - *Java*

  REPO CURRENTLY UNDER CONSTRUCTION   
  Designed and Created a multithreaded console app that supports polymorphism and websockets. The app allows for a client connection to an inventory store in which the     client can view, sort, and purchase items. These items are different types. An admin can connect and update the inventory via a json string or view the inventory returned as json. The admin and client connections can be run asynchronously.   


- Minesweeper Full-Stack Webapp - *C#, ASP.NET, JavaScript*

  REPO CURRENTLY UNDER CONSTRUCTION   
  Created and Deployed (as a collaboratory team of 4) a full-stack minesweeper webapp to Azure. Features include: registration, logging in, a playable minesweeper game,   saving of progress in game, and the playing of saved games. An SQL database is implemented to store users and saved games.
