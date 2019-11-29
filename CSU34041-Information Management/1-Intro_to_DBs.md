# Info Man Notes 
##  Introduction to Databases

### What is a database?
Data is any info you want to store and refer to again. Can be in many forms
 Database is an organised collection of information or Data.
 More formally: " A database is a persistent collection of related data supoorting several different applications within an organisation. 
 
 Data is organised to...

 * Model aspects of reality 
 * to suuport processes that require this data
 *  make data useful

### Metadata
This is data that adds context to data (i.e. data about data for example data type, element size)
### Database Management Systems
DBMS simplify storage of and access to data, and support:

* defintion
* manipulation
* querying

DBMS can manage single or set of DBs and provide.

**Efficient**, **reliable**, and **secure** management of large amounts of persistent data.
**Data Definition Language**: Language for defining DB

**Data Manipulation Language**: language for <u>storing</u>, <u>retrieving</u>, and <u>updating</u> data in DB.
Well known examples include oracle, IBM db2 (proprietary), mySQL, sqlite, postgresql (open source).

### Database Systems
![Image of database system](https://www.w3schools.in/wp-content/uploads/2016/08/Database-System-Environment.png)

DBS consist of DB and DBMS and application programs. In DB associated metadata and applciation data are stored separately.

### Why use a database?
DB approach over file systems aims to eliminate redundancy(data dupplicatoin: wasteful of storage, inefficient, leads to inconsistencies).
Data from all applications is integrated and stored oncev in DB, and all applications have same physical copy of the data.

### Data Independence 

* File based systems **data dependent** 
* DBMS support **logical data independence**
  * allows view to change and data added without changing underlying organisation
* DBMS support **physical data independence**
  * as insulate the way data is viewed by apps/users from the way it is physically stored

### Data Integrity 
**consistency** and **accuracy** of data in DB. Data redundancy threatens Data integrity.
* Dbs model real world with many rules eg. 1 student ID per person
* DBMS express these rules with "integrity constraints"
* Validation of data being entered another aspect of data integirty
* "concurrency" control needed for simultaneous update thret to integrity 

### Advantages of Databases
* search and retrieval capabilities (filtering according to specific needs)
* Reduced data redundancy (ease of updte)
* Increased data integrity
* Indepence from applications, concurrent access
* improved data security
* reduced costs for data entry, storage and retrieval

### Disadvantages of Databases
* training required
* complex to design and time consuming
* hardware,software and training cost
* loss of autonomy brought by centralised data control
* inflexibility due to complexity

### Database Languages
these are programming languages used to
    * define DB - its entities and relationships between them
    * maniplualate its content - insert new, update, delete
    * conduct queries- request info based on defined criteria
  * **Structured Query Language (SQL)** most commonly used for RDBs and supported by all RDBMSs
### SQL
There is 4 sets of commands
* Data definition language
* Data manipulation language - modify stored data, not schema or db objects
* Data query language 
* data control language

### Transactions
Groups actions atomically - all or nothing
Guarantees to move DB content from 1 consistent state to another, and ensures DB is recoverable in case of failure

### Users
* DBMS implementer
* DB designer
* DB application developer
* DB administrator
