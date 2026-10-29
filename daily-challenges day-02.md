# Day 2 — Button Styling

## What I practised
- Styling a button with CSS.
- Adding padding, borders, and rounded corners.
- Creating a hover effect.
- Keeping keyboard focus visible.

## What I learned
A clear hover state helps users recognise an interactive element. A visible focus state is also important for people navigating with a keyboard.

## CSS example

```css
.button-demo {
    padding: 10px 16px;
    border: 2px solid var(--color-primary);
    border-radius: 6px;
    background-color: var(--color-primary);
    color: white;
    cursor: pointer;
}

.button-demo:hover {
    background-color: var(--color-accent);
}

.button-demo:focus-visible {
    outline: 3px solid var(--color-accent);
    outline-offset: 3px;
}
```

## What I will improve
I will practise applying consistent button styles across my pages.
