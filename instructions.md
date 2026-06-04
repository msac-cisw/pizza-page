# Pizza Page Instructions

Use this guide to build a simple HTML page about one type of pizza, add an image, connect a CSS file, and then ask AI to help create a visual style.

## 1. Create the Project Files

Create two files in your project folder:

- `index.html`
- `style.css`

Your folder can also include one pizza image from this repo:

- `neopolitan.png`
- `newyork.png`
- `chicago.png`
- `sicilian.png`

## 2. Create the HTML Document

Open `index.html` and add the basic HTML structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pizza Page</title>
</head>
<body>

</body>
</html>
```

Open the file in your browser. At this point, the page should be blank.

## 3. Add the Pizza Type, Information, and Graphic

Choose one pizza type from the README or write your own description. Add a heading, image, and paragraph inside the `<body>` tags.

This example uses New York-style pizza:

```html
<h1>New York-Style Pizza</h1>

<img src="newyork.png" alt="A New York-style pizza">

<p>
  New York-style pizza is known for its large, thin, foldable slices.
  The crust is crisp on the outside and chewy inside, making it easy
  to eat by hand while walking through the city.
</p>
```

Your full `index.html` should now look similar to this:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pizza Page</title>
</head>
<body>
  <h1>New York-Style Pizza</h1>

  <img src="newyork.png" alt="A New York-style pizza">

  <p>
    New York-style pizza is known for its large, thin, foldable slices.
    The crust is crisp on the outside and chewy inside, making it easy
    to eat by hand while walking through the city.
  </p>
</body>
</html>
```

Refresh the browser. You should see your title, image, and paragraph on a plain page.

## 4. Link the CSS File

To style the page, connect `style.css` to `index.html`.

Add this line inside the `<head>` section:

```html
<link rel="stylesheet" href="style.css">
```

Your `<head>` section should now look like this:

```html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pizza Page</title>
  <link rel="stylesheet" href="style.css">
</head>
```

## 5. Add Starter CSS

Open `style.css` and add a few rules:

```css
body {
  font-family: Arial, sans-serif;
  margin: 40px;
  background: #fff7ed;
  color: #2f1b12;
}

h1 {
  font-size: 48px;
}

img {
  max-width: 100%;
  width: 500px;
  border-radius: 8px;
}

p {
  font-size: 20px;
  line-height: 1.6;
  max-width: 700px;
}
```

Refresh the browser again. The page should now have basic styling.

## 6. Ask AI for a Style Idea

Once your plain page works, use AI to help create a stronger visual design.

Try a prompt like this:

```text
I have a simple HTML page about New York-style pizza with an h1, image, and paragraph.
Create CSS that makes it look like a bold pizzeria menu poster.
Use warm colors, strong typography, good spacing, and make the page responsive.
Only give me CSS for style.css.
```

You can change the style idea. For example, ask for:

- a fancy Italian restaurant menu
- a comic book pizza ad
- a modern food blog
- a vintage travel poster
- a sports bar menu board

## Example Outcome

Your page does not need to match this exactly. This is one possible finished style:

![Example Pizza Page](example.png)
