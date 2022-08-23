# Add/Remove

This is a simple combination of css rules for adding a toggleable button that represents add and remove without the need of JavaScript. Since this is all
Though I have not done much extensive testing, all of the features should work in IE9+ and vendor prefixes are added for Safari and IE support.

To use make a checkbox plus label combo and then add the class you want to use

```
<input type="checkbox" class="add-remove" id="add"/>
<label for="add"></label>
```

**Don't forget to use an id in the input and match it with the ```for``` attribute in the label**

### Remove-Add vs Add-Remove

I have included 2 separate classes for styling checkboxes because I wanted to allow for easy handling of making the default to either be add or remove instead of requiring that the inputs be checked in order to get the desired result.
If you only want one, then you can simply and safely delete all the rules that begin as ```input.add-remove``` or ```input.remove-add```.

### Further Styling
The elements themselves scale very well based on the width and height in the label and changing colors is very easy as well. 

----------

An example and overview can be found here: http://theshrouded.com/wp/?p=16

Inspired by [cdflynn's Android crossview](https://github.com/cdflynn/crossview)
