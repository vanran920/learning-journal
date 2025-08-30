🧱 1. <!DOCTYPE html> — Document Type Declaration
Tells the browser that the document uses HTML5.

Must be the very first line in the file.
**Example**
html
<!DOCTYPE html>


🌐 2. <html> — Root Element
Wraps the entire HTML content.

All other elements are nested inside this.
**Example**
html
<html lang="en">
  ...
</html>


🧠 3. <head> — Metadata Section
Contains information about the document (not visible on the page).

Includes:

<title>: Page title (shown in browser tab)

<meta>: Character encoding, viewport settings, SEO tags

<link>: External CSS files

<script>: External JS files (can also go in <body>)

 **Example** 
html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Web Page</title>
  <link rel="stylesheet" href="styles.css">
</head>

  

  📄 4. <body> — Visible Content
Everything inside <body> is rendered on the webpage.
Includes:

Headings (<h1> to <h6>)

Paragraphs (<p>)

Images (<img>)

Links (<a>)

Lists, tables, forms, buttons, etc.
  <h1>Hello, Vansh!</h1>
  <p>This is your first HTML page.</p>
</body>
