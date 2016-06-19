# graphql-node-mongo
Experimenting with GraphQL, Node and Mongo

Requires MongoDB running

Using queries/mutations inside Postman is much easier.

Import https://www.getpostman.com/collections/4a2b6fe97174396c522e

example:

Query blog posts
http://localhost:8080/graphql?query={ blogPosts { _id, title, description } }
