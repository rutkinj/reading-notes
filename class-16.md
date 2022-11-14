# Reading

## Spring Security

- AutheticationManager -> interface used to confirm authentications
- ProviderManager -> implements above; delegates to several AuthenticationProviders which are similar to above but only support a single kind of auth?
- use auth manager builder to make an auth manager suited to your auth model
- AccessDecisionManager -> uses auth to determine if a user has access rights to certain things
- seems like all this then works through a series of filters, some of which check for auth and access
- you can restrict access to certain methods

## Spring Auth Cheatsheet

- a bit more clear and concise
- hopefully useful after lecture
- saved for ref
