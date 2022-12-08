# Reading 29

What database engine is Room wrapped around? Do you think this is a good choice? Why or why not?

- SQLite. I have no idea if that's a good choice or not lol. But it sounds fast and lightweight, which is good for mobile. Maybe it's difficult to make the stored data accessable elsewhere, i.e. not locally.

Do Rooms have any similarities to JPA?

- Both are database interface layers. Both assume the user hates writing sql?

Describe a DAO in your own words

- Data Access Object. They look like objects that are used to interact with specific tables in a database. This is where you would write your inserts, deletes, and custom queries for use elsewhwere in your app.
