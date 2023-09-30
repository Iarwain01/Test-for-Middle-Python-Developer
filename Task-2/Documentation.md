### SQLite (SQL Database) Structure:

Here I use SQLite Database as example to complete my task, I created simple relational database with a single table called "users." This table has the following columns:

1. id (INTEGER PRIMARY KEY AUTOINCREMENT): This column serves as the primary key for uniquely identifying each user record. It is set to auto-increment, ensuring that each new user record gets a unique ID automatically.

2. name (TEXT): This column stores the user's name as text.

3. email (TEXT): This column stores the user's email address as text.

### Reasons for the Structure:

Here are the reasons of why I use SQLite

1. Reliability :  SQLite not a standalone app. rather, it is a library that software developers embed in their apps. 

1. Simplicity: The SQLite database structure is straightforward, making it easy to understand and work with, especially for small-scale applications or prototypes.

2. Relational Data: We chose a relational structure because the data we are dealing with (user information) has a well-defined schema, and relationships between tables are not required in this case.

3. Efficiency: SQLite is suitable for local or small-scale applications, and its relational structure provides efficient data retrieval and manipulation capabilities.
