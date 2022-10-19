Reading
Status Codes Based On REST Methods

In your own words, describe what each group of status code represents:

100’s = sounds like a heads up message; thing is starting, or thing won't work don't continue

200’s = success or acceptance

300’s = redirect? so a thing has been moved and so a request is redirected with a 300's error? never seen these before.

400’s = bad request, you didn't even get out of the starting gate

500’s = server error, your request was fine but the server itself has some problem

What is a status code 202?

- promise code? valid request but needs to process before return

What is a status code 308?

- permanent redirect. the page has moved forever, but will a redirect happen or just a message with redirect location or something?

What code would you use if an update didn’t return data to a client?

- 204. in what situation would you want to update and return data?

What code would you use if a resource used to exist but no longer does?

- 410.

What is the ‘Forbidden’ status code?

- 403

Videos
Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

- how does save-dev work??? auto gitignore? sounds cool
- but then he immediately adds .env to gitignore manually, idk what save-dev does lol

Why do we need to pull our MongoDB database string out of our server and put it into our .env?

- because access looks different on local vs deploy, it's literally an environment variable

What is middleware?

- code that runs when requests are sent to your server but before they actually get there, I don't think middleware actually does the handoff though?

What does app.use(express.json()) do?

- lets server accept json as a body

What does the /:id mean in a route?

- query param to identify a specific bit of data to get

What is the difference between PUT and PATCH?

- patch can take in partial info whereas put needs all info, or will update all info regardless of whether you passed it in? maybe updates all unpassed in info to null or something?

How do you make a default value in a schema?

- `default: 'I am default'`

What does a 500 error status code mean?

- server side error, generic

What is the difference between a status 200 and a status 201?

- 200 is generic success, 201 is successful creation of a thing
