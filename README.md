# Inventory & Order Management System

A complete **Inventory & Order Management System** developed using **Oracle SQL** and **PL/SQL** to manage inventory tracking, stock management, customer orders, sales reporting, and audit logging.

---

# Technologies Used

- Oracle SQL
- PL/SQL
- Stored Procedures
- Functions
- Packages
- Triggers
- Cursors
- Dynamic SQL
- Analytical Queries
- Exception Handling
- Transaction Control (`COMMIT` & `ROLLBACK`)

---

# Key Features

## Inventory Management

- Product inventory tracking
- Stock quantity management
- Automatic stock deduction
- Low stock alert system
- Reorder level monitoring

---

## Order Management

- Customer order creation
- Add multiple order items
- Automatic order amount calculation
- Order history management

---

## Advanced PL/SQL Features

- PL/SQL Packages for modular programming
- Stored Procedures and Functions
- Cursor-based sales reporting
- Triggers for automatic stock updates
- Dynamic SQL using `EXECUTE IMMEDIATE`
- Exception handling using `RAISE_APPLICATION_ERROR`

---

## Inventory Validations

- Insufficient stock validation
- Secure transaction handling
- Automatic inventory audit logging
- Data consistency management

---

## Performance Optimization

- Indexed columns for faster query execution
- Optimized SQL queries
- Efficient sales reporting
- Analytical queries using `RANK()`

---

## Audit & Monitoring

- Automatic inventory audit trail
- Tracks stock quantity changes
- Sales monitoring and reporting
- Low stock monitoring system

---

# Database Objects

## Tables

- Products
- Customers
- Orders
- Order_Details
- Inventory_Audit

---

## PL/SQL Objects

- Procedures
- Functions
- Packages
- Triggers
- Cursors
- Dynamic SQL
- Indexes
- Analytical Queries

---

#  Modules Included

| Module | Description |
|--------|-------------|
| Product Management | Manage product inventory |
| Customer Management | Handle customer details |
| Order Processing | Create and process orders |
| Stock Management | Automatic stock deduction |
| Sales Reporting | Generate sales reports |
| Low Stock Alert | Detect low inventory |
| Audit Logging | Store inventory activity logs |
| Performance Optimization | Faster query execution using indexes |

---

# Advanced Features

- Automated inventory tracking
- Automatic stock deduction using triggers
- Low stock alert system
- Sales reporting using cursors
- Analytical queries using `RANK()`
- Dynamic SQL using `EXECUTE IMMEDIATE`
- Inventory audit logging
- Exception handling using `RAISE_APPLICATION_ERROR`
- Indexed columns for performance optimization
- Transaction handling using `COMMIT` and `ROLLBACK`

---

# Learning Outcomes

- Real-world PL/SQL project development
- Inventory and order management system design
- Writing modular PL/SQL code using packages
- Dynamic SQL implementation
- Trigger-based automation
- Analytical query writing using `RANK()`
- Advanced exception handling techniques
- Database transaction management

---

# Sample Operations

## Create Order

```sql
BEGIN
   inventory_package.create_order(1001,1);
END;
/
