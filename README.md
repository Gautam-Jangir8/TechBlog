--> About:
The TechBlog project is a web application designed to facilitate note-taking and blogging for users interested in technology topics. It is developed using a variety of technologies, including HTML, CSS, JavaScript, Bootstrap for the frontend, Core Java for backend logic, Servlets and JSP for dynamic web pages, Hibernate for database interaction, and OOPs concepts for modular and structured code.


--> Features:
1) User Authentication: The project includes user authentication features, allowing users to sign up for an account and log in securely. User credentials are stored securely in the database, and password hashing techniques are used to ensure data security.
2) Note Taking: Logged-in users can create, edit, and delete their notes on various technology topics. The notes are stored in the database and associated with the user's account.
3) Dynamic Web Pages: Servlets and JSP are used to generate dynamic web pages that display user-specific content, such as the user's notes and account information.
4) Responsive Design: Bootstrap framework is utilized to ensure that the web application is responsive and mobile-friendly, providing a seamless user experience across devices of all sizes.
5) Database Interaction: Hibernate, an ORM (Object-Relational Mapping) framework, is employed to interact with the underlying database. It abstracts away the complexities of SQL queries and provides a more object-oriented approach to database operations.
6) Logging: The project includes logging features to record important events, errors, and user activities. Logging helps in troubleshooting issues and monitoring application behavior.


--> Architecture: The TechBlog project follows a typical Model-View-Controller (MVC) architecture:
1) Model: The business logic and data access code are encapsulated in Java classes using OOPs principles. Hibernate ORM is used to map Java objects to database tables and perform CRUD (Create, Read, Update, Delete) operations.
2) View: The frontend UI is implemented using HTML, CSS, JavaScript, and Bootstrap. JSP files are used to generate dynamic web pages that display user-specific content.
3) Controller: Servlets act as controllers that handle HTTP requests, process user input, interact with the model layer (Java classes), and generate appropriate responses using JSP files.
