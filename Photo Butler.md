# Entity Name

* *[General](#general)*
	* *[Introduction](#introduction)*
	* *[Glossary](#glossary)*
	* *[Use cases](#use-cases)*
	* *[Permissions](#permissions)*
	* *[Requirements](#requirements)*
	    * *[Annotated screenshots](#annotated-screenshots)*
	    * *[Elements description](#elements-description)*
* *[Backend](#backend)*
	* *[Tech documentation](#tech-documentation)*
	* *[Relations](#relations)*
	* *[Data model](#data-model)*
	* *[Endpoints](#endpoints)*
	* *[Non-functional requirements](#non-functional-requirements)*
	* *[Other](#other)*

## General

### Introduction

* General description about Entity
* Business needs
* User needs
* General use cases about Entity and it's role

### Glossary

* Explanations for specific Entities used in the module
* List of all abbreviations and their explanation
* List of data used in the module (financial, staff, etc.)

|*#*|*Abbreviation*|*Name*|*Description*|
|---|--------------|------|-------------|

### Use cases

* Describes behavior for Entity, user interaction with it and how other entities may interact with it

| ID | Use Case | Description |
|------|------------|---------------|

### Permissions

* User roles that have access rights to view, add, update, delete functions

| Role | User ID | View | Add | Update | Delete |
|--------|-----------|--------|-------|----------|----------|

### Requirements

* Overal requirements for frontend and backend. If requirement needs to be implemented only on UI or API - it is marked as 'X' in front of the requirement in the appropriate column, if on both - marked 'X' in both columns

| ID | Section | Subsection | Requirement Description |
|------|-----------|--------------|---------------------------|

### Annotated screenshots

* Visualizing and numbering elements location on the page

### Elements description

* Describes rules for elements

| ID | Control Name |*Component Type*|*Behaviour/Description*|
|------|----------------|----------------|-----------------------|

## Backend

### Tech documentation

* List of Entity fields
* List of validation rules for Entity
* Entity States
* Background processes

### Relations

* Entity belonging to other entities
* Workflow diagrams
* UML diagrams

### Data model

* Database tables
* Stored procedures
* Stored functions
* Views
* Migrations
* Database scheme

### Endpoints

* List of endpoints needed to be implemented

|*#*|*URL*|*Purpose*|*Method*|*Parameters*|*Response*|*Acceptance criteria*|
|---|-----|---------|--------|------------|----------|---------------------|

### Non-functional requirements

  * Current amount of entity items - ?, potential growth - ? items per year
  * Amount of users using module - ?, potential growth - ? users per year
  * Potential amount of concurrent users for module - ? concurrent users
 
### Other

* Data sources
* Background tasks
* Nightly tasks