Download the handout. Take a look at its content.

Now, import its contents into MongoDB, into a database called "pcat" and a collection called "products". Use the mongoimport utility to do this.

When done, run this query in the mongo shell:
```
db.products.find( { type : "case" } ).count()
```
What's the result?


## Answer
3