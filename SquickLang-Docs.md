# SquickLang

Język do zarządzania bazami danych PostgreSQL

" * " = (optional)

## DML (Data Manipulation Language):
### SELECT
`query <name> = <DATABASE>.<TABLE>[*<column1>, *<column2>]`

( [ ] = SELECT * )

example:

```
query ZAPYTANIE1 = DATABASE1.TABLE1["nickname", "name", "age"]
```

is equal to:

`SELECT nickname, name, age FROM DATABASE1.TABLE1;`

### INSERT

`<DATABSE>.<TABLE>.append{ columns : [<column1>, <column2>], values : [ [<value1_1>, <value1_2>], [<value2_1>, <value2_2>] ]}`

example:

```
<DATABASE1>.<TABLE1>.append{ 
  columns: ["nickname", "name", "age"],
  values: [
    ["janek123", "Jan", 19],
    ["wojtek123", "Wojtek", 23]
  ]
}
```

is equal to:

`INSERT INTO DATABSE1.TABLE1 (nickname, name, age) VALUES ("janek123", "Jan", 19), ("wojtek123", "Wojtek", 23);`

### UPDATE

`<DATABSE>.<TABLE>.update{ <column1> : <value1>, <column2> : <value2>] }`


example:

```
<DATABASE1>.<TABLE1>.update{ 
  "name" : "Jan",
  "age" : 19
}.where("nickname" == "janek123")
```

is equal to:

`UPDATE DATABSE1.TABLE1 SET name = "Jan", age = 19 WHERE nickname = "janek123;`