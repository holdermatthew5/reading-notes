- Database normalization - process used to organize a database into tables and columns.
- limiting tables to single purpose helps elimniate duplicate data which eliminates some issues with modification.
> The progression from unruly to optimixed passes through several normal forms. - Kris Wenzel
- reasons for normalizing a database:
  - minimize duplicate data.
  - minimize/avoid modification issues.
  - simplify queries.
- first normal form (1NF) - The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.
- second normal form (2NF) - in 1NF and all columns rely on tables primary key.
- third normal form (3NF) - in 2NF and all columns are not transitively dependent on the primary key.