# SQL Developer Internship - Task 1

## Objective
The objective of this task is to design a relational database schema for a chosen domain and learn how to create databases, tables, and define relationships between them.

## Domain Chosen
E-commerce System

## Deliverables
- Database Name: `ecommerce`
- Tables: `Customers`, `Orders`, `Products`, `Categories`, `OrderDetails`
- Relationships: One-to-Many and Many-to-Many relationships using foreign keys

## Tools Used
- MySQL Workbench for schema design and table creation
- dbdiagram.io for creating the ER diagram

## Files Included
- `schema.sql` – contains all DDL commands used to create the database and tables
- `ER_Diagram.png` – visual representation of entities and their relationships

## Description
The database consists of multiple entities representing an e-commerce platform:
- Customers can place multiple orders.
- Each order can contain multiple products through an intermediary table, `OrderDetails`.
- Products are categorized using the `Categories` table.
- All relationships are established using foreign keys to ensure referential integrity.

## Outcome
A well-structured and normalized database schema suitable for an e-commerce application.
