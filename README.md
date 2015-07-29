

### Students Will Be Able To...
* Set up has_many and belongs_to ActiveRecord relationships
* Understand how has_many/belongs_to works via an id column
* Build up and down migrations to create and modify tables

---
### Getting Real with Active Record
<img align="right" src="http://librarylink.regent.edu/wp-content/uploads/2012/10/databases.jpg" width="400" hspace="20"> Last week we did a ton of work with ActiveRecord to get our databases hooked up to our apps. Our twitter database is pretty simple though - we just have one tweets table with users and their statuses. But what if we were keeping track of tweets and followers and trending hashtags and direct messages? We would need a much more complex database with separate tables and models for tweets, users, hashtags and direct messages. 

Getting all of these tables hooked up to each other and making all of these models play nice is super important and that is where we see the magic of ActiveRecord. 

