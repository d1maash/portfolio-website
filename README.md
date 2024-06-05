# portfolio-website
My Portfolio Website 


git init <br> 
git add --all  <br> 
git commit -a -m 'first commit'  <br> 
git remote add origin https://github.com/user/project.git  <br> 
git pull --rebase origin master  <br> 
git push origin master  <br> 








Конечно! Вот обновленный текст с жирными вопросами:

**OOP (Object-Oriented Programming)**

**•  What is Object-Oriented Programming (OOP)?** Object-Oriented Programming (OOP) is a programming paradigm based on the concept of "objects", which can contain data in the form of fields (often known as attributes or properties), and code in the form of procedures (often known as methods). OOP focuses on the objects that developers want to manipulate rather than the logic required to manipulate them.<br>
**•  What is Procedural Programming?** Procedural programming is a programming paradigm that uses a linear or top-down approach. It is based on the concept of procedure calls, where statements are structured into procedures (also known as routines or subroutines).<br>
**•  Object-Oriented Programming (OOP) and how does it differ from procedural programming?** OOP differs from procedural programming in that it organizes software design around data, or objects, rather than functions and logic. OOP models real-world entities as software objects that have some data associated with them and can perform certain functions. Procedural programming, on the other hand, is structured around functions and logic flows.<br>
**•  The concept of classes in Python.** A class in Python is a blueprint for creating objects. A class defines a set of attributes and methods that the created objects can have. It allows bundling of data and functionality together.<br>
**•  Public, Private, and Protected Members in Python Classes.**<br>
•	Public Members: Accessible from anywhere.<br>
•	Private Members: Accessible only within the class where they are defined. They are defined with double underscores (__).<br>
•	Protected Members: Accessible within the class and its subclasses. They are defined with a single underscore (_).<br>
**•  The concept of objects in Python.** Objects are instances of classes. An object is created using the class constructor and can have attributes (variables) and methods (functions) defined by the class.<br>
**•  Constructor Method (__init__) in Python.** The __init__ method in Python is a special method that gets called when an object is instantiated. It is used to initialize the object's attributes.<br>
**•  Destructor Method (__del__) in Python.** The __del__ method in Python is a special method that gets called when an object is about to be destroyed. It is used to clean up resources before the object is removed from memory.<br>
**•  How is encapsulation implemented in Python? Provide an example.** Encapsulation in Python is implemented using private and protected access specifiers. Example:<br>
class Example:<br>
    def __init__(self, value):<br>
        self.__private_value = value  # private variable<br>
        self._protected_value = value  # protected variable<br>
    def get_private_value(self):<br>
        return self.__private_value<br>
    def set_private_value(self, value):<br>
        self.__private_value = value<br>
**•  What is inheritance in Python? Give an example of a simple inheritance hierarchy.** Inheritance allows a class to inherit attributes and methods from another class. Example:<br>
class Parent:<br>
    def __init__(self, name):<br>
        self.name = name<br>
    def display_name(self):<br>
        print(self.name)<br>
class Child(Parent):<br>
    def __init__(self, name, age):<br>
        super().__init__(name)<br>
        self.age = age<br>
    def display_age(self):<br>
        print(self.age)<br>
**•  Single Inheritance in Python.** Single inheritance allows a class to inherit from one superclass. Example:<br>
class Parent:<br>
    pass<br>
class Child(Parent):<br>
    pass<br>
**•  Multiple Inheritance in Python.** Multiple inheritance allows a class to inherit from more than one superclass. Example:<br>
class Parent1:<br>
    pass<br>
class Parent2:<br>
    pass<br>
class Child(Parent1, Parent2):<br>
    pass<br>
**•  Multilevel Inheritance in Python.** Multilevel inheritance is a type of inheritance where a class inherits from a class that inherits from another class. Example:<br>
class Grandparent:<br>
    pass<br>
class Parent(Grandparent):<br>
    pass<br>
class Child(Parent):<br>
    pass<br>
**•  Hierarchical Inheritance in Python.** Hierarchical inheritance is a type of inheritance where multiple classes inherit from a single superclass. Example:<br>
class Parent:<br>
    pass<br>
class Child1(Parent):<br>
    pass<br>
class Child2(Parent):<br>
    pass<br>
