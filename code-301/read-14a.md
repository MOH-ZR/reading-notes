# Database Normalization
database normalization is the process of structuring a database, usually a relational database, in accordance with a series of so-called *normal forms* in order to reduce data redundancy and improve *data integrity*.  

There are a few rules for database normalization. Each rule is called a "normal form." If the first rule is observed, the database is said to be in "first normal form." If the first three rules are observed, the database is considered to be in "third normal form." Although other levels of normalization are possible, third normal form is considered the highest level necessary for most applications.

## First normal form (1NF)
* Eliminate repeating groups in individual tables.
* Create a separate table for each set of related data.
* Identify each set of related data with a primary key.
## Second normal form (2NF)
* Create separate tables for sets of values that apply to multiple records.
* Relate these tables with a foreign key.
## Third normal form (3NF)
* Eliminate fields that do not depend on the key