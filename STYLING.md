# Styling Guidelines for Vistapress

## General Principles

- **Consistency**: Keep styling consistent across all components.
- **Responsiveness**: Ensure all pages and components are responsive, supporting both mobile and desktop views.
- **Modularity**: Each component should have its own scoped styles to prevent bleeding of styles across components.

## CSS Structure

- **Variables**: Use CSS variables for defining colors, fonts, and sizes to enable theme flexibility.
- **Grid Layouts**: Use Flexbox or CSS Grid for arranging content dynamically.
- **Typography**: Use consistent typography sizes and font families across the application. Default font is `Roboto, sans-serif`.

### Color Scheme
- **Primary Color**: `#1a73e8` (Blue)
- **Secondary Color**: `#fbbc04` (Yellow)
- **Background Color**: `#f1f3f4` (Light Gray)
- **Text Color**: `#202124` (Dark Gray)

### Button Styling
- Buttons should have a primary, secondary, and disabled state.

```css
.btn {
  padding: 10px 15px;
  border-radius: 5px;
  background-color: var(--primary-color);
  color: white;
  border: none;
}

.btn:hover {
  background-color: var(--secondary-color);
}

.btn:disabled {
  background-color: #ccc;
}
