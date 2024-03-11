# DB-Assignment

Answer 1 :  The Product and product category entities are related in a parent child relationship. A product category can have many products, but a product can only belong to one product category. This represented by the one to many relationship between two entities.

Answer 2 :  There are a few ways to ensure that each product int the product table has a valid category assigned to it. 
            One way is to use Foreign key constraint that ensures that the value in a coulmn in one table references a valid value in a coulmn in another table.
            Another way is to use Trigger. A trigger is a special type of stored procedure that is automatically executed when a certain event occurs.
            Finally you can use combination of foreign keys constraints and triggers to ensure that each product has a valid category assigned to it.  
