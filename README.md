SQL Queries


1.Query for adding to base table:

```bash
insert into base(base_name)

values("normal");
```


2.Query for fetching data from base table 

```bash
select * 

from base;
```

3.Query for adding data to size table:

```bash
insert into size(size_description)

values("small");
```


4.Query for fetching data from size table:

```bash
select * 

from size;
```


5.Query for adding data to topping table:

```bash
insert into topping(topping_name)

values("cheese");
```


6.Query for fetching data from topping table:

```bash
select * 

from topping;
```

7.Query for adding data to pizza table:
```bash
insert into pizza(base_id,size_id,price)

values(1,2,700);
```


8.Query for fetching data from pizza table:

```bash
select * 

from pizza;
```


9.Query for adding data to customer table:

```bash
insert into customer(customer_name,phone,address)

values("leo",'812999999','rose villa');
```


10.Query for fetching data from customer table:

```bash
select * 

from customer;
```


11.Query for adding data to order table:

```bash
insert into order(customer_id,order_date_time)

values(1,now());
```


12.Query for fetching data from order table:

```bash
select * 

from order;
```


13.Query for adding data to pizzatopping table:

```bash
insert into pizzatopping 

values(1,1);
```


14.Query for fetching data from pizzatopping table:

```bash
select * 

from pizzatopping;
```


15.Query for adding data to pizzaorder table:

```bash
insert into pizzaorder 

values(1,2,1);
```


16.Query for fetching data from pizzaorder table:

```bash
select * 

from pizzaorder;
```



