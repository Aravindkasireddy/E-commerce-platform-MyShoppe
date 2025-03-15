🛒 MyShoppe: Hybrid Relational & NoSQL Database for E-Commerce
This repository contains the design, implementation, and optimization of a hybrid MySQL (RDBMS) and MongoDB (NoSQL) database system for an e-commerce platform, MyShoppe. The project aims to create an efficient, scalable, and secure data management solution for an online marketplace.

📂 Repository Contents
📄 Report (DBS- Group 8 report.pdf) – Detailed research, database design, ER diagrams, normalization, and implementation.
📊 Presentation (Dbs Group 8 presentation.pptx) – Project overview, database architecture, and challenges.

🎯 Project Goals
Design and implement a structured relational database using MySQL for core e-commerce operations.
Enhance flexibility with MongoDB for unstructured data and faster retrieval.
Implement a robust e-commerce architecture with user authentication, product catalog, orders, and payments.
Optimize database performance using query indexing, caching, and transactions.
Ensure security and scalability with data encryption, authentication, and input validation.
🔬 Database Architecture
This project integrates two database technologies: ✅ MySQL (Relational Database)

Used for structured e-commerce data such as users, products, orders, payments, and inventory.
Features normalized schema (3NF) to ensure data integrity and consistency.
✅ MongoDB (NoSQL Database)

Used for flexible, unstructured data like customer reviews, personalized recommendations, and product searches.
Supports horizontal scalability for high-performance applications.
🏆 Key Features & Implementations
✅ ER Diagram & Schema Design

Well-structured relational database schema for e-commerce operations.
Normalization applied (1NF, 2NF, 3NF) to optimize data storage.
✅ Hybrid Database System

MySQL for structured transactional data (e.g., orders, payments).
MongoDB for flexible, fast searches and analytics (e.g., product reviews, recommendations).
✅ Data Migration & Synchronization

Migrated structured data from MySQL to MongoDB using MongoDB Relational Migrator.
Developed real-time data synchronization strategies to maintain consistency.
✅ CRUD Operations & Backend Implementation

Create, Read, Update, Delete (CRUD) queries implemented for both MySQL & MongoDB.
Backend functionalities include user authentication, product management, order tracking, and payment processing.
✅ Performance Optimization Techniques

Query Optimization: Efficient SQL queries, reduced joins.
Indexing & Caching: Enhanced data retrieval performance.
Transaction Handling: Ensured atomicity, consistency, isolation, durability (ACID).
✅ Security & Data Privacy

Encryption for sensitive data (user passwords, payment details).
Role-based authentication (RBAC) for customers, vendors, and admins.
Data validation & sanitization to prevent SQL Injection & XSS attacks.
📊 Platform Comparison: MySQL vs. MongoDB
Feature	MySQL (RDBMS)	MongoDB (NoSQL)
Structure	Tabular, fixed schema	Document-based, flexible schema
Scalability	Vertical scaling	Horizontal scaling
Transactions	ACID-compliant	BASE model (eventual consistency)
Query Speed	Optimized for structured data	Optimized for unstructured data
Use Case	Orders, Payments, Inventory	Product recommendations, Reviews
🚀 Future Enhancements
📌 Microservices-based architecture for modular scaling.
📌 AI-based recommendations using NoSQL analytics.
📌 Real-time analytics dashboard for customer insights.
📌 Performance benchmarking for SQL vs. NoSQL queries.

