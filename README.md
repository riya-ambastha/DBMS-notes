what is database ?
The database is a collection of inter-related data which is used to retrieve, insert and delete the data efficiently.  
It is also used to organize the data in the form of a table, schema, views, and reports, etc. 
example: The college Database organizes the data about the admin, staff, students and faculty etc.

what is Database Management System ?
Database management system is a software which is used to manage the database. For example: MySQL, Oracle, etc are a very popular commercial database which is used in different applications.
DBMS provides an interface to perform various operations like database creation, storing data in it, updating data, creating a table in the database and a lot more.
It provides protection and security to the database. In the case of multiple users, it also maintains data consistency.


DBMS allows users the following tasks:

1. Data Definition: It is used for creation, modification, and removal of definition that defines the organization of data in the database.

2. Data Updation: It is used for the insertion, modification, and deletion of the actual data in the database.

3. Data Retrieval: It is used to retrieve the data from the database which can be used by applications for various purposes.

4. User Administration: It is used for registering and monitoring users, maintain data integrity, enforcing data security, dealing with concurrency control, monitoring performance and recovering information corrupted by unexpected failure.

Characteristics of DBMS
1. It uses a digital repository established on a server to store and manage the information.
2. It can provide a clear and logical view of the process that manipulates data.
3. DBMS contains automatic backup and recovery procedures.
4. It contains ACID properties which maintain data in a healthy state in case of failure.
5. It can reduce the complex relationship between data.
6. It is used to support manipulation and processing of data.
7. It is used to provide security of data.
8. It can view the database from different viewpoints according to the requirements of the user.

9. Advantages of DBMS
1. Controls database redundancy: It can control data redundancy because it stores all the data in one single database file and that recorded data is placed in the database.
2. Data sharing: In DBMS, the authorized users of an organization can share the data among multiple users.
3. Easily Maintenance: It can be easily maintainable due to the centralized nature of the database system.
4. Reduce time: It reduces development time and maintenance need.
5. Backup: It provides backup and recovery subsystems which create automatic backup of data from hardware and software failures and restores the data if required.
6. multiple user interface: It provides different types of user interfaces like graphical user interfaces, application program interfaces

7. Disadvantages of DBMS
1. Cost of Hardware and Software: It requires a high speed of data processor and large memory size to run DBMS software.
2. Size: It occupies a large space of disks and large memory to run them efficiently.
3. Complexity: Database system creates additional complexity and requirements.
4. Higher impact of failure: Failure is highly impacted the database because in most of the organization, all the data stored in a single database and if the database is damaged due to electric failure or database corruption then the data may be lost forever.

DBMS Architecture :
The DBMS design depends upon its architecture. The basic client/server architecture is used to deal with a large number of PCs, web servers, database servers and other components that are connected with networks.
The client/server architecture consists of many PCs and a workstation which are connected via the network.
DBMS architecture depends upon how users are connected to the database to get their request done.

Types of DBMS Architecture

1.  1-Tier Architecture
a) In this architecture, the database is directly available to the user. It means the user can directly sit on the DBMS and uses it.
b) Any changes done here will directly be done on the database itself. It doesn't provide a handy tool for end users.
c) The 1-Tier architecture is used for development of the local application, where programmers can directly communicate with the database for the quick response.

2. 2-Tier Architecture
a) The 2-Tier architecture is same as basic client-server. In the two-tier architecture, applications on the client end can directly communicate with the database at the server side. For this interaction, API's like: ODBC, JDBC are used.
b) The user interfaces and application programs are run on the client-side.
c) The server side is responsible to provide the functionalities like: query processing and transaction management.
d) To communicate with the DBMS, client-side application establishes a connection with the server side.

3. 3-Tier Architecture
a) The 3-Tier architecture contains another layer between the client and server. In this architecture, client can't directly communicate with the server.
b) The application on the client-end interacts with an application server which further communicates with the database system.
c) End user has no idea about the existence of the database beyond the application server. The database also has no idea about any other user beyond the application.
d) The 3-Tier architecture is used in case of large web application.

Three schema Architecture
a) The three schema architecture is also called ANSI/SPARC architecture or three-level architecture.
b) This framework is used to describe the structure of a specific database system.
c) The three schema architecture is also used to separate the user applications and physical database.
d) The three schema architecture contains three-levels. It breaks the database down into three different categories.

