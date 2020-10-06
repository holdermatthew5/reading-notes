# JavaScript Notes

- JavaScript - javascript is the "behavior level". It should be kept seperately from css and html where possible. It's main purpose is interactivity. One example being the sites ability to pull the date and time from the device it's being viewed on in order to display differing information. To be more clear; the example site views the devices date and time and determines that it is after 12pm and before 6pm so it display good afternoon instead of good morning or good evening.
- conditionals - a conditional is a command that depends on local circumstances. The conditional in this example is that "if it is after 0000 and before 1200 return good morning, if it is after 1200 and before 1800 return good afternoon and if it is after 1800 and before 0000 return good evening.
- operators - 
- datatypes
  - number - 42
  - boolien - true or false
  - string - "42" "forty-two" "" "any content mostly"
### code from do-along
```
var today = new Date();
var hourNow = today.getHours();
var greeting;

if (hourNow > 18) {
    greeting = 'Good evening!';
} else if (hourNow > 12) {
    greeting = 'Good afternoon!';
} else if (hourNow > 0) {
    greeting = 'Good morning!';
}

document.write('<h3>' + greeting + '</h3>');
```