**•  super() Function in Python Inheritance.** The super() function is used to call the parent class's methods. Example:<br>
class Parent:<br>
    def __init__(self):<br>
        self.value = "Parent"<br>
class Child(Parent):<br>
    def __init__(self):<br>
        super().__init__()<br>
        print(self.value)<br>
**•  Composition in Python.** Composition is a design principle where one class contains an object of another class. Example:<br>
class Engine:<br>
    def start(self):<br>
        print("Engine started")<br>
class Car:<br>
    def __init__(self):<br>
        self.engine = Engine()<br>
    def start(self):<br>
        self.engine.start()<br>
**•  Aggregation in Python.** Aggregation is a type of association where one class owns another class, but both can exist independently. Example:<br>
class Department:<br>
    pass<br>
class Employee:<br>
    def __init__(self, department):<br>
        self.department = department<br>
**•  Association in Python.** Association is a relationship between two classes where they use each other’s functionalities but can exist independently. Example:<br>
class Teacher:<br>
    def __init__(self, name):<br>
        self.name = name<br>
class Course:<br>
    def __init__(self, title):<br>
        self.title = title<br>
**•  Importance of polymorphism in OOP.** Polymorphism allows objects of different classes to be treated as objects of a common superclass. It is important for flexibility and the ability to use a single interface for different underlying forms (data types).<br>
**•  What is the purpose of the __init__ method in Python classes?** The __init__ method initializes an object's state by setting initial values for its attributes.<br>
**•  How do you achieve method overloading in Python?** Python does not support traditional method overloading. Instead, default arguments and variable-length arguments are used to achieve similar functionality.<br>
def greet(name, message="Hello"):<br>
    print(f"{message}, {name}")<br>
**•  Magic Methods (Special Methods) in Python.** Magic methods in Python are special methods that start and end with double underscores. They allow customization of class behavior. Examples include __init__, __str__, __repr__.<br>
**•  __str__ and __repr__ Methods in Python.**<br>
•	__str__: Returns a human-readable string representation of an object.<br>
•	__repr__: Returns an unambiguous string representation of an object, often used for debugging.<br>
**•  __len__ and __getitem__ Methods in Python.**<br>
•	__len__: Returns the length of an object.<br>
•	__getitem__: Retrieves an item from a collection using indexing.<br>
**•  __add__ and __sub__ Methods in Python.**<br>
•	__add__: Defines the behavior for the + operator.<br>
•	__sub__: Defines the behavior for the - operator.<br>
**•  Class and Static Methods in Python.**<br>
•	Class methods: Defined using @classmethod, take cls as the first parameter, and can modify class state.<br>
•	Static methods: Defined using @staticmethod, do not modify class or instance state.<br>
**•  @classmethod and @staticmethod Decorators in Python.**<br>
•	@classmethod: Used to define a method bound to the class and not the instance.<br>
•	@staticmethod: Used to define a method that does not access or modify class or instance state.<br>
**•  Explain the difference between class variables and instance variables in Python.**<br>
•	Class variables: Shared by all instances of the class.<br>
•	Instance variables: Unique to each instance.<br>
**•  Discuss the concept of method overriding and provide an example in Python.** Method overriding allows a subclass to provide a specific implementation of a method already defined in its superclass.<br>
class Parent:<br>
    def greet(self):<br>
        print("Hello from Parent")<br>
class Child(Parent):<br>
    def greet(self):<br>
        print("Hello from Child")<br>
**•  How can you implement multiple inheritance in Python?** Multiple inheritance can be implemented by defining a class that inherits from multiple base classes.<br>
class Parent1:<br>
    pass<br>
class Parent2:<br>
    pass<br>
class Child(Parent1, Parent2):<br>
    pass<br>


**PostgreSQL**


**•  What is PostgreSQL and how does it differ from other relational database systems?** PostgreSQL is an advanced open-source relational database management system. It differs from other

 RDBMS by its support for advanced data types, extensibility, and compliance with SQL standards.<br>
