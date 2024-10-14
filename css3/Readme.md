## class Attribute:
The class attribute is used to assign one or more classes to an HTML element.
It can be reused multiple times on different elements.


## id Attribute:
The id attribute assigns a unique identifier to an HTML element.
An id should be unique within a document, meaning you can only use it once.

## In CSS, class is selected using .classname and id using #idname



## Pixels (px): Absolute and fixed. Doesn't change based on anything.

## Accessibility: Pixels don't respect the user's browser settings. Many users adjust their default font size to improve readability, but pixel-defined fonts will not scale, making the text difficult to read for some people.



## em: Relative to the font size of the parent element. Can cause cascading scaling.

## rem: Relative to the root (html) font size, making it more predictable and consistent.

## 3em means  3 * 16px (3* parent pixel(if no parent element it takes a body element of 16px))

## 5rem means 5 * 16px (5 * root element pixel(head)) head element is the root element of all the elements


## problem with em
The cascading issue with em refers to how em units inherit and multiply relative to the font size of the parent element. This can cause unexpected results if you're not careful because each nested element's size will be based on the em value of its parent, rather than the root or body font size.


In contrast, rem avoids this problem by always being relative to the root element. This makes it easier to predict and manage font sizes without worrying about how the structure of the HTML will affect the appearance of text.