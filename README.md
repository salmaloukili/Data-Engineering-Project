# Database Optimization Project

This project focuses on optimizing and normalizing the MoviesDB relational database to enhance performance, reduce redundancy, and improve data integrity. The database, originally consisting of four tables with substantial issues, was expanded with a fifth table and refined according to SQL normalization principles.

## Key Enhancements
- **Normalization**: Converted `VARCHAR` primary keys to `INT` and separated comma-separated lists into individual rows for efficient querying.
- **NULL Value Reduction**: Moved columns with excessive NULLs to separate tables, improving query efficiency.
- **Foreign Keys & Indexing**: Established foreign key constraints and added indexes on key columns to improve relational integrity and query speed.
- **Additional Features**: Created views, stored procedures, and triggers for added functionality and data consistency.

## Results
Optimized the database with up to 99% lower query costs in key cases, meeting requirements for a normalized, efficient, and easily manageable SQL database.

