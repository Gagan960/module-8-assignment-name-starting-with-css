# module-8-assignment-name-starting-with-css

# CSS Priority Example

This project demonstrates the three main ways to add CSS to an HTML page:

1. **Inline CSS**: Added directly to an element using the `style` attribute.
2. **Internal CSS**: Defined within a `<style>` tag in the `<head>` section.
3. **External CSS**: Linked from an external `.css` file using the `<link>` tag.

## How CSS Priority Works

When multiple CSS rules target the same element, the priority is:

1. **Inline CSS** (highest)
2. **Internal CSS**
3. **External CSS** (lowest)

In this example, the `.box` div is styled by all three methods. The background color is set by each, but the inline style (`background-color: red;`) takes precedence, so the div appears with a red background.

## Files

- `Q1(starting with css).html` — The main HTML file.
- `styles.css` — The external CSS file (not shown here).

## Comments

Comments are included in the HTML and CSS to explain each section.

---

# Q2 (Starting with CSS)

This project demonstrates the use of class selectors in CSS to style multiple paragraphs, each with a unique class name, following the BEM (Block Element Modifier) naming convention.

## Files

- `Q2(starting with css).html`: The main HTML file containing the paragraphs and CSS.

## BEM Naming Convention

- **Block:** `text-block` (represents the overall text section)
- **Element:** `para` (the paragraph element within the block)
- **Modifiers:** `intro`, `highlight`, `note` (different styles for each paragraph)

# Custom Styled HTML Form

This project demonstrates an HTML form with various input elements, styled using a custom CSS color palette and opacity effects.

## Features

- Custom color palette using CSS variables
- Styled input fields and select dropdown
- Opacity applied to a form section for visual effect

## How to Use

1. Open `Q3(starting with css).html` in your browser.
2. Interact with the form elements to see the custom styles.

## Customization

- Modify the CSS variables in the `<style>` section to change the color palette.
- Adjust the `.form-section` opacity for different transparency effects.
