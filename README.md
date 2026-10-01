# Declan Carvalho — Biography Website

A fun personal biography website for **Declan Carvalho**.

It highlights that he loves coding, likes Minecraft, and includes a few friendly jokes and surprises along the way.

## Tech

This project uses **only HTML and CSS**.

- No JavaScript
- No frameworks
- No build tools
- No npm or Node.js

You can open it by double-clicking `index.html` or hosting the project folder as a static site.

## How to open locally

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in a web browser.

That is all. Nothing needs to be installed.

## Smooth scrolling

In `style.css`, the page uses:

```css
html {
    scroll-behavior: smooth;
}
```

Navigation links point to section IDs, for example:

```html
<a href="#coding">Coding</a>
```

When you click a nav link, the browser smoothly scrolls to that section.

## Major sections

1. **Home** — intro hero with a fake terminal
2. **About** — character-stat style cards
3. **Coding** — terminal / code-editor theme
4. **Minecraft** — blocky inventory cards
5. **Bank surprise** — the around-$200 financial joke
6. **Contact** — unusual email and phone details
7. **Random Declan Stats** — final character sheet

## How the game section is styled

**Minecraft** uses grass/dirt/stone/wood colours, square borders, and an inventory-style grid so it feels different from the coding terminal section.

## Responsive design

Near the bottom of `style.css` there is a media query:

```css
@media (max-width: 768px) {
    /* Phone layout */
}
```

On smaller screens:

- navigation stacks more cleanly
- grids become one column
- text stays readable
- horizontal scrolling is avoided

## Hosting on Netlify

This is a static HTML/CSS site, so Netlify setup is simple:

- **Build command:** none
- **Publish directory:** project root (`.`)

You can drag and drop the folder into Netlify, or connect this GitHub repository and deploy.

## Project files

```text
Web-Dev-Project/
├── index.html
├── style.css
├── README.md
└── .gitignore
```

## Notes

This website was made to be understandable by a Grade 10 web development student. It mostly uses:

- HTML sections and anchors
- CSS Flexbox and Grid
- sticky navigation
- hover effects and transitions
- media queries for phones

There may be some hidden Easter eggs around the website.
