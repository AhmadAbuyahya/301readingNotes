# Database normalization
* Database normalization is a process used to organize a database into tables and columns. The idea is that a table should be about a specific topic and that only those columns
which support that topic are included.

## Example:
### a spreadsheet containing information about sales people and customers serves several purposes:
* Identify sales people in your organization
* List all customers your company calls upon to sell product
* Identify which sales people call on specific customers

* By limiting a table to one purpose, you reduce the number of duplicate data that is contained within your database, which helps eliminate some issues stemming from database
modifications. To assist in achieving these objectives, some rules for database table organization have been developed. The stages of organization are called normal forms;
there are three normal forms most databases adhere to using. As tables satisfy each successive normalization form, they become less prone to database modification anomalies 
and more focused toward a sole purpose or topic. Before we move on, be sure you understand the definition of a database table.

## easons for Normalization
* There are three main reasons to normalize a database. The first is to minimize duplicate data, the second is to minimize or avoid data modification issues, 
and the third is to simplify queries. 
