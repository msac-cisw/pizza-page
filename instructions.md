# Pizza Page Instructions

Use this guide to build a simple HTML page that presents all four pizza types, uses all four pizza images, connects a CSS file, and then asks AI to help create a visual style.

## 1. Create the Project Files

Create two files in your project folder:

- `index.html`
- `style.css`

Use all four pizza images from this repo:

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
  <title>The Magic of Pizza</title>
</head>
<body>

</body>
</html>
```

Open the file in your browser. At this point, the page should be blank.

## 3. Add All Pizza Information and Images

Use the text from [Pizza Information](pizza-information.md). Inside the `<body>` tags, add a main page heading, an introduction, and one section for each pizza type.

```html
<h1>The Magic of Pizza</h1>

<p>
  There are many different ways to enjoy your pizza. Here are four distinct
  types offering a glimpse into the flavorful and fun world of pizzas.
</p>

<section>
  <h2>Neapolitan Pizza</h2>

  <img src="neopolitan.png" alt="A Neapolitan pizza">

  <p>
    Originating from Naples, Italy, Neapolitan pizza is often considered the
    original and most traditional form. It features a thin, soft crust with a
    delightfully puffy edge, known as the "cornicione." Due to strict guidelines,
    authentic Neapolitan pizza uses specific ingredients like San Marzano
    tomatoes and Mozzarella di Bufala Campana. It's typically baked at very high
    temperatures in a wood-fired oven for a short period, resulting in a slightly
    charred, bubbly crust and a fresh, simple flavor. Common varieties include
    the Margherita, with tomato, mozzarella, fresh basil, and olive oil, and the
    Marinara, with tomato, garlic, oregano, and olive oil.
  </p>
</section>

<section>
  <h2>New York-Style Pizza</h2>

  <img src="newyork.png" alt="A New York-style pizza">

  <p>
    A giant of the American pizza scene, New York-style pizza is characterized by
    its large, thin, and foldable slices. This style evolved from Neapolitan
    pizza, adapted by Italian immigrants in New York City. The crust is typically
    hand-tossed, resulting in a crispy edge and a chewy interior that's sturdy
    enough to be eaten on the go. Often sold in wide slices, it's traditionally
    topped with a layer of tomato sauce and a generous amount of shredded,
    low-moisture mozzarella cheese. Pepperoni is a classic topping, but
    New York-style pizzas can accommodate a wide variety of additional
    ingredients.
  </p>
</section>

<section>
  <h2>Chicago Deep-Dish Pizza</h2>

  <img src="chicago.png" alt="A Chicago deep-dish pizza">

  <p>
    As its name suggests, Chicago deep-dish pizza is known for its incredibly
    thick crust, which is baked in a round, high-sided pan similar to a cake pan.
    This creates a deep basin that allows for a large volume of toppings. Unlike
    other pizzas, the ingredients are layered in reverse order: the crust is lined
    with mozzarella cheese, followed by toppings like Italian sausage, pepperoni,
    and vegetables, and then finished with a chunky tomato sauce on top. The
    baking time is significantly longer than for thin-crust pizzas, resulting in
    a rich, hearty, and almost casserole-like meal.
  </p>
</section>

<section>
  <h2>Sicilian Pizza</h2>

  <img src="sicilian.png" alt="A Sicilian pizza">

  <p>
    Hailing from Sicily, Italy, this style typically features a thick, airy, and
    rectangular crust that is often baked in a well-oiled pan, giving the bottom a
    distinctively crisp and slightly fried texture. Sicilian pizza is known for
    its spongy dough and is traditionally topped with a robust tomato sauce,
    onions, anchovies, and herbs, often with less cheese than other styles, or
    sometimes no cheese at all. In America, Sicilian-style pizza often has a
    thicker layer of mozzarella cheese and a variety of other toppings, but it
    retains its characteristic rectangular shape and thick, focaccia-like crust.
  </p>
