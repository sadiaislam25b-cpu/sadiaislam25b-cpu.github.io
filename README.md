# sadiaislam25b-cpu.github.io
 Personal Portfolio

This is my personal portfolio website built with HTML and CSS.

## Reflection

### Technical Concept I Gained Mastery Over
One technical concept I strengthened during this project was **CSS layout using Flexbox and Grid**. My mental model is that the parent container controls layout. Flexbox is best for one-direction layouts, while Grid is better for two-dimensional layouts.

I used Grid in my projects section to create a responsive layout:

```css
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
}

Project Requirement I’m Proud Of
I’m proud of building a responsive layout using only HTML and CSS. It was challenging because small CSS changes often affected multiple sections. I solved this by structuring the page into clear sections and relying on Flexbox and Grid instead of fixed sizes. For example, I used Flexbox to vertically center the hero content:
.hero {
  height: 100vh;
  display: flex;
  align-items: center;
}

This made the layout more consistent and easier to maintain.
