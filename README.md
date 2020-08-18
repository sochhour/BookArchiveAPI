# Creating a Web API with Python and Flask 

In this project I built a prototype API using Python and the Flask web framework. 
This API acts as a distant reading archive - a book catalog that includeds data
of interest to those working on digital projects. Flask was ideal for this project
as their applications are able to be used in a variety of ways and are
suited for contained applications such as an API. 

I used Flask to build a home page for the website. I then added a dictionary-like list 
of data in a JSON file format with information such as id, author, title, first-sentence,
and last-sentence documented. Lastly, I implemented a 'get' HTTP request whether the API
can read data from a SQLite database. 

These filtering properties, as a whole, allow users to query parameters, build an SQL 
query, find matching objects for the query, and return those matches in a JSON format.

