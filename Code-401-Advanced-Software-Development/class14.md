# DB Normalization

![Image](https://cdn.mindmajix.com/blog/images/normalization-and-t-sql-in-sql-server-280120.png)


> - Database normalization is a process used to organize a database into tables and columns. The main idea with this is that a table should be about a specific topic and only supporting topics included

## Reasons for Database Normalization
> -  There are three main reasons to normalize a database. The first is to minimize duplicate data, the second is to minimize or avoid data modification issues, and the third is to simplify queries.

## Insert Anomaly

> - There are facts we cannot record until we know information for the entire row. so in order to create the record, we need provide a primary key.

## Deletion Anomaly

> - Deletion of a row causes removal of more than one set of facts.

## Search and Sort Issues
> - You can eliminate or reduce the issues of sorting and searching anomalies by separating the data into different tables. This puts the data into tables serving a single purpose.

> - The process to redesign the table is database normalization.
