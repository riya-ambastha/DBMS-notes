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
