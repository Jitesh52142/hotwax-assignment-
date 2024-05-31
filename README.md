# hotwax-assignment-

#Q1. Check status of your order?
Ans. Let order id of your order be 'O1' then the query will be as follows
(select user_id,status from order_data where order_id = "1";)

#Q2. Find total amount of your orders ? 
Ans. so find the total amount of orders we use select statement ..
(SELECT ORDER_ID ,TOTAL AS TOTAL_AMOUNT FROM ORDER_DATA;)

#Q3. Update your city ?
Ans. FOR UPDATE CITY WE FIRST WANT TO UPDATE PINCODE FROM USER TABLE BEACAUSE WHENEVER  WE CHANGE CITY THE PINCODE IS ALSO CHANGE SO FIRSTLY WE CHANGE THE PINCODE THE GO FOR THIS QUERY:
(Update address set city = "indore" where pin_code = 452002;)

#Q4. change product_description in product table ? 
Ans. To change product description in product table , use the SQL UPDATE statement along with SET , then the SQL query will be :
(update products set product_description ="air shose " where product_id= "p2";)

#Q5. Display returnable products ?
Ans. To display returnable products , use the SELECT statement along with WHERE CLAUSE , then the SQL query will be :
(select product_id ,product_name ,product_description from products where product_retuned = "yes";)

#Q6. Generate er diagram ?
Ans. ER Diagram is attached with the repo.........
