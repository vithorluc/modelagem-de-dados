# Relational model and its composition

1. Models: It is a structure that helps to communicate the concepts that are in the mind of the designer. We can use it for tasks like describing, analyzing, specifying and communicating ideas.
Note: The model must have enough details for a developer to be able to build the database according to the needs of the project.


1. Data Modeling: Physical modeling consists of choosing a DBMS and creating the project (Logical Modeling) in this system. The Entities and Relationships Model is an abstract model whose purpose is to describe, in a conceptual way, the data to be used in an Information System or that belong to a domain.


* Data Models;
* Hierarchical;
* Network;
* Relational;
* Object Oriented;
* Non-Relational.


1. Relational Model: In the relational model data is stored in collections of two-dimensional tables, these tables are also called "relations", relations are a way of organizing data in the form of rows and columns, based on logic and set theory.


## Composition of the Relational Model:

 
Collection of objects or relationships that store data;
A set of operators who act in relationships;
Data integrity, for accuracy and consistency.
 

## Components of a Relational Database:

 
1. Table: Basic component of an RDBMS system. Stores necessary data about something in the real world, such as customers, orders or products. also called a relationship. A relational database can have one or more tables.


1. Tuple: Or line / record, represents data required for a particular occurrence of a particular entity. For example, the data for a specific customer. Each row in a table must be identified by a primary key, so that there is no duplication of records.


1. Column: Unit that stores a specific type of data (value) - or does not store anything, with a null value. This is a non-key column, meaning that its value can be repeated in other rows of the table.


1. Relationship: Association between entities (tables), connected by primary keys and foreign keys.
Others: Indices, SP, Triggers, etc.


1. Primary Key: column (attribute) that uniquely identifies a record in the table. For example, a customer's CPF, containing a value that is not repeated in the list.


1. Secondary Key: column that defines how the tables relate to each other. An FK refers to a PK or a unique key in another table (or in the same table!). For example, in the orders table we can have a foreign key making the relationship with the primary key in the customer table.


## Entity-Relationship Model


* MER, creates an entity-relationship diagram from the business specifications or user narratives. It allows to illustrate the entities in a business and also relationships between them. We built the MER during the analysis phase in the system development life cycle.

* A MER separates the information necessary for the business from the activities that are carried out for the business.


## MER components

1. Entity: Something significant, about which we must have information. As examples, we have customers, employees, orders and products.

1. Attributes: Something that describes or qualifies an entity. For example, the entity * client * has attributes that describe his name, address, telephone, identification number, among others.

1. Relationship: This is an association named between entities, with a degree of association. For example, customers can be associated with orders.

## Conventions for modeling entities, relationships, attributes and cardinality

1. Entities: Unique, singular name; Caps Lock;

1. Attributes: Name in the singular; lowercase; mandatory attributes marked with '*'; unique identifier marked with '#'.

1. Relationship: Identifier name (verb); optionality ("must be" or "can be"); degree or cardinality ('one and only one', or 'one or more').

1. Cardinality: It defines the degree of relationship between two entities or tables. In the relational model, we can have the following relationship levels: 1: N, N: N, 1: 1.

[Data Modeling Course](https://www.youtube.com/watch?v=hGstS10kCPM&list=PLucm8g_ezqNoNHU8tjVeHmRGBFnjDIlxD&index=2)








 
