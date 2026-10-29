# Day 5 — Form and Footer Styling

## What I practised
- Styling form fields and labels.
- Adding consistent spacing between form elements.
- Styling a footer to match the rest of the website.
- Keeping keyboard focus visible.

## What I learned
Well-organised forms help users understand what information to enter. A consistent footer gives a website a clear ending and can contain copyright information or useful links.

## CSS example

```css
.form-demo label {
    display: block;
    margin-bottom: 6px;
    font-weight: bold;
}

.form-demo input,
.form-demo textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid var(--color-border);
    border-radius: 6px;
    font: inherit;
}

.form-demo input:focus-visible,
.form-demo textarea:focus-visible {
    outline: 3px solid var(--color-accent);
    outline-offset: 2px;
}

.footer-demo {
    margin-top: 32px;
    padding: 20px;
    background-color: var(--color-primary);
    color: white;
    text-align: center;
}
```

## What I will improve
I will practise making forms accessible and keeping page sections visually consistent.
