# PopUpJS

PopUpJS is a basic JavaScript file designed to simplify style changes for objects with minimal coding through the use of functions. Make sure it is in the same directory or in the directory's subdirectories.

### Functions:

- `ShowPopUp(ObjectID, DisplayType)`: Changes the display attribute of an object using its ID.

- `HidePopUp(PopUpID)`: Hides an object using its ID.

- `ChangeInnerText(TextID, Text)`: Changes the text in a text object using its ID.

- `ChangeInnerHTML(PopUpID, HTML)`: Changes the inner HTML of an object using its ID.

- `ChangeBackgroundColor(PopUpID, Color)`: Changes the background color of an object using its ID.

- `ChangeTextFont(PopUpID, Font)`: Changes the font of a text object using its ID.

- `ChangeStyle(PopUpID, StyleData)`: Allows advanced editing of an object's style data using its ID.

### Usage Example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PopUp Examples</title>
</head>
<body>
    <h1 id="PopUpText" style="display: none;">Hello</h1>
    <button onclick="ShowPopUp('PopUpText', 'block')">Hello</button>

    <script src="PopUp.js"></script>
</body>
</html>
