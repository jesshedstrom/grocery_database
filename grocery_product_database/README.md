# Grocery Product Database 🛍️
## Project Overview
The Grocery Product Database project is designed to create a structured inventory of grocery items, focusing on essential data like product names, categories, pricing, and availability. This database will serve as a foundation for building applications that require a comprehensive grocery item dataset, supporting functionalities like price comparison, product cataloging, and inventory tracking.

## Project Goals 🎯
- **Database Design:** Learn the basics of database structure, including entities, attributes, and relationships within a grocery product context.
- **Data Organization:** Organize data efficiently to support fast, accurate queries related to product search and retrieval.
- **Practical Use Cases:** Create a scalable database that could support applications such as price comparison tools, inventory management systems, and customer-facing grocery shopping apps.
## Database Entities and Relationships 🫂
### Entities (Tables)
1. **Products:** Represents individual grocery items.
2. **Categories:** Represents the category each product belongs to (e.g., Dairy, Produce, Snacks).
3. **Stores:** Represents the stores where products are available.
4. **Prices:** Represents the price of each product in different stores.
## Example Columns
- **Products:** `product_id`, `name`, `category_id`, `brand`, `description`
- **Categories:** `category_id`, `name`, `description`
- **Stores:** `store_id`, `name`, `location`, `website`
- **Prices:** `price_id`, `product_id`, `store_id`, `price`, `date`
## Key Relationships 👯‍♀️
- **Products to Categories:** Each product is linked to one category.
- **Products to Stores (via Prices):** Many-to-many relationship, where each product can have different prices at different stores. This relationship is facilitated through the `Prices` table.
## Learning Objectives
- **Entity-Relationship Mapping:** Understand how to set up entities and define their relationships for efficient data retrieval.
- **Database Normalization:** Apply normalization principles to avoid redundancy and maintain data integrity.
- **Basic SQL Queries:** Practice querying this database to retrieve information such as product listings by category, pricing information by store, and availability details.
## Getting Started
1. **Database Setup**: Install PostgreSQL and create a new database named `grocery_product_database`.
2. **Schema Creation**: Use the provided schema (once created) to set up tables and relationships.
3. **Data Insertion**: Populate tables with sample data to test database queries.
4. **Sample Queries**: Experiment with basic SQL queries to retrieve data based on various criteria.
## Future Enhancements 🔮
- **Add Supplier Information:** Link products to suppliers for expanded tracking capabilities.
- **Add Expiration Data: Include** expiration dates for perishable items.
- **API Integration:** Make this database accessible through an API for use in applications.
## Notes
This project is part of a larger set of database projects designed to help build expertise in data management, query optimization, and database design. Check out the parent repository,`grocery_database`, for additional projects and resources.
