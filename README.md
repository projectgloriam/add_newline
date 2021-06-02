# add_newline
Adds a line break after a specified number of periods. Creates paragraphs as well. This is a jQuery plugin. 
By default it skips exceptions like " Mr."," Mrs.", " Dr.", ".com", " P.O.", " St.", " Ms.", " www.", ".org". You can add other exceptions as well.

## To use this plugin

```
<script type="text/javascript" src="jquery.js"></script>

<script type="text/javascript" src="add_newline.js"></script>
```
Place this 
`````````
$(function() {
  $("#test_element").add_newline({
      find: ".",
      replaceWith: ".</br>",
      paragraph: 0,
      otherExceptions: []
  });
});

`````````
