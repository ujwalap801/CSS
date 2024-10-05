## CSS text styling properties with definitions and examples:

# color:

Definition: Specifies the color of the text. You can use color names, hex codes, RGB, or HSL values.
Example:
p {
  color: blue;
}

This will change the text color to blue.

# text-align:

Definition: Specifies the horizontal alignment of the text within its container. It can be set to values like left, right, center, or justify.
Example:

h1 {
  text-align: center;
}
This centers the text horizontally.

# text-decoration:

Definition: Adds decorations to text, such as underlines, overlines, or strike-throughs.
Example:

a {
  text-decoration: underline;
}
This adds an underline to the text (commonly used with links).

# text-transform:

Definition: Controls the capitalization of text. Options include uppercase, lowercase, or capitalize.
Example:
p {
  text-transform: uppercase;
}
This will convert all text to uppercase letters.

# text-shadow:

Definition: Applies shadow effects to text. The values define the horizontal and vertical shadow positions, blur radius, and shadow color.
Example:
h2 {
  text-shadow: 2px 2px 5px grey;
}
This adds a grey shadow 2 pixels to the right and 2 pixels down, with a blur of 5 pixels.

# line-height:

Definition: Sets the space between lines of text. It can be specified as a unit (e.g., px, em) or as a multiplier (e.g., 1.5).
Example:
p {
  line-height: 1.5;
}
This will increase the line spacing to 1.5 times the default line height.

# letter-spacing:

Definition: Sets the amount of space between letters in a text. It can be useful for adjusting the appearance of text.
Example:
h1 {
  letter-spacing: 2px;
}
This adds 2 pixels of space between each letter in the heading.

# word-spacing:

Definition: Sets the space between words in a text. It helps control the distance between words for readability or styling.
Example:
p {
  word-spacing: 5px;
}
This adds 5 pixels of space between words.

# font-size:

Definition: Sets the size of the text. It can be defined in various units like px, em, rem, or percentages.
Example:
p {
  font-size: 16px;
}
This sets the font size to 16 pixels.

# font-family:

Definition: Defines the typeface (or font) for the text. You can list several fonts as fallbacks, in case the first font is unavailable.
Example:
body {
  font-family: 'Arial', sans-serif;
}
This sets the font to Arial, with a fallback to a generic sans-serif font.

# font-style:

Definition: Specifies the style of the font. Common values include normal, italic, and oblique.
Example:

p {
  font-style: italic;
}
This makes the text italic.

# font-weight:

Definition: Sets the thickness (weight) of the text. Values can be normal, bold, lighter, or a numeric value like 100, 400, 700, etc.
Example:

h1 {
  font-weight: bold;
}
This makes the text bold.


# Each of these properties plays a key role in controlling the visual appearance of text on a webpage.