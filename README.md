# ButtonGroup - Adaptive with Container Queries

This repository contains a proof of concept (POC) for an adaptive button group component using HTML and CSS. The button group adjusts its layout based on available space using CSS container queries. If there is enough space, the buttons are aligned horizontally; otherwise, they stack vertically.

## Features

- **Responsive Layout:** The button group adapts to the container's width.
- **Container Queries:** Uses modern CSS container queries to determine button layout.
- **Re-usability:** Easily customizable for different button groups across projects.

## Technologies Used

- **HTML5:** Structure of the button groups and containers.
- **CSS3:** Styling for buttons and layout management using container queries.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/button-group-container-query.git
   cd button-group-container-query
   ```
2. Open index.html in your browser to view the example.

## Usage

The button groups in this example are wrapped inside a .button-group\_\_container element. Depending on the container's width, buttons are aligned horizontally or stacked vertically.

Here's an example of how to use it:

```html
<div class="button-group__container">
  <div class="button-group">
    <button class="button">Cancel</button>
    <button class="button button--primary">Submit</button>
  </div>
</div>
```
