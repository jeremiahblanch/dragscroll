dragscroll
==========

Dragscroll is a micro JavaScript library (734 bytes minified) which
enables scrolling via holding the mouse button ("drag and drop" or
"click and hold" style, [online
demo](http://asvd.github.io/dragscroll/)).


### Usage


Download the and unpack
[distribution](https://github.com/asvd/dragscroll/releases/download/v0.0.5/dragscroll-0.0.5.tar.gz),
or install it using [Bower](http://bower.io/):

```sh
$ bower install dragscroll
```

Load the `dragscroll.js` in a preferable way (that is an UMD module):

```html
<script src="path/to/dragscroll.js"></script>
```

Add the `dragscroll` class to a scrollable element:

```html
<div class=dragscroll>
    Big text goes here...
</div>
```

That's it! Now you can scroll it by dragging. You can also add the
`dragscroll` class to the `<body>` element and drag the whole page.

Keep in mind that now it is not possible to select the content with
mouse, so apply the `cursor: default;` CSS style to prevent confusing
the users (or even `cursor: grab;` in case the content is not a text).

If you add or remove the `dragscroll` class dynamically, invoke
`dragscroll.reset()` to update the listeners.

-

Follow me on twitter: https://twitter.com/asvd0
