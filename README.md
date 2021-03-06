# Removing duplicates from an array
**JavaScript**: removing duplicated elements in an array without sorting them.

## Usage

```javascript
r_d(the_array)
```

It's recommended to use the latest [remove_duplicate_shorter.js](https://github.com/monkeyraptor/remove_duplicates/blob/master/remove_duplicate_shorter.js)

That version won't change the original order of the array elements.

## Example
```javascript
var array = [1, 2, 3, 4, "doo", "dee", "doo", "♪", "doo"],
    trimmed = r_d(array);

// *trimmed* variable output will be an array.
// It consists of [1, 2, 3, 4, "doo, "dee", "♪"]
```

## Additional
The `"remove_duplicate_obj.js"` version will return the **sorted array**.

It will also **return an array without the duplications**.

The 1st version (longer snippet) was the initial tinkering. It has the same output as the `"shorter"` version but has longer lines of code.

## Idea explanation (JavaScript) and Python snippet

1. Kinda an explanation on <a href="http://monkeyraptor.johanpaul.net/2015/04/javascript-removing-same-elements-in.html" target="_blank" title="new window">Monkey Raptor</a>.

2. Python equivalency post on <a href="http://monkeyraptor.johanpaul.net/2015/04/python-removing-same-elements-in-array.html" target="_blank" title="new window">Monkey Raptor</a>.
