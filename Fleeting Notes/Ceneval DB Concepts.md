# Ceneval DB Concepts
Created: 2021-10-10 16:38

- DBMS do NOT always support Data Definition Language (DDL)
- Concurrency control allows the processing of several simultaneous operation in the DB without interference
- Logical independence is the capability to modify a conceptual schema without altering application programs or altering external schema
- Physical independence is the ability to modify a schema without altering the conceptual schema
- The number of attributes in a relationship is known as the "degree of the relationship"
- A candidate key is the minimum set of attributes needed to identify a unique key in a tuple
- All primary key values must be non null values
- The relational model uses a declarative Data Manipulation Language (DML)
- The graph model and hierarchy model use a procedural Data Manipulation Language (DML)
- the hierarchy model is limited in its data modeling capabilities
- if an entity has a many-to-many relationship with another entity, a new table is formed
- a multi-variable attribute creates a new table with a foreign key to the original table 
- if a -> x,y,z it is possible that y -> z
- (x,y) ->z is not equivalent to x->z, y->z
- z -> x,y is equivalent to z->x,z->y
- Object Oriented Database System Manifesto indicates that simple and  multiple inheritance support, OID manipulation, object encapsulation must be included
-   ODMG: data model, object definition language, query language
### Normal forms
1. has primary key, no repeating groups in individual tables, create table for each set of related data
2. separate tables for sets of values that apply to multiple records, and their primary keys
3. eliminate fields that do not depend on the key
## Reference
1. 