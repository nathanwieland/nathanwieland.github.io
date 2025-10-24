# AI Agent Instructions for nathanwieland.github.io

## Project Overview
This is a simple static website project built with pure HTML and inline CSS. The site consists of two main pages:
- `index.html`: The main landing page
- `product.html`: A secondary page for products

## Architecture and Structure
- The project uses a flat structure with all files in the root directory
- Navigation between pages is handled through simple anchor tags
- Styling is implemented using inline CSS for simplicity
- Images are referenced directly from the root directory (e.g., `pwc.png`)

## Design Patterns and Conventions
1. **Styling Conventions**:
   - Font family: "Times New Roman" with Times and serif fallbacks
   - Text alignment: Centered layout
   - Standard margin-top of 2% on body elements

2. **Common Components**:
   - Header image: `<img src="pwc.png">`
   - Horizontal rule with specific styling:
     ```html
     <hr style="width: 80%; border: 0.5px dashed rgb(194, 53, 53); margin: 4px auto">
     ```
   - Navigation links with consistent styling:
     ```html
     <a href="..." style="text-decoration: none; color: black; font-weight: bold; font-size: 18px; line-height: 1.2;">
     ```

3. **Layout Patterns**:
   - Multi-column text sections using CSS columns
   - Line height of 1.2 for text readability
   - Consistent margin spacing (20px) for navigation elements

## Development Workflow
- This is a static site - no build process required
- Pages can be tested by opening directly in a browser
- Deploy by pushing changes to the main branch (GitHub Pages)

## Integration Points
- The site is hosted on GitHub Pages
- Assets (images) should be placed in the root directory
- No external dependencies or third-party integrations

## Tips for AI Agents
1. When adding new pages, follow the existing pattern of:
   - Inline CSS in the head section
   - Consistent navigation link styling
   - Header image and horizontal rule inclusion
2. Maintain the established styling conventions for consistency
3. Keep the file structure flat - no subdirectories for simple pages