</section>
```

Your full `index.html` should now look similar to this:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>The Magic of Pizza</title>
</head>
<body>
  <h1>The Magic of Pizza</h1>

  <p>
    There are many different ways to enjoy your pizza. Here are four distinct
    types offering a glimpse into the flavorful and fun world of pizzas.
  </p>

  <section>
    <h2>Neapolitan Pizza</h2>

    <img src="neopolitan.png" alt="A Neapolitan pizza">

    <p>
      Originating from Naples, Italy, Neapolitan pizza is often considered the
      original and most traditional form. It features a thin, soft crust with a
      delightfully puffy edge, known as the "cornicione." Due to strict
      guidelines, authentic Neapolitan pizza uses specific ingredients like San
      Marzano tomatoes and Mozzarella di Bufala Campana. It's typically baked at
      very high temperatures in a wood-fired oven for a short period, resulting
      in a slightly charred, bubbly crust and a fresh, simple flavor. Common
      varieties include the Margherita, with tomato, mozzarella, fresh basil, and
      olive oil, and the Marinara, with tomato, garlic, oregano, and olive oil.
    </p>
  </section>

  <section>
    <h2>New York-Style Pizza</h2>

    <img src="newyork.png" alt="A New York-style pizza">

    <p>
      A giant of the American pizza scene, New York-style pizza is characterized
      by its large, thin, and foldable slices. This style evolved from
      Neapolitan pizza, adapted by Italian immigrants in New York City. The crust
      is typically hand-tossed, resulting in a crispy edge and a chewy interior
      that's sturdy enough to be eaten on the go. Often sold in wide slices, it's
      traditionally topped with a layer of tomato sauce and a generous amount of
      shredded, low-moisture mozzarella cheese. Pepperoni is a classic topping,
      but New York-style pizzas can accommodate a wide variety of additional
      ingredients.
    </p>
  </section>

  <section>
    <h2>Chicago Deep-Dish Pizza</h2>

    <img src="chicago.png" alt="A Chicago deep-dish pizza">

    <p>
      As its name suggests, Chicago deep-dish pizza is known for its incredibly
      thick crust, which is baked in a round, high-sided pan similar to a cake
      pan. This creates a deep basin that allows for a large volume of toppings.
      Unlike other pizzas, the ingredients are layered in reverse order: the
      crust is lined with mozzarella cheese, followed by toppings like Italian
      sausage, pepperoni, and vegetables, and then finished with a chunky tomato
      sauce on top. The baking time is significantly longer than for thin-crust
      pizzas, resulting in a rich, hearty, and almost casserole-like meal.
    </p>
  </section>

  <section>
    <h2>Sicilian Pizza</h2>

    <img src="sicilian.png" alt="A Sicilian pizza">

    <p>
      Hailing from Sicily, Italy, this style typically features a thick, airy,
      and rectangular crust that is often baked in a well-oiled pan, giving the
      bottom a distinctively crisp and slightly fried texture. Sicilian pizza is
      known for its spongy dough and is traditionally topped with a robust tomato
      sauce, onions, anchovies, and herbs, often with less cheese than other
      styles, or sometimes no cheese at all. In America, Sicilian-style pizza
      often has a thicker layer of mozzarella cheese and a variety of other
      toppings, but it retains its characteristic rectangular shape and thick,
      focaccia-like crust.
    </p>
  </section>
</body>
</html>
```

Refresh the browser. You should see all four pizza sections on a plain page.

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
  <title>The Magic of Pizza</title>
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

section {
  margin: 40px 0;
}

h2 {
  font-size: 32px;
}

img {
  max-width: 100%;
  width: 500px;
  border-radius: 8px;
}

p {
  font-size: 20px;
  line-height: 1.6;
  max-width: 800px;
}
```

Refresh the browser again. The page should now have basic styling.

## 6. Ask AI for a Style Idea

Once your plain page works, use AI to help create a stronger visual design.

Try a prompt like this:

```text
I have a simple HTML page about four pizza styles: Neapolitan, New York-style,
Chicago deep-dish, and Sicilian. Each section has an h2, image, and paragraph.
Create CSS that makes the page look like a bold pizzeria menu poster.
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
