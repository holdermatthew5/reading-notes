- if I do `((3 > 2) && (3 < 2) || (1 < 2))` will it evaluate true since one of the 2 attatched to `||` are true and the far left is true? If not will it evaluate false since 3 !< 2? Can I make it check the left 2 first by putting them in parenthesis and then check the result to the right side since PEMDAS exists? what can this form of equation be used for in larger examples? can this be used to form AI? or faster if then statements?
- `==` - is equal to
- `===` - is trictly equal to (numbers v strings)
- `!=` = is not equal to
- `!==` - is not strictly equal to
- `<` - left less than right
- `>` - left greater than right
- `<=` - left less than or equal to right
- `>=` - left greater than or equal to right
- `&&` - logical 'and'
- `||` - logical 'or'
- `!` - logical 'not'
- `+=` means to add meaning to the end of the assigned meaning. aka:
```
msg = msg + 'new content';
```
- this code block (a for loop)
```
for (var i = 0; i < 10; i++) {
    document.write(i);
}
```
- writes the value of i then adds 1 to the value of i until the value of i reaches 10. for that reason it will return 0 1 2 3 4 5 6 7 8 and 9 but not 10 or any higher.
- this could be used to automatically run a code block to fix a bug once detected (if (bug is present) evaluates true) evaluates true being the key word. If it doesn't work the first time it's okay because it works a limited number of times and can switch to another code block to test a different solution.
- a while loop is useful if you don't know how many times the code block should be run, but can be specified to run a set number of times as well.
- assuming the issue isn't too complex putting a for loop inside a while loop could form a sort of self healing code which changes it's own variables to suit the needs of the machine it's run on.
- do while is the same as a while loop except that do while will run the code block it contains at least once even if it's parameters evaluate false. this could be useful in checking applications when they are downloaded to make sure they do not contain malware. the malware would not provide an immediate adverse effect so the statement (malware is present) would evaluate false, but it's best to check anyway so the do while loop would check the app and potentially stop the app from installing the malware or stop the malware from affecting the device it's downloaded to.
- the parameters to these loops do not have to be contained within the loops code block.
- loop - 
- while true - loop over code
- for - for a certain number of times
- iterate - each time it loops
- condition - think of conditional statements (while (true && true) || false)
- increment - increase possibly by one
- decrement - increase possibly by one