1. Internal Level
a) The internal level has an internal schema which describes the physical storage structure of the database.
b) The internal schema is also known as a physical schema.
c) It uses the physical data model. It is used to define that how the data will be stored in a block.
d) The physical level is used to describe complex low-level data structures in detail.

2.  Conceptual Level
   a) The conceptual schema describes the design of a database at the conceptual level. Conceptual level is also known as logical level.
b) The conceptual schema describes the structure of the whole database.
c) The conceptual level describes what data are to be stored in the database and also describes what relationship exists among those data.
d)  In the conceptual level, internal details such as an implementation of the data structure are hidden.
e) Programmers and database administrators work at this level.

3. External Level
  a)  At the external level, a database contains several schemas that sometimes called as subschema. The subschema is used to describe the different view of the database.
b) An external schema is also known as view schema.
c) Each view schema describes the database part that a particular user group is interested and hides the remaining database from that user group.
d) The view schema describes the end user interaction with database systems.

DATA MODEL
Data Model is the modeling of the data description, data semantics, and consistency constraints of the data. It provides the conceptual tools for describing the design of a database at each level of data abstraction.

TYPES OF DATA MODEL:
1) Relational Data Model: This type of model designs the data in the form of rows and columns within a table. Thus, a relational model uses tables for representing data and in-between relationships. Tables are also called relations. This model was initially described by Edgar F. Codd, in 1969. The relational data model is the widely used model which is primarily used by commercial data processing applications.
2) Entity-Relationship Data Model: An ER model is the logical representation of data as objects and relationships among them. These objects are known as entities, and relationship is an association among these entities. This model was designed by Peter Chen and published in 1976 papers. It was widely used in database designing. A set of attributes describe the entities. For example, student_name, student_id describes the 'student' entity. A set of the same type of entities is known as an 'Entity set', and the set of the same type of relationships is known as 'relationship set'.
3)  Object-based Data Model: An extension of the ER model with notions of functions, encapsulation, and object identity, as well. This model supports a rich type system that includes structured and collection types. Thus, in 1980s, various database systems following the object-oriented approach were developed. Here, the objects are nothing but the data carrying its properties.

Data model Schema and Instance:
a) The data which is stored in the database at a particular moment of time is called an instance of the database.
b) The overall design of a database is called schema.
c) A database schema is the skeleton structure of the database. It represents the logical view of the entire database.
d) A schema contains schema objects like table, foreign key, primary key, views, columns, data types, stored procedure, etc.
e) A database schema can be represented by using the visual diagram. That diagram shows the database objects and relationship with each other.
f) A database schema is designed by the database designers to help programmers whose software will interact with the database. The process of database creation is called data modeling.
g) A schema diagram can display only some aspects of a schema like the name of record type, data type, and constraints. Other aspects can't be specified through the schema diagram. For example, the given figure neither show the data type of each data item nor the relationship among various files.
Data Independence
a) Data independence can be explained using the three-schema architecture.
b) Data independence refers characteristic of being able to modify the schema at one level of the database system without altering the schema at the next higher level.

There are two types of data independence:

1. Logical Data Independence
Logical data independence refers characteristic of being able to change the conceptual schema without having to change the external schema.
Logical data independence is used to separate the external level from the conceptual view.
If we do any changes in the conceptual view of the data, then the user view of the data would not be affected.
Logical data independence occurs at the user interface level.

3. Physical Data Independence
Physical data independence can be defined as the capacity to change the internal schema without having to change the conceptual schema.
If we do any changes in the storage size of the database system server, then the Conceptual structure of the database will not be affected.
Physical data independence is used to separate conceptual levels from the internal levels.
Physical data independence occurs at the logical interface level.

Database Languages in DBMS
A DBMS has appropriate languages and interfaces to express database queries and updates.
Database languages can be used to read, store and update the data in the database.

Types of Database Languages

1. Data Definition Language (DDL)
DDL stands for Data Definition Language. It is used to define database structure or pattern.
It is used to create schema, tables, indexes, constraints, etc. in the database.
Using the DDL statements, you can create the skeleton of the database.
Data definition language is used to store the information of metadata like the number of tables and schemas, their names, indexes, columns in each table, constraints, etc.

