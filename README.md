Keeping it classy
Classes are useful when you have a bunch of elements that should all receive the same styling. Rather than applying the same rules to several selectors, you can simply apply the same class to all those HTML elements, then define the styling for that class in the CSS tab.

Classes are assigned to HTML elements with the word class and an equals sign, like so:

<div class="square"></div>
<img class="square"/>
<td class="square"></td>
Classes are identified in CSS with a dot (.), like so:

.square {
    height: 100px;
    width: 100px;
}
This allows you to take elements of different types and give them the same styling.

Instructions
Create any number of HTML elements you like and give them the class "fancy". On the CSS tab, set .fancy to have a font-family of cursive and a color of #0000CD.
