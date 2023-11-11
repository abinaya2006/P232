# P232

CODE:
  select customers.first_name,customers.last_name,company_orders.date,company_orders.order_number 
  from customers inner join company_orders on customers.id=company_orders.customer_id;

OUTPUT:
  ![image](https://github.com/abinaya2006/P232/assets/72507845/8dda9dfe-d09c-44ad-b871-84beb105ab5b)
