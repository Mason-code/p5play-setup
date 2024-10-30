<!-- the readme is written in markdown -->
# Setup Steps

## 1. Create the Project Folder

1. Make a new folder for your project.
2. Inside this folder, create two files:
   - **An HTML file** (e.g., `index.html`)
   - **A JavaScript file** (e.g., `game.js`)

## 2. Set Up the HTML File

In `index.html`, add the following basic structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>p5.play Project</title>
  <!-- Load p5.js library -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.4.0/p5.js"></script>
  <!-- Load p5.play library -->
  <script src="https://cdn.jsdelivr.net/npm/p5.play/lib/p5.play.js"></script>
  <!-- Link to your main game file -->
  <script src="game.js" defer></script>
</head>
<body>
</body>
</html>
```

## 3. Write Your p5 Code

Add your code in game.js, for example:

```js
function setup() {
  createCanvas(400, 400);
  background(200);
}

function draw() {
  // Your game code goes here
}
```
