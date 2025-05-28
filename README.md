# The Emancipation Proclamation: A Step Toward Freedom

A historical website about the Emancipation Proclamation, created following the template structure from the NHD (National History Day) website design.

## Files Structure

- `index.html` - Main landing page with project overview and navigation grid
- `thesis.html` - Main argument about the Emancipation Proclamation
- `background.html` - Historical context before 1863
- `proclamation.html` - What the document did and didn't do
- `soldiers.html` - Impact on Black military service
- `consequences.html` - Immediate effects and reactions
- `rights.html` - Rights gained and responsibilities accepted
- `legacy.html` - Long-term impact and modern relevance
- `styles.css` - CSS stylesheet with NHD-inspired design
- `README.md` - This documentation file

## Features

- **Multi-Page Structure**: Each section has its own dedicated page
- **NHD-Inspired Design**: Red, white, and blue color scheme matching National History Day aesthetics
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Sticky Navigation**: Easy navigation between all pages
- **Modern Styling**: Clean, professional appearance with gradients and shadows
- **Accessible**: Proper heading structure and semantic HTML

## Navigation Structure

The website uses a consistent navigation menu across all pages:

1. **Home** - Landing page with project overview
2. **Thesis** - Main argument about the Proclamation's significance
3. **Background** - Historical context and causes of the Civil War
4. **The Proclamation** - Details about the document itself
5. **Black Soldiers & Action** - Military service and the 54th Massachusetts
6. **Consequences** - Immediate reactions and effects
7. **Rights & Responsibilities** - Freedom and civic duties
8. **Legacy** - Modern impact and continuing relevance

## Design Elements

### Color Scheme (NHD-Inspired)

- **Primary Blue**: `#1e3a8a`, `#3b82f6` (headers, navigation accents)
- **Primary Red**: `#dc2626`, `#ef4444` (navigation bar, highlights)
- **Supporting Colors**: Various grays and whites for content areas
- **Accent Colors**: Blue and red gradients throughout

### Special Features

- **Quote Boxes**: Highlighted historical quotes with special styling
- **Highlight Boxes**: Important information in red gradient boxes
- **Section Cards**: Interactive grid layout on the home page
- **Hover Effects**: Smooth transitions and animations

## How to Use

1. Open `index.html` in any web browser to start
2. Use the navigation menu to visit different sections
3. Each page maintains the same navigation for easy movement
4. The design is fully responsive for all device sizes

## Template Credit

This website follows the design principles and color scheme from the National History Day website project examples, specifically inspired by the PARC v. Pennsylvania template at [https://nhd.org/en/resources/website-project-example-2-parc-v-pennsylvania-pioneering-the-right-to-education-for-children-with-cognitive-impairments/](https://nhd.org/en/resources/website-project-example-2-parc-v-pennsylvania-pioneering-the-right-to-education-for-children-with-cognitive-impairments/).

## Customization

### Adding Images

To add historical images:

1. Create an `images` folder
2. Add your image files (Lincoln portraits, historical documents, etc.)
3. Insert `<img>` tags in the appropriate HTML pages
4. Style them using CSS

### Example image addition:

```html
<div class="image-container">
  <img src="images/lincoln-portrait.jpg" alt="Abraham Lincoln portrait" />
  <p class="caption">President Abraham Lincoln</p>
</div>
```

### CSS for images:

```css
.image-container {
  text-align: center;
  margin: 2rem 0;
}

.image-container img {
  max-width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.caption {
  font-style: italic;
  color: #6b7280;
  margin-top: 0.5rem;
}
```

## Browser Compatibility

Works in all modern browsers including:

- Chrome
- Firefox
- Safari
- Edge

## Educational Use

This website structure is perfect for:

- National History Day projects
- School history presentations
- Educational research projects
- Historical analysis assignments
