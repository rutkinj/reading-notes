# Reading 38

## Intent Filter

- add an intent filter to your app to allow other apps to start it via an intent
- intent filters consist of:
    - an action, such as send or view
    - a category, not certain what this is exactly
    - data types, determines what kind of data the intent filter can handle
- an intent will only have one of each of these, but the filter can be built to handle all sorts of intents
- Implicit intent -> no call to a specific component, instead calls for an action. Sounds likes it's handled by the android system and uses intent filters to find the best component for the job.
- Explicit intent -> call to a specific component. This is what we've been using for page to page navigtion in our app.

