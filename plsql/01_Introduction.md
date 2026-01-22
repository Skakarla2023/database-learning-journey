<h2 center="center"><b> Introduction to PL/SQL</b></h2>

- SQL is used to store, retrieve, update, and delete data from a database.
- PL/SQL is used to write programs inside the database to control how SQL runs using conditions, loops, and error handling.
- Following is the basic structure of pl/sql block:

```plsql
DECLARE 
   <declarations section> 
BEGIN 
   <executable command(s)>
EXCEPTION 
   <exception handling> 
END;
```


### Features of PL/SQL:

It Offers :
- Error checking.
- Numerous data types.
- Object oriented programming.
- it supports structured programming through procedures and functions.
- A variety of programming structures.


### PL/SQL Identifiers

- PL/SQL identifiers are constants, variables, exceptions, procedures, cursors, and reserved words. The identifiers consist of a letter optionally followed by more letters, numerals, dollar signs, underscores, and number signs and should not exceed 30 characters.
- By default, identifiers are not case-sensitive. So you can use integer or INTEGER to represent a numeric value. You cannot use a reserved keyword as an identifier.

### PL/SQL Comments

- The PL/SQL single line commands start with --.
- Multiline comments are enclosed by /* and */.

```plsql
DECLARE
  -- variable declaration
BEGIN
  /*
  PL/SQL executable commands
  */
END;
/
```
