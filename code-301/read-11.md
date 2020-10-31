## Video 2 Notes:

- Where is the Hello world coming from? I don't see that `console.log()` anywhere.
  - index.ejs file has h1 tag with it.

## Video 3 Notes:

- Does index.ejs file replace index.html?
- Is it not possible to use .html or is this just for the lesson?
- What would replace CSS and JavaScript?
- `<%= foo %>` means what now? It seems to be referencing a variable from the serfver.js file. It's from the `response.render()`.
- `Response.render()` takes in view, local varibales object, callback.
Video 4 Notes:
- `<%= %>` can take javaScript.
- The following code block will render lis for each object ( `[{name: 'dave'},{name: 'jerry}, ...]` ) in an array in response.render():

```
<ul>
  <% for(let person of people) { %>
    <% if (person.name === 'dave') { %>
      <li>This is definitely <%= object.key %>!!!</li>
    <% } else { %>
      <li> This is definitely not dave!!! This is <%= person.name %></li>
    <% } %>
  <% } %>
</ul>
```

## Video 5 Notes are changes to the above code.

## Video 6 Notes:

- adds about.ejs and layout.ejs.
- Will these be to seperate html js and css?
- Add layouts to express with `npm install --save express-ejs-layouts`.
- require()-ing 'express-ejs-layouts' allows you to use ^that^ layouts file by app.use()-ing that variable.
- so layout seems to be html, index js and about iiiss???

## Video 7 Notes:

- adds partials/onepartial to same directory as about, index and layout.
- adds `<%- include('partials/onepartial') %>` under `<%- body %>` and the h1 tag in partial/onepartial shows up on screen with the rest of the unstyled text.