A database is a program that is built around soring data...

DBMS enables the definition, creation and maintenance of a database. Provides controlled access.

# CDM
* Represent the data requirements of an organisation
* independent of a database software used

# ERD
* represents relationship betwee entities using ERD
* degree of relationship. how are they related?:
  * `1:1`
  * `1:many`/`many:1`
  * `many:many`

# Normal forms
* first normal form: a table has a primary key, atomic (smallest possible) values
* second normal form: table must be in 1NF, has no partial key dependencies
* third normal form: must be in 2NF, contains no non-key dependancies


# Definitions
* Primary Key: unique identifier of a record in a database
* composite key: combination of attributes used to create unique identifier of a record in a table
* foreign key: link field, field in the table where the primary key links to the foreign key
* referential integrity: checks to ensure tha a value used as foreign key is a primary key in another tbale
* normalisation: given a set of data, removing the redundancies
