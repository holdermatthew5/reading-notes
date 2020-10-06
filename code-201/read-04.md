- `<a href='url'>link text</a>` - a == link opening/closing tag, href == holds the URL that will be assigned to this link, link text == what will be visible to user. Can be placed inside list elements for adding navigation bars/recommendations or p elements for adding links to content.
- full URL (www.url.com) is an absolute URL (displays domain name), reference to internal page (index.html) is a relative url (does not need domain name just a proper path through the directory).
- URL == Uniform Resource Locator. Contains domain name and path to selected page.
- child of a child is also called grandchild
- where are the css and js files in the example? we have a whole other folder for each but it seems like they reserve folders for sections of the site and put several htmls in each folder. is this just dated to when css and js were still put in the html file or do we form files in folders in folders? cause that seems a little excessive. Is there a reson we put a js file in a js folder? do we put all html files together all css files together and all js files together? if so is that just a thing that changes with each company you go to?
- linking files here works the same as in ubuntu? `../102/` would link to my 102 parent folder even here (assuming it was actually loaded into the site map)?
- mailto: starts the users email program and adresses an email to the specified email address. This is used in an href attribute of an a tag so it can be labelled however you please and still link to the right email address.
- target='_blank' attribute to a tag opens link in new window. when doing this the user should be warned that the link will open in a new window.
- to link to a specific part of the same page use element id in href (href='#elementId'). to link to a specific part of a different site ensure that part has an id and add it to the end of the url in the href after a # (href='www.url.com/example/#elementId').
- after reading 363-364 I thought that in order to fix the text/h1 issue I've been ignoring I could just put it inside a parent element with the element I'm trying to put it next to then target the p/h1 to be centered in the parent element rather than just trying to position them next to eachother without them being connected by anything other than the body or main but then I remembered that they're in the same article. should I maybe put inline-block in the article then try to target p/h1 to center it and the images to align them left? if so how can I align them left? float left?
- to make things go into normal flow without any other css affecting it the syntax would be `position: static;` but the browser does this for you automatically unless you specify otherwise.
- to position things based on the position they would be in normal flow the syntax is:
```
selector {
  position: relative;
  top: 0px;
  right: 0px;
  bottom: 0px;
  left: 0px;
}
```
Here the element is not moved but changing the 0's next to px would change it's position in the direction to the left of the changed 0.
- position: absolute changes position on screen not affecting other elements at all so they'll appear on top or under the affected element. Does this mean it won't leave its spot even after scrolling? Is this how ads cover content?