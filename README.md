# Programming Foundations: Databases
While the [_Programming Foundations: Databases_][1] course on LinkedIn Learning is intended as an overview of the ideas behind relational databases, and not a hands-on exploration of using a database, we’ve heard from many of our learners that they would like access to the database used in the course for practice.

This repository includes files you can use to practice. The files are:
* tables of data used to populate the Restaurant database (contents of the `csvs` folder)
* two versions of the Restaurant database for various software tools (`restaurant.sql` and `restaurant_sqlite.db`)
* a listing of the commands that I used to work with the database (`queries.md`)

**You do not need to use these files to follow along with the course.**

Chapter 5 in the [_Programming Foundations: Databases_][2] course is intended as a preview of what you can do with a relational database after learning SQL. 

For an introduction to the SQL language, see the course [_Learning SQL Programming_][3] on LinkedIn Learning.

## Software Used
In the course, I demonstrated interacting with the database using [HeidiSQL][4], connected to a [MariaDB][5] server. Because this can take some effort to set up, you may consider using [DB Browser for SQLite][6] on a local system instead. I’ve provided the database here in two formats:
* `restaurant.sql` can be imported into tools like *MySQL*, *SQL Server*, and other compatible database management systems.
* `restaurant_sqlite.db` can be opened in *DB Browser for SQLite*.

For practice purposes, both options work in a similar way.

### An example showing HeidiSQL
![][image-1]

### An example showing DB Browser for SQLite
![][image-2]

[1]:	https://www.linkedin.com/learning/programming-foundations-databases-2
[2]:	https://www.linkedin.com/learning/programming-foundations-databases-2
[3]:	https://www.linkedin.com/learning/learning-sql-programming
[4]:	https://www.heidisql.com/
[5]:	https://mariadb.com/
[6]:	https://sqlitebrowser.org/

[image-1]:	imgs/heidisql.png
[image-2]:	imgs/dbbrowser.png
