# floatpractice
Float Practice Assignment

Live Site: https://mroberts70.github.io/floatpractice/

Notes:

- Notice in the main, how each set of image + corresponding text is enclosed in < div > tags. Also notice that the opening < div > tag has a class="clearfix"
- Notice in the < style > section, found within the < head > of the index.html, there is a rule block for the "div" tag that clears both floats:

<pre>div {
     clear: both;
}</pre>

That is a required minimum step necessary to complete this assignment. But to really do it right, you should also search for and copy/paste a correctly formatted "clearfix" class into your code. You can then add this class name to the opening div tags in your html:

<pre>< div class="clearfix"></pre>

This does make the "clear: both" property that we did first redundant, so if you do include the clearfix, you can delete the clear: both from the div rule block. However this is not a requirement. 

- Notice that you can now add space between your sets of image+text by adding a margin-bottom to the div rule block. This wasn't possible without the clearfix class. 
- To "search" for the correctly formatted "clearfix" class, open a new browser tab and do a search for "CSS Clearfix" - you will come up with several, all variations on the same theme. I personally like the simplicity of the W3Schools one

Clearfix:
<pre>.clearfix::after {
  content: "";
  clear: both;
  display: table;
}</pre
