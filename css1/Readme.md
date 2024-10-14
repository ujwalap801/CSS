# 1. Internal CSS:

## Internal CSS is written within the <style> tag inside the <head> section of an HTML document. It is used to apply styles to a single HTML file.


 <style>
        body {
            font-family: Arial, sans-serif;
        }
        h1 {
            color: blue;
        }
        p {
            color: green;
        }
    </style>

# 2. External CSS:

## External CSS is written in a separate .css file and linked to the HTML document using a <link> tag in the <head> section. This is the most commonly used method for larger projects or websites.

 <link rel="stylesheet" href="styles.css">


# 3. Inline CSS
## Inline CSS is a method where CSS styles are applied directly to individual HTML elements using the style attribute within the element tag. This method is useful for applying specific styles to a single element without affecting other parts of the document.


   <h1 style="color: blue; font-size: 24px;">This is a heading</h1>