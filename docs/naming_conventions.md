# **DB Naming Conventions** 

This document outlines that naming conventions used within this project for schemas, tables, columns, views and other objects. 

## **Table of Contents**

1. [General](#general)
2. [Tables](#tables)
	- [Bronze](#bronze)
	- [Silver](#silver)
	- [Gold](#gold)
3. [Columns](#columns)
	- [Keys](#keys)
	- [Calculated](#calculated)
4. [Procedures](#procedures)
---

## **General**

- General naming will use snake_case using all lowercase characters and an underscore `_` character to separate words
- Language used will be English
- SQL reserved words to be avoided

## **Tables**

- All tables must begin with an identifier of the source system name.
- **`[source_system]_[entity]`**
	- `[source_system]`: The name of system from which the data was extracted, i.e. `crm`, `erp`
	- `[entity]`: Exact table name in the source system
	- Example: `crm_customers` -> Customer information from the crm system

### **Bronze**

### **Silver**

### **Gold**


## **Columns**

### **Keys**

### **Calculated**

## **Procedures**

