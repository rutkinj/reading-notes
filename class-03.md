# Reading

## Primitive vs. Object

- primitives are the regular ol' int or char
- their object counterparts are Integer and Character
- object type aka reference type aka wrapped/wrapper class
- primitives are smaller and relatively faster to access (stack vs heap)
- in the context of arrays, the wrapped classes become more space efficient
  - but the sentence in the article is difficult to parse...
- in array operations, primitives significantly win on speed
- default values are ~0 for prim and `null` for wrapper
- I can't say I'm sold on reference type variables lol
- "On the other hand, current Java language specification doesn't allow usage of primitive types in the parametrized types (generics),  in the Java collections or the Reflection API."
- I don't know what those things are tho

## Exceptions

### what

- exceptional event: something that messes up program execution, an error
- catch an exception: an exception goes up the callstack, searching for an appropriate handler, if found exception handler does it's thing
- if the exception is not "caught", runtime terminates
- checked exception: anticipated and planned for, no crash, catch/specify
- error: unexpected, external, probably crashes
- runtime exception: unexpected, internal, probably crashes, maybe just doesn't compile?

### how

- possible exception making code must be contained in either a try/catch or a method w the `throw` clause (catch or specify)
- try/catch looks much the same, catch looks for a specific exception type. use `|` to catch various
- finally is a new bit, executes after the try/catch is executed regardless of exception (unless your runtime exits)
- try-with-resources seems like an alternative to finally. I'm not sure what resources exactly refers to or why you need to close them? looks like resources are maybe object instances that will just hang around in memory if not manually closed?

## Scanner

- seems useful for extracting data from files of a specifc format
- is scanner how java interacts with json files?
