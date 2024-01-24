# Jdbc

## connections
- driver manager - a class that interacts with the driver for creating connections
- datasource - a modern class that interacts with the driver for creating connections
- connection - a class 
## Executions
- statement - the representation SQL to be executed
- resultset - he response from the database in a logical
- prepared statement - precompiled statements
- callable statement - references stored procedures
## Transactions
- block of code that executes togeher
- auto-commit - 

## CRUD
- create, read, update, delete
- part of the data manipulation language
# Thoughts
- learn SQL
- learn data theory
- learn relational algebra
- understanding indexes

## Creating data
- INSERT statement
- constraints must be honored
- isolation levels can impact results
- not idemnpotent

## Read data
- SELECT statement
- constraint not important unless doing joins
- idempotent operation

## Update data
 - UPDATE statement
 - isolation levels have impact
 - should be idempotent

## Delete data
- DELETE
- constraints can cause errors
- idempotent after first execution
- isolation levels can impact

## DAO Basics
- provide abstraction between jdbc and the rest of the code
- abstraction or true object
## DTO
- data transfer object
- provides single domain data
## DAO
- supports multiple tables
- ## DAO Factory