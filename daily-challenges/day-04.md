# Day 4 — Hero Section Styling

## What I practised
- Creating a clear introductory section.
- Using padding and spacing to organise content.
- Applying CSS variables for consistent colours.
- Making a hero section responsive.

## What I learned
A hero section introduces a website and helps visitors understand its purpose. Clear headings, readable text, and a useful call-to-action link can improve the experience.

## CSS example

```css
.hero-demo {
    padding: 48px 20px;
    background-color: var(--color-primary);
    color: white;
    text-align: center;
    border-radius: 12px;
}

.hero-demo h1 {
    margin-bottom: 16px;
}

.hero-demo p {
    max-width: 650px;
    margin: 0 auto 20px;
    line-height: 1.6;
}

.hero-demo a {
    display: inline-block;
    padding: 10px 16px;
    border-radius: 6px;
    background-color: var(--color-surface);
    color: var(--color-primary);
}

.hero-demo a:focus-visible {
    outline: 3px solid var(--color-accent);
    outline-offset: 4px;
}
```

## What I will improve
I will practise building introductions that remain readable on small screens.
