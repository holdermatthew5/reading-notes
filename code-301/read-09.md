Functional Programming

In functional programming we don't use loops or mutators?
Referential transparency refers to a functiona that always returns the same value when given the same arguments. So it can't rely on changing data.
Your function also cannot have 'side-effects'. Meaning it can't mutate data, log to any console or terminal, or perform any task outside of it's main purpose. (Does this mean error logs have to be done by envoking an external error function inside the function that encountered the error?)
Console.log is impure because it writes to the console.
Eventlisteners are impure because they most likely rely on changing data.
Math.random is impure because it does not return the same output when it recieves the same input.
An ajax call is impure because it relies on changing data.
80/20 rule states that 80% of your functions should be pure while the remaining 20% are only impure out of their necessity.
Object.freeze({key: value}) creates an object that cannot be mutated which allows it to be used in a pure function without making the function impure. It can be assigned to a const variable for ease of reference.
Instead of mutating arrays simply create a new one with the change and return that instead.