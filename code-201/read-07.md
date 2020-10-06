- based on my inability to call a method by function name instead of key name and the similar structure of functions provided in the article I know there's something important to be learned here but I can't quite understand what it is. Using words like instantiate sure doesn't help (even with the dictionary definition I don't understand what it's trying to say).
- what exactly does it mean by "instances"? is it refering to how many times something shows up/is used? Is there some other source I can get this info from cause this isn't making any sense to me.
- `<table>` - creates a table
- `<tr>` - creates a row
- `<th>` - creates a heading for a row or column
- `<td>` - creates a data block in the row
- all together used:

```
<table>
  <tr>
    <th>empty block for row titles</th>
    <th>first column heading</th>
    <th>second column heading</th>
  </tr>
  <tr>
    <th>title for row</th>
    <td>table data</th>
    <td>table data</th>
  </tr>
</table>
```

- attribute `colspan="2"` added to td tag allows a data block to stretch across 2 columns representing belonging in both. This data block belongs to 2 columns changing the 2 to a 3 would make it belong to 3 columns: `<td colspan="2">`

- The same works for rowspan. The data box would belong to 2 rows and 1 column.
- column head tags should be kept in a `<thead>` tag, rows should be kept in `<tbody>` tags and results (sum, difference, product, etc) should be kept in `<tfoot>` tag.
- changing col/row width, spacing, border and background-color can give an extra professional 3D-esque look and can be done in HTML but can I do it in css?
- is `var car = {}` the same as `var car = new object()`? is the second one just a version of object creation that you can more easily use in a function?
- using lines like `car.name = Matt;` creates a property or method for the selected object
- to save consumer input do we have to save it as a key/value pair somewhere?
- can I use a perameter in place of a var name to allow the user to create the object name?
- to change value of an existing key use `car.name = matt;` or `car['name'] = matt;` again where car references the object name, name references the key name and matt is the new value to be assigned. brackets can be used for properties but not methods. leaving the new value an empty string replaces the previous data with an empty string.
- `delete car.name` removes the chosen property from the chosen object.
- using this instead of object name in dot notation indicates the following values will be part of the object created by the following constructor function:

```
function Hotel(name, rooms, booked) {
  this.name = name;
  this.rooms = rooms;
  this.booked = booked;
  this.checkAvailability = function() {
    return this.rooms - this.booked;
  };
}
```

- `var objectName = new Hotel(object, 20, 0);` to define(not create) a new object named 'objectName'.
- values are provided when function is called
- semi-colon outside of existing object
- use new when using function to create object. elaborate?