Here are some tasks that come under DDL:
Create: It is used to create objects in the database.
Alter: It is used to alter the structure of the database.
Drop: It is used to delete objects from the database.
Truncate: It is used to remove all records from a table.
Rename: It is used to rename an object.
Comment: It is used to comment on the data dictionary.
These commands are used to update the database schema that's why they come under Data definition language.

2. Data Manipulation Language (DML)
DML stands for Data Manipulation Language. It is used for accessing and manipulating data in a database. It handles user requests.

Here are some tasks that come under DML:

Select: It is used to retrieve data from a database.
Insert: It is used to insert data into a table.
Update: It is used to update existing data within a table.
Delete: It is used to delete all records from a table.
Merge: It performs UPSERT operation, i.e., insert or update operations.
Call: It is used to call a structured query language or a Java subprogram.
Explain Plan: It has the parameter of explaining data.
Lock Table: It controls concurrency.

3. Data Control Language (DCL)
DCL stands for Data Control Language. It is used to retrieve the stored or saved data.
The DCL execution is transactional. It also has rollback parameters.
(But in Oracle database, the execution of data control language does not have the feature of rolling back.)

Here are some tasks that come under DCL:

Grant: It is used to give user access privileges to a database.
Revoke: It is used to take back permissions from the user.
There are the following operations which have the authorization of Revoke:

CONNECT, INSERT, USAGE, EXECUTE, DELETE, UPDATE and SELECT.

4. Transaction Control Language (TCL)
TCL is used to run the changes made by the DML statement. TCL can be grouped into a logical transaction.

Here are some tasks that come under TCL:

Commit: It is used to save the transaction on the database.
Rollback: It is used to restore the database to original since the last Commit.

ER (Entity Relationship) Diagram in DBMS: 

1) ER model stands for an Entity-Relationship model. It is a high-level data model. This model is used to define the data elements and relationship for a specified system.
2) It develops a conceptual design for the database. It also develops a very simple and easy to design view of data.
3) In ER modeling, the database structure is portrayed as a diagram called an entity-relationship diagram.
4) For example, Suppose we design a school database. In this database, the student will be an entity with attributes like address, name, id, age, etc. The address can be another entity with attributes like city, street name, pin code, etc and there will be a relationship between them.
5) COMPONENTS OF ER MODEL:

1. Entity:
An entity may be any object, class, person or place. In the ER diagram, an entity can be represented as rectangles.

A) WEAK ENTITY - An entity that depends on another entity called a weak entity. The weak entity doesn't contain any key attribute of its own. The weak entity is represented by a double rectangle.

2. Attribute
The attribute is used to describe the property of an entity. Eclipse is used to represent an attribute

a. Key Attribute
The key attribute is used to represent the main characteristics of an entity. It represents a primary key. The key attribute is represented by an ellipse with the text underlined.

b)composite attribute 
An attribute that composed of many other attributes is known as a composite attribute. The composite attribute is represented by an ellipse, and those ellipses are connected with an ellipse.

c. Multivalued Attribute
An attribute can have more than one value. These attributes are known as a multivalued attribute. The double oval is used to represent multivalued attribute.

d. Derived Attribute
An attribute that can be derived from other attribute is known as a derived attribute. It can be represented by a dashed ellipse.

3. Relationship
A relationship is used to describe the relation between entities. Diamond or rhombus is used to represent the relationship.

Types of relationship are as follows:

a. One-to-One Relationship
When only one instance of an entity is associated with the relationship, then it is known as one to one relationship.
For example, A female can marry to one male, and a male can marry to one female.

b. One-to-many relationship
When only one instance of the entity on the left, and more than one instance of an entity on the right associates with the relationship then this is known as a one-to-many relationship.
For example, Scientist can invent many inventions, but the invention is done by the only specific scientist.

c. Many-to-one relationship
When more than one instance of the entity on the left, and only one instance of an entity on the right associates with the relationship then it is known as a many-to-one relationship.
For example, Student enrolls for only one course, but a course can have many students.

d. Many-to-many relationship
When more than one instance of the entity on the left, and more than one instance of an entity on the right associates with the relationship then it is known as a many-to-many relationship.
For example, Employee can assign by many projects and project can have many employees.

 
