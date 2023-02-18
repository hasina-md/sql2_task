# sql2_task 
### anyalzying daily expenses, real use-case.

## Information about expenditures. 
##### Each day people spend money on varius things. Each transaction holds a bunch of meta (meta data is a data that provides/describes information of other data.)information.  instead of going to waste, that information can be used to learn about one's tendencies. What percentage of money is spent on food? on transport? travlling?  how expensive are the cities that were visited? how much money is spent daily? weekly? mothly? We use
> The DATA EXPENSES TRACKER.

#### Here is the sample data of expenditure of a person (Ravi)

> All we need to create a data base, a table, insert the columns in the table, insert the sample data information, as given below;

1. exp_id
1. catergory
1. date
1. country/place
1. expense/amount
1.payment_mode
1. decription

### Sample Data of expense_tracker

| exp_id | category   | date     | country/place | expense/amount  | description      | payment_mode |
| ---| ---| --- | ---| --- | --- | --- |
|   1902    | Food      |1-02-2023| saudiarabia |  6000   |chicken_shawarma,kahwa     | upi        |
|   1909    | travelling     |1-08-2022| madinah |  10000   | visited Jabal al nour     | cash        |
|   2909    | shoping     |8-08-2022| madinah |  19000   | brougt abayah | cash        |
|   3909    | alms     |8-05-2022| andhra pradesh |  29000   | donation | cash        |

## create expense_tracker
```sql
 create table expense_tracker(exp_id int, category varchar(20), date date , country/place varchar(20)expense/ amount float, description varchar(30), payment_mode varchar(10));

## insert rows in expense_tracker
 ```sql
 insert into expense_tracker values (
    1902, 'food', 1-02-2023, 'saudiarabia', 6000, 'chickenshawarma,kahwa', 'upi',
    1909, 'travelling', 1-08-2022, 'madinah', 10000, 'visited jabal al noor', 'cash',
    2909, 'shoping', 8-08-2022, 'madinah', 19000, 'bought abaya', 'cash',
    3909, 'alms', 8-05-2022, 'andhra pradesh', 29000, 'donation', 'cash'
 )

 ## json
 ```json
 {
    "expense_id": 1902, 
    "category" : "food",
    "date" : "1-02-2023",
    "country/place" : "saudiarabia",
    "expense/amount: 6000,
    "description" : "chicken_shawarma,kahwa",
    "payment_mode" : "upi"
 }


this is the json format storing the data.






