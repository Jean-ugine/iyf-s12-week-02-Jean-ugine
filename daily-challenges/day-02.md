# Day 2: Create a Card Component

## Objective
Create a reusable card component using HTML and CSS.

## What I Built
I created a card to display information about a web development project. The card includes a title, description, and button.

## HTML

```html
<article class="card">
  <h2>My Web Development Journey</h2>
  <p>I am learning HTML and CSS to build responsive websites.</p>
  <a href="projects.html" class="card-button">View Projects</a>
</article>
```

## CSS

```css
.card {
  max-width: 350px;
  padding: 24px;
  margin: 20px auto;
  background-color: #ffffff;
  border: 1px solid #d8dee8;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08);
}

.card h2 {
  margin-bottom: 12px;
  color: #234e70;
}

.card p {
  margin-bottom: 18px;
  line-height: 1.6;
}

.card-button {
  display: inline-block;
  padding: 10px 16px;
  color: white;
  background-color: #234e70;
  text-decoration: none;
  border-radius: 6px;
}

.card-button:hover {
  background-color: #e07a5f;
}
```

## What I Learned
- How to structure a card using semantic HTML.
- How padding, margins, borders, and border-radius affect appearance.
- How to style links as buttons.
- How hover states improve user interaction.

## Status
Completed.
