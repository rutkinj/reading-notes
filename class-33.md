# Reading 33

Describe asynchronous actions in your own words.

- an action that doesn't follow the pattern of call -> complete but instead looks more like call -> promise to complete -> complete where other unrelated actions occur between the second and third steps

What is the benefit of asynchronous methods?

- improved program latency. If your method needs to retrieve info from somewhere on the web, it might take awhile. If your whole program has to wait for that bit of info, regardless of whether it relies on it or not, your poor program is going to lag. If that method to grab info was async, your program could go on it's merry way while that bit of info is making it's way back.