**•  Explain the architecture of PostgreSQL, including the major components and their roles.** The architecture of PostgreSQL includes components such as the postmaster, background processes, shared memory, and the database itself. The postmaster is the main server process that handles connections, the background processes handle tasks like writing to disk, and shared memory is used for caching and inter-process communication.<br>
**•  How do you install PostgreSQL on a Unix-based system?** Installation involves updating the package lists, installing the PostgreSQL package, and starting the PostgreSQL service. Example commands:<br>
sudo apt update<br>
sudo apt install postgresql postgresql-contrib<br>
sudo systemctl start postgresql<br>
**•  Discuss the process of creating a new database and user in PostgreSQL.** Creating a new database and user involves using the `createdb` and `createuser` commands or executing SQL commands within the `psql` interface. Example:<br>
createdb mydatabase<br>
createuser myuser --interactive<br>
**•  How do you connect to a PostgreSQL database using the psql command-line tool?** You can connect to a database using the `psql` command followed by the database name, username, and host information. Example:<br>
psql -U myuser -d mydatabase -h localhost<br>
**•  What are the different data types available in PostgreSQL?** PostgreSQL supports a wide range of data types including integer, floating-point, string, boolean, date/time, arrays, JSON, and custom types using the CREATE TYPE command.<br>
**•  Explain the concept of tablespaces in PostgreSQL and how to create one.** Tablespaces in PostgreSQL are locations on disk where database objects are stored. They allow database administrators to manage disk layout. Example of creating a tablespace:<br>
CREATE TABLESPACE mytablespace LOCATION '/mnt/data/pgdata';<br>
**•  How do you perform backup and restore operations in PostgreSQL?** Backup and restore operations can be performed using `pg_dump` and `pg_restore` for logical backups, or `pg_basebackup` for physical backups. Example:<br>
pg_dump mydatabase > mydatabase.sql<br>
psql mydatabase < mydatabase.sql<br>
**•  What is the Write-Ahead Logging (WAL) in PostgreSQL and why is it important?** WAL is a logging mechanism that ensures data integrity by recording changes before they are applied. It allows for crash recovery and supports replication.<br>
**•  How do you set up streaming replication in PostgreSQL?** Setting up streaming replication involves configuring the primary server to allow replication connections and setting up a standby server to connect and replicate data. Example steps:<br>
Configure `postgresql.conf` on primary:<br>
wal_level = replica<br>
max_wal_senders = 3<br>
Create a replication user on primary:<br>
CREATE ROLE replicator REPLICATION LOGIN;<br>
Start standby server with `pg_basebackup` and configure recovery:<br>
primary_conninfo = 'host=primary_host user=replicator'<br>
**•  Discuss the role of indexes in PostgreSQL and the types of indexes available.** Indexes improve query performance by allowing faster data retrieval. Types of indexes include B-tree, hash, GiST, SP-GiST, GIN, and BRIN.<br>
**•  How do you create and manage indexes in PostgreSQL?** Indexes are created using the `CREATE INDEX` command. They can be managed by analyzing their usage and dropping unused indexes. Example:<br>
CREATE INDEX myindex ON mytable (mycolumn);<br>
**•  Explain the concept of transactions and isolation levels in PostgreSQL.** Transactions in PostgreSQL are sequences of operations executed as a single unit of work. Isolation levels control the visibility of changes made by concurrent transactions. Levels include READ COMMITTED, REPEATABLE READ, and SERIALIZABLE.<br>
**•  How do you implement foreign keys and constraints in PostgreSQL?** Foreign keys and constraints enforce relationships and data integrity. They are implemented using the `FOREIGN KEY` and `CONSTRAINT` clauses in table definitions. Example:<br>
CREATE TABLE orders (<br>
    order_id SERIAL PRIMARY KEY,<br>
    customer_id INTEGER REFERENCES customers(customer_id),<br>
    CONSTRAINT order_date_check CHECK (order_date <= NOW())<br>
);<br>
**•  Discuss the use of stored procedures and functions in PostgreSQL.** Stored procedures and functions allow for encapsulating business logic within the database. They are created using the `CREATE FUNCTION` or `CREATE PROCEDURE` commands and can be written in various languages like PL/pgSQL, SQL, and more.<br>
**•  What is the role of the PostgreSQL optimizer and how does it work?** The PostgreSQL optimizer generates efficient execution plans for SQL queries. It uses statistics about the data and available indexes to choose the best plan.<br>
**•  How do you analyze and optimize query performance in PostgreSQL?** Query performance is analyzed using `EXPLAIN` and `EXPLAIN ANALYZE` to understand execution plans. Optimization involves indexing, rewriting queries, and adjusting configuration parameters.<br>
**•  Explain the process of table partitioning in PostgreSQL and its benefits.** Table partitioning involves dividing a large table into smaller pieces for better performance and manageability. Benefits include improved query performance and easier maintenance. Example of range partitioning:<br>
CREATE TABLE orders (<br>
    order_id SERIAL,<br>
    order_date DATE<br>
) PARTITION BY RANGE (order_date);<br>
CREATE TABLE orders_2021 PARTITION OF orders FOR VALUES FROM ('2021-01-01') TO ('2022-01-01');<br>
**•  Discuss the security features available in PostgreSQL, including authentication and authorization.** PostgreSQL provides security features such as user authentication (password, LDAP, etc.), role-based access control, SSL/TLS for encrypted connections, and row-level security.<br>
**•  How do you monitor PostgreSQL performance and health?** Monitoring is done using tools like `pg_stat_activity`, `pg_stat_statements`, and external tools like pgAdmin, Prometheus, and Grafana. These tools help track query performance, system resources, and other metrics.<br>
**•  What are extensions in PostgreSQL and how do you install them?** Extensions are modules that add functionality to PostgreSQL. They are installed using the `CREATE EXTENSION` command. Example:<br>
CREATE EXTENSION IF NOT EXISTS hstore;<br>
**•  How do you perform database migration in PostgreSQL?** Database migration involves moving data from one database to another. Tools like `pg_dump`, `pg_restore`, and logical replication can be used. Example:<br>
pg_dump mydatabase | psql -h newhost -d newdatabase<br>
**•  Discuss the role and configuration of connection pooling in PostgreSQL.** Connection pooling reduces the overhead of establishing connections by reusing existing ones. Tools like `PgBouncer` and `pgpool-II` are used for connection pooling. Configuration involves setting pool size, timeouts, and other parameters.<br>
**•  What are the common backup strategies for PostgreSQL databases?** Common strategies include logical backups (using `pg_dump`), physical backups (using `pg_basebackup`), and continuous archiving (using WAL archiving). Each strategy has its advantages and use cases.<br>
**•  How do you handle database corruption and recovery in PostgreSQL?** Handling corruption involves identifying the corrupted data, restoring from backups, and using tools like `pg_resetwal` for recovery. Regular backups and monitoring are crucial for minimizing data loss.<br>
**•  Explain the concept of logical replication in PostgreSQL and its use cases.** Logical replication involves replicating data changes at the logical level, allowing for more flexible replication setups. Use cases include selective replication, data warehousing, and integrating with other systems. Example setup:<br>
CREATE PUBLICATION mypublication FOR TABLE mytable;<br>
CREATE SUBSCRIPTION mysubscription CONNECTION 'host=primary_host dbname=mydatabase user=replicator' PUBLICATION mypublication;<br>
**•  How do you handle large databases and tables in PostgreSQL?** Handling large databases involves strategies like table partitioning, indexing, using efficient data types, and regularly vacuuming to reclaim space.<br>
**•  Discuss the importance of regular maintenance tasks such as vacuuming and analyzing in PostgreSQL.** Regular maintenance tasks like vacuuming and analyzing help in reclaiming space, updating statistics for the optimizer, and ensuring efficient query performance.<br>
**•  What is the role of autovacuum in PostgreSQL and how is it configured?** Autovacuum automatically performs vacuuming and analyzing tasks to maintain database health. Configuration involves setting parameters like `autovacuum_vacuum_threshold`, `autovacuum_vacuum_scale_factor`, and `autovacuum_naptime` in `postgresql.conf`.<br>
**•  Explain the concept of hot standby and failover in PostgreSQL.** Hot standby involves setting up a standby server that can take over in case of primary server failure. Failover is the process of switching to the standby server. This ensures high availability and disaster recovery.<br>
**•  How do you manage database roles and permissions in PostgreSQL?** Database roles and permissions are managed using the `CREATE ROLE`, `GRANT`, and `REVOKE` commands. Roles can be assigned specific privileges and can inherit permissions from other roles.<br>
