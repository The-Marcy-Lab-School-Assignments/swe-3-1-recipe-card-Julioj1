# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: HTML Structure

What is the difference between the `<head>` and `<body>` sections of an HTML document? What kind of content goes in each?

**Your Answer:** The `<head>` section contains information about the webpage, such as the title, meta data, links to CSS files, and scripts. This content is not displayed directly on the page. The `<body>` section contains all the visible content of the webpage, including text, images, buttons, and other elements that users interact with.

## Question 2: Semantic HTML

Why should we use semantic elements like `<header>`, `<main>`, and `<footer>` instead of using `<div>` tags for everything?

**Your Answer:** Semantic elements like `<header>`, `<main>`, and `<footer>` describe the meaning and structure of the content they contain. They make the HTML easier to read and understand for developers, screen readers, and search engines. Using semantic HTML improves accessibility and SEO compared to using generic `<div>` tags for everything.

## Question 3: CSS Selectors

Given the following HTML:

```html
<ul>
  <li class="vegetable">Carrots</li>
  <li class="vegetable">Broccoli</li>
  <li class="fruit" id="favorite">Mango</li>
</ul>
```

Write THREE different CSS rules:

1. One that makes ALL list items have a `yellow` background
2. One that makes only the vegetables have `green` text color
3. One that makes only the Mango `bold`

**Your Answer:**

```css
/* 1. All list items have a yellow background */
li {
  background-color: yellow;
}

/* 2. Only vegetables have green text */
.vegetable {
  color: green;
}

/* 3. Only Mango is bold */
#favorite {
  font-weight: bold;
}
```

## Question 4: The Box Model

In your own words, explain the four parts of the CSS box model (content, padding, border, margin). What is the purpose of each part?

**Your Answer:** The content is the actual text or image inside an element. Padding is the space between the content and the border, while the border wraps around the padding and content. Margin is the space outside the border that separates the element from other elements. Together, these parts control spacing and layout on the page.

## Question 5: Box-Sizing

What problem does `box-sizing: border-box` solve? Why do we include it in a CSS reset at the top of our CSS files?

**Your Answer:** `box-sizing: border-box` ensures that padding and borders are included in an element’s total width and height. Without it, elements can become larger than expected and break layouts. We include it in a CSS reset to make sizing more predictable and consistent across all elements.

## Question 6: Display Property

What is the difference between `display: block`, `display: inline`, and `display: inline-block`? Give an example of when you might use `inline-block`.

**Your Answer:** `display: block` elements take up the full width and start on a new line, while `display: inline` elements only take up as much space as their content and do not accept width or height. `display: inline-block` allows elements to sit inline while still allowing width, height, and margin. Inline-block is useful for things like buttons in a navigation bar.
