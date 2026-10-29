# Day 3 — Card Styling

## What I practised
- Using padding and margins to create space.
- Adding a border, rounded corners, and a shadow.
- Organising content inside a card.
- Using CSS variables for consistent colours.

## What I learned
A card groups related information into a clear, reusable component. Consistent spacing and subtle borders help make content easier to read.

## CSS example

```css
.card-demo {
    padding: 20px;
    border: 1px solid var(--color-border);
    border-radius: 10px;
    background-color: var(--color-surface);
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
}

.card-demo h2 {
    color: var(--color-primary);
    margin-bottom: 12px;
}
```

## What I will improve
I will practise reusing card styles across project sections while keeping the layout responsive.
