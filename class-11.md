# Reading

## Data with JPA

- jpa -> java persistence api
- lots of `@` annotations
- looks like we are making an object that can be easily stored in a relational db
- you have to make a custom db interface for your object in order to store it
- everything looks pretty straightforward but too verbose to reasonably write down.
- saved for reference

## JPARepository

[Copypasta from linked article](https://www.baeldung.com/spring-data-repositories)
- findAll() – get a List of all available entities in database
- findAll(…) – get a List of all available entities and sort them using the provided condition
- save(…) – save an Iterable of entities. Here, we can pass multiple objects to save them in a batch
- flush() – flush all pending task to the database
- saveAndFlush(…) – save the entity and flush changes immediately
- deleteInBatch(…) – delete an Iterable of entities. Here, we can pass multiple objects to delete them in a batch
