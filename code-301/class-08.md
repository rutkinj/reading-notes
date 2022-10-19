# Reading

## API Design Best Practices

What does REST stand for?

- REpresentation State Transfer

REST APIs are designed around a ____.

- resource?

What is an identifier of a resource? Give an example.

- a unique id for a specific resource
- in this example it's `users`
`https://website.com/users/3def34e`

What are the most common HTTP verbs?

- GET PUT POST PATCH DELETE more commonly known as g3pd (i made this up)

What should the URIs be based on?

- nouns of resource, not verbs of operation
- because for any resouce in an api you could GET or DELETE, etc. use your own verbs

Give an example of a good URI.

- `https://website.com/users`

What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

- an api that send data over lots of requests, this is generally bad.
- send one large packet of info instead

What status code does a successful GET request return?

- 200

What status code does an unsuccessful GET request return?

- 404

What status code does a successful POST request return?

- 201 (made a thing)
- 200 (updated? a thing)

What status code does a successful DELETE request return?

- 204 (found thing, nothing to return)
