# Data modeling - Levels

## We classify the modeling process into three levels:

1. Conceptual model (high level) - MCD

1. Logical Model - MLD

1. Physical Model (low level) - MFD


## Conceptual model


This is the first phase of modeling, where we represent the world in relation to power through a simplified view of data and their relationships. This way we can determine what information will be stored in the DB.

At this level the project is independent from DBMS.

Example:
**Register a product in a store**
Required data: Product name, product category (cleaning, hygiene, etc.), supplier code, type of packaging, size, quantity.

At this level, details of the implementation do not appear, however it is detailed enough to be able to describe the types of data required, their relationships with each other and rules of consistency.


## Logical model


(images/exampleofMER.jpg)

* A logical model has concepts that users are able to understand, while not being far from the physical model of the database.

* At this level the project is independent from DBMS.

* It consists of the logical specification of the data in a format suitable to the chosen DBMS. The data types are completely defined.


## Physical model


(images/estructuretable.png)

* **From a logical model** we derive **the physical model**, which details the physical structure components of the database, including tables, fields, types of values, etc.

* When creating the physical model, we can start implementing the database using the most suitable DBMS.


## Three-tier architecture


(images/arqlevels.png)


## Database schema


* A schema and a database definition specified during the project, stored from the **data dictionary**.

* A scheme rarely changes during the life of the DBMS.

* This is about organizing the data into a plan that shows how the bank is built.

* The scheme defines tables, fields, relationships, views, functions and many other elements that make up the DB.


## Stages of DB development
The main steps in the development of a DB are:

- Requirements specification and analysis.
 - The requirements are documented.

- Conceptual design
 - Based on requirements

- Logical design
 - Expressed in a data model, such as the relational one.

- Physical project
 - Specifications for storing and accessing the database.
 - DB implementation, insertion of real data and maintenance.


## Modeling tasks

The modeling tasks must be performed so that it is possible to perform data modeling and functional DB design:

* Identify the types of entities

* Identify attributes
 
* Identify relationships
 
* Create and associate keys
 
* Normalize to reduce redundancy
 
* Denormalize to increase performance

## MER
After surveying the requirements, these are transformed into a **Entity-Relationship Model** (MER), which consists of the following elements:

* Entities
* Relationships
* Attributes

The model is further refined using specific techniques and finally implemented in a physical database.



 

