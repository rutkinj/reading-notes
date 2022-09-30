# Reading

## Understanding the JavaScript Call Stack

What is a ‘call’?

-function invocation

How many ‘calls’ can happen at once?

- one, if call stack is single threaded like in JS

What does LIFO mean?

- last in, first out

Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

    funcytown:    call:     stack:
    uno(){        uno()     drie()
      deux()                deux()
    }                       uno()
    deux(){
      drie()
    }
    drie(){
      console.log('hello')
    }

What causes a Stack Overflow?

- endless loop

## JavaScript error messages

What is a ‘reference error’?

- bad reference; mispelled variable, or variable that hasn't been declared yet

What is a ‘syntax error’?

- bad syntax; your code grammar is bad

What is a ‘range error’?

- trying to access a value that doesn't exist, usually by index of an array

What is a ‘type error’?

- you're doing something with the wrong thing; varThatHoldsANumber.toUpperCase()

What is a breakpoint?

- a spot where you manually pause your code to check what was going on right around that point.

What does the word ‘debugger’ do in your code?

- shows call stack up to that point
