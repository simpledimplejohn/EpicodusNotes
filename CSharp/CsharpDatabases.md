NEVER DELETE
information_schema
mysql
performace_schema


NOTES
Databases
made up of csv tables
Tables are made up of rows and columns
PRIMARY KEY -- when a row is added the first column is the id which is the primary key.

Class singular and uppercase
tables are plural and lowercase

COMMAND LINE COMMANDS:
To quit
`exit`
`quit` quits
To log in
`mysql -u root -p`
or 
`mysql -uroot -pepicodus`
EF core
How to export databases


CREATE DATBASE test_database;'
CREATE SCHEMA `name_of_database` ;
SHOW DATABASES;
USE test_database;
SELECT DATABASE();
CREATE TABLE contacts (name VARCHAR (255), age INT, birthday DATETIME);
 VARCHAR is varying number of characters SQL string
DESCRIBE contacts
SHOW TABLES;
DROP TABLE table_name;

WORKBENCH:
Auto-increment keeps the number increasing

MySqlConnector connects our database to our C# objects

SQL COMMAND FORMAT
SELECT <column> FROM <tables> WHERE <condition> AND <condition> ORDER BY <column> <asc or desc>;
 SELECT description FROM items;

SQL Designer
Relationships between tables
 Foreign keys


Tuesday
ORM object relational mapping how we access database info
 Turn databases into objects so C can see them

Entity Framework, how we do this

HTML helper methods: forms

Wednesday
Update with EF Core
viewBag

Thursday
ACID Databases
Anatomical
Consistency
Isolation
Durability

Friday Project:
Export and SQL file and include on top level of repository same level as readme
Erik Ergens Csharp teacher

migration -updating database changes
Make sure your .csproj file has updated <ItemGroup> packageReferences 
Make sure there is a:
DesignTimeDbContextFactory.cs file in Models

> dotnet ef migrations add Initial
creates a migration named Initial
> dotnet ef database update

//add entity 
dotnet add package Microsoft.EntityFrameworkCore -v 5.0.0
dotnet add package Pomelo.EntityFrameworkCore.MySql -v 5.0.0-alpha.2 
// for migration setuo 
dotnet add package Microsoft.EntityFrameworkCore.Design -v 5.0.0

