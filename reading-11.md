## NoSQL vs SQL

## I think it depends

## Thats right there are-

## I mean if the first movie can stand on its own does it need a sequel

## Why are you like this?

# NoSQL vs SQL
- [SQL vs NoSQL](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

|SQL|NoSQL|
| --- | --- |
| Realtional Databases(RDBMS) | non-relational or distributed database |
| table based | document base, key-value pairs. graph databases, or wide-column stores |
| standard predefined schema | dynamic schema |
| Vertically Scalable | Horizontally scalabe |
| scale by increasing power of hardware | scale by increasing amount of servers |
| SQL(structured query language) | UnQL(unstructred query language) |
| use the same structure to query for all SQL | use different query structure for every DB |
| works bettter for complex queries | does not have a standard interface making it harder to make a more complex query |
| usually non-hierarchical data | better with hierachical |
| vendor support | community support |
| open vs closed | ways of storing data |

1. What kind of data is a good fit for an SQL database?
- Non-hierarchical is a better fit for a SQL database.

2. Give a real world example.
- Like the table above. All data is identified by the column it is in. There is no deeper experience.

3. What kind of data is a good fit a NoSQL database?
- key-value pairs but other forms of storing data that is not a table.

4. Give a real world example.
- The way we were storing data in the cache with a key and an associated object

5. Which type of database is best for hierarchical data storage?
- NoSQL is the best for hierarchiacal storage.

6. Which type of database is best for scalability?
- Depends on the goals and available resources. If you just want to add entries to your set up table and have access to stronger hardware than SQL is the better option, but if you are try to add other hierarchical data and have access to lots of servers then NoSQL.
- SQL does allow for more complex queries is something you should keep in mind 

- [Sql vs NoSql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)
1. What does SQL stand for?
-standard query langauge

2. What is a realational database?
- all of the data is identified by realation to other tables

3. What type of structure does a relational database work with?
- tables 

4. What is a ‘schema’?
- specified fields that all data entries follows this structure

5. What is a NoSQL database?
- Non Standard query language

6. How does it work?
- key: value pairs

7. What is inside of a Mongo database?
- collections
  - documetns

8. Which is more flexible - SQL or MongoDB? and why.
- NoSQL is more flexible because you can have data that is in any form not to a strict schema

9. What is the disadvantage of a NoSQL database?
- Duplicate data requires all points to be rewritten

[Return Home](README.md)