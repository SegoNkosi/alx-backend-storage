README FOR 0x01-NoSQL

INSTRUCTIONS AND REQUIREMENTS

1. Write a script that lists all databases in MongoDB.

2. Write a script that creates or uses the database my_db:

3. Write a script that inserts a document in the collection school:

The document must have one attribute name with value “ALX”
The database name will be passed as option of mongo command

4. Write a script that lists all documents in the collection school:

The database name will be passed as option of mongo command

5. Write a script that lists all documents with name="ALX" in the collection school:

The database name will be passed as option of mongo command

6. Write a script that displays the number of documents in the collection school:

The database name will be passed as option of mongo command

7. Write a script that adds a new attribute to a document in the collection school:

The script should update only document with name="Holberton school" (all of them)
The update should add the attribute address with the value “972 Mission street”
The database name will be passed as option of mongo command

8. Write a script that deletes all documents with name="ALX School" in the collection school:

The database name will be passed as option of mongo command

9. Write a Python function that lists all documents in a collection:

Prototype: def list_all(mongo_collection):
Return an empty list if no document in the collection
mongo_collection will be the pymongo collection object

10. Write a Python function that inserts a new document in a collection based on kwargs:

Prototype: def insert_school(mongo_collection, **kwargs):
mongo_collection will be the pymongo collection object
Returns the new _id

11. Write a Python function that changes all topics of a school document based on the name:

Prototype: def update_topics(mongo_collection, name, topics):
mongo_collection will be the pymongo collection object
name (string) will be the school name to update
topics (list of strings) will be the list of topics approached in the school

12. Write a Python function that returns the list of school having a specific topic:

Prototype: def schools_by_topic(mongo_collection, topic):
mongo_collection will be the pymongo collection object
topic (string) will be topic searched

13. Write a Python script that provides some stats about Nginx logs stored in MongoDB:

Database: logs
Collection: nginx
Display (same as the example):
first line: x logs where x is the number of documents in this collection
second line: Methods:
5 lines with the number of documents with the method = ["GET", "POST", "PUT", "PATCH", "DELETE"] in this order (see example below - warning: it’s a tabulation before each line)
one line with the number of documents with:
method=GET
path=/status
You can use this dump as data sample: dump.zip

The output of your script must be exactly the same as the example

14. Write a script that lists all documents with name starting by ALX in the collection school:

The database name will be passed as option of mongo command

15. Write a Python function that returns all students sorted by average score:

Prototype: def top_students(mongo_collection):
mongo_collection will be the pymongo collection object
The top must be ordered
The average score must be part of each item returns with key = averageScore

16. Improve 12-log_stats.py by adding the top 10 of the most present IPs in the collection nginx of the database logs:

The IPs top must be sorted (like the example below)
