# RESTful-blog-app

RESTful routing blog app from "The Web Developer Bootcamp" by Colt Steele: https://www.udemy.com/the-web-developer-bootcamp/

# Summary

Blogging web app created to practice RESTful routing.

# RESTful Routes:

|Name | Path |HTTP Verb | Purpose | Mongoose Method
|Index |/blogs |GET |List all blogs |Blog.find()
|New |/blogs/new |GET |Show new blog form | N/A
|Create |/blogs |POST |Create a new blog, then redirect somewhere |Blog.create()
|Show |/blogs/:id |GET |Show info about one specific blog |Blog.findById()
|Edit |/blogs/:id/edit |GET |Show edit form for one blog |Blog.findById()
|Update |/blogs/:id |PUT |Update a particular blog, then redirect somewhere |Blog.findByIdAndUpdate()
|Destroy|/blogs/:id |DELETE |Delete a particular blog, then redirect somewhere |Blog.findByIdAndRemove()
