- problem domains are hard I should put some extra effort into these before it gets impossible
- asking someone who knows more about the problem domain can save alot of time and money later
- the progression style of video games can make it easier to understand the problem domain (specifically taking it piece by piece rather than all at once)
- object are a collection of variables intended to represent a real world item
- in an object:
  - variables are called properties
  - functions are known as methods
- booked++ could be added to a function intended to mark a room as booked the function could be called by pushing a button after filling out a form which applies values to variables
- certain controller buttons(video games) could be calling functions intended to make an avatar(object) do something(fire an arrow). Each of these functions could be stored in the object as methods to make it easy to add and remove the character from play(inserting it would be inserting all the necessary functionality and removing it does the same)
- `this` referres to the fact that we're pulling the requested info from the object it's requested in
- `object.command` is dot notation where object represents the thing we're calling and command represents the thing we want it to do.
- `object[command]` has the same affect and putting parenthesis to the right of the brackets SHOULD call its methods (`object[method]()`)
  - the book says it doesn't but someone in class said this and it worked when ray tried it
- kind of a thing here... how are we supposed to apply differing tags to each new object/element when it's created dynamically? meaning i dont know of any way to add an id/class/differing object name. I gues we could use a function to add a specific object name:
```
object.name = prompt('type name of object');
```
  - placed in a form and using a text box instead of `prompt`
- so there are js tools to change attributesthen?
