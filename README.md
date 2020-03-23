# SQLite
My works related to SQLite, a C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine.

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [SQLite developers.](#developers)
4. [GitHub notes.](#github)
5. [GitHub repository calculation.](#calculation)

<a name="introduction"></a>
## 1. Introduction.
<img src="sqlite.png" height="110"> 
SQLite is a C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine. SQLite is the most used database engine in the world. SQLite is built into all mobile phones and most computers and comes bundled inside countless other applications that people use every day.
<br /><br />
The SQLite file format is stable, cross-platform, and backwards compatible and the developers pledge to keep it that way through at least the year 2050. SQLite database files are commonly used as containers to transfer rich content between systems and as a long-term archival format for data. There are over 1 trillion (1e12) SQLite databases in active use.
<br /><br />
SQLite is ACID-compliant and implements most of the SQL standard, generally following PostgreSQL syntax. However, SQLite uses a dynamically and weakly typed SQL syntax that does not guarantee the domain integrity. This means that one can, for example, insert a string into a column defined as an integer. SQLite will attempt to convert data between formats where appropriate, the string "123" into an integer in this case, but does not guarantee such conversions, and will store the data as-is if such a conversion is not possible.
<br /><br />
SQLite is a popular choice as embedded database software for local/client storage in application software such as web browsers. It is arguably the most widely deployed database engine, as it is used today by several widespread browsers, operating systems, and embedded systems (such as mobile phones), among others. SQLite has bindings to many programming languages.
<br /><br />
D. Richard Hipp designed SQLite in the spring of 2000 while working for General Dynamics on contract with the United States Navy. Hipp was designing software used for a damage-control system aboard guided missile destroyers, which originally used HP-UX with an IBM Informix database back-end. SQLite began as a Tcl extension.
<br /><br />
The design goals of SQLite were to allow the program to be operated without installing a database management system or requiring a database administrator. Hipp based the syntax and semantics on those of PostgreSQL 6.5. In August 2000, version 1.0 of SQLite was released, with storage based on gdbm (GNU Database Manager). SQLite 2.0 replaced gdbm with a custom B-tree implementation, adding transaction capability. SQLite 3.0, partially funded by America Online, added internationalization, manifest typing, and other major improvements. In 2011 Hipp announced his plans to add a NoSQL interface (managing documents expressed in JSON) to SQLite databases and to develop UnQLite, an embeddable document-oriented database.

<a name="references"></a>
## 2. Official references websites. 
SQLite official website : https://sqlite.org <br />
SQLite official download page : https://sqlite.org/download.html <br />
DB Browser for SQLite : https://sqlitebrowser.org <br />
DB Browser for SQLite download page : https://sqlitebrowser.org/dl/ <br />

**_SQLite questions and answers_** <br />
Stack Overflow questions and answers website : https://stackoverflow.com <br />

**_SQLite questions and answers by Stack Overflow_** <br />
Differences between SQLite database in Android and IOS by Stack Overflow : https://stackoverflow.com/questions/14792671/differences-between-sqlite-database-in-android-and-ios <br />

**_SQLite documentation by sqlite.org_** <br />
SQL As Understood By SQLite by sqlite.org : https://www.sqlite.org/lang_keywords.html <br />
Datatypes In SQLite Version 3 by sqlite.org : https://www.sqlite.org/datatype3.html <br />

**_SQLite related articles_** <br />
What is an Operator in SQLite? by tutorialpoint : https://www.tutorialspoint.com/sqlite/sqlite_operators.htm <br />

<a name="developers"></a>
## 4. SQLite developers.
SQLite was created by Dwayne Richard Hipp : https://github.com/dhh, https://twitter.com/DRichardHipp <br />
Awais Mirza : https://twitter.com/AwaisMirza01 <br />
 
<a name="github"></a>
## 6. GitHub notes.
Clone the current GitHub remote repository contents into local machine.
```
$ git clone https://github.com/syakirharis25/SQLite.git
$ cd SQLite/
$ git remote -v
$ git status
```

<a name="calculation"></a>
## 7. GitHub repository calculation.
```
draft
```
Refer to : https://github.com/syakirharis25/cloc
