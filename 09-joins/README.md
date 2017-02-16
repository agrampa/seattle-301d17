# Code 301, Class 9: ***SQL Joins & Relations***

## Today's Plan

Song for today: ["Table for Two"](https://www.youtube.com/playlist?list=PLVngfM2hsbi97X7yB1bCwl5qSoC23l9zo) by Loretta Lynn & Vince Gill

Announcements
- Lunch & Learn on Friday: James Mategko (software architect for CBRE)
- Tomorrow at 1:00 we'll have a visit from Admissions to take questions on you next steps
- We'll be offering a 401 Q&A Info Session with the 401 instructors on Tuesday 2/21 at 4:00pm in the event space. Come meet the 401 instructors and ask them any questions you might have about those courses!

Code Review

`10 minute break`

- [Slides](09-sql-joins-relations.pdf)

[Reference document on joins](joins.md)

##### Normalization & Joins

- Database Relationships
- 1:1 Rel
- 1:Many / Many:1 Rel
- Many:Many Rel
	- Include Junction Tables
- Self-referencing Rel

##### Database Normalization

- Remove duplicate data.
- Minimize database redesign.
- Minimize modification anomalies.

##### Joins

- Understanding Primary and Foreign Keys
	- Discuss how these keys are related and can be used for database normalization

- Inner Join
	- Discuss syntax
	- Discuss concepts

- High Level Overview of Other Join types* *

`10 minute break`

##### Demo

- How to normalize a database.
- How to use foreign keys.
- How to perform an inner join.

##### Lab Prep

- Be sure to follow the instructions in the lab README to get today's set up. You need to do a DROP TABLE on the articles table from yesterday's lab to prevent problems. Today we have two tables, one of which, 'articles', is the same name as the table we used yesterday.

###Class 09 Readings (to be completed before class)

- [SQLBolt (Lessons 6-7) (Essential)](http://sqlbolt.com/lesson/select_queries_with_joins)
- [A Primer on SQL (Chapter 11) (Reference)](https://leanpub.com/aprimeronsql/read#leanpub-auto-understanding-joins)
- [Visual Guide to SQL Joins](http://www.codeproject.com/Articles/33052/Visual-Representation-of-SQL-Joins)

### Useful resources.

 - [SQLBolt](http://sqlbolt.com/) -- Interactive SQL Tutorial
 - [SQL Cheat Sheet](http://www.cheat-sheets.org/sites/sql.su/)
 - [Query String Primer](https://en.wikipedia.org/wiki/Query_string)

## Learning Objectives

- Understand how objects in a database can be interrelated with foreign keys
- Have familiarity with queries using SQL that select data from across multiple tables
- Have familiarity with different relationships in database tables
