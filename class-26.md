# Reading

## Intent

What is an Intent in Android Studios? Give some fresh examples of when you might use it.

- an Intent is an object created by various things ??? and used as a way to transport information/instructions both within a single app and between seperate apps?
- intents activate activities, services, and broadcast recievers, but not content providers
- ex: when I scan a QR code in my camera app, I bet it sends an Intent to my default browser, which then opens the scanned link

## Activity

Describe an Activity in your own word.

- Sounds like a single purpose, standalone page or scene. Your website might have a page for login, a page for searching, a page for checkout, etc; each of these are equivalent to an activity in an android app
- It also sounds like an ~everything in android is a service~ sort of thing, but maybe that's not quite right, more like everything your user will see

## Service

- Implied -> background service. Some process with no user interface
- Do activities begin/run services exclusively or can they run their own processes?
- Started Service -> a service to keep running until it's completed
- Bound Service -> a service that is being used/required by another service

## Broadcast Reciever

- a way for apps to talk to the system and visa versa.
- a gateway, not a workhorse

## Content Provider

- not exactly sure on this one, sounds like a way for an app to manage how other apps interact with it's data. What is avaiable or not, does other app have permission, how is this specific piece of data refered to, etc
