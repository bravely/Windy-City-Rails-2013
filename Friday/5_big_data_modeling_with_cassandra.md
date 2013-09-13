# Big Data Modeling with Cassandra
by [Mat Brown (@0utoftime)](http://www.twitter.com/0utoftime) at Rap Genius
github.com/outoftime

http://github.com/cequel/cequel
mat@rapgenius.com

## Why Cassandra?
#### Distributed and Masterless.
* Talk to any node you want.
* Tolerant to failure. If a node goes down, whatever.
* Scaling.
* Optimized for Writes.

### Okay, but *Why Cassandra?*
* Tables, Rows, and Columns
* CQL: Looks like SQL, but isn't quite. Very similar though!

### Why *not* Cassandra?
* Schema Constrains Queries: ?
* Data integrity constraints: Can't do NOT_NULL. UNIQUE columns. No Foreign Key/Joins. DB can't do these, leave it to the app.
* CQL < SQL. Not relational, so no joins. Subsets!
* Transactions: nope

## Data Modeling.
Lets make a blog!

No auto-incrementing.

Secondary Indexes! But only one column per secondary index.

## Lower level.

* Column Family: Looks like ruby hash.
* Wide Rows stick together. Each. 
* Compound Types: Tuples. Woot.

### Back to the blog.
* Partition Key
* Clustering Column
* Data Column Name
* Data Column Value

```
	SELECT * FROM posts
	WHERE blog_subdomain = 'mycat'
	ORDER BY id DESC
	LIMIT 10
```
* Range Queries: Very nice!
* Secondary Indexes: DO NOT USE TO DRIVE CORE DATA ACCESS.
* Write without reading.
* Sipmle Primary Keys: Can't do range queries. Simple PK.