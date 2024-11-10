# Jaspersoft Examples

To run this project, I used a local posgresql database. Since it uses JDBC (Java Database Connectivity), it is possible to use any remote database.

### Important

- Jaspersoft uses Java. For testing purposes, I used `OpenJDK 21.0.2`, but you can use any version of Java.
- I used `PostgreSQL 13.4` for the database, but you can use any other database that supports JDBC.

The database that I used is called `jasper_demo` which had two tables: `customers` and `products`. Be sure to have the following attributes

- `customers` table:

  - `id` (int)
  - `first_name` (varchar)
  - `last_name` (varchar)
  - `email` (varchar)
  - `created_date` (date)

- `products` table:
  - `order_id` (int)
  - `orders_id` (int)
  - `order_amount` (int)
  - `status` (varchar)
