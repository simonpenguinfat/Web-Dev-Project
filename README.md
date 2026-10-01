# Declan Carvalho — Biography Website

A fun personal biography website for **Declan Carvalho**.

It highlights that he loves coding, likes Undertale, FrontWars, and Minecraft, and includes a few friendly jokes and surprises along the way.

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
4. **Undertale** — black-and-white RPG dialogue style
5. **FrontWars** — strategy map / command panels
6. **Minecraft** — blocky inventory cards
7. **Bank surprise** — the around-$200 financial joke
8. **Contact** — unusual email and phone details
9. **Random Declan Stats** — final character sheet

## How the game sections are styled

Each game world uses different colours and layouts in `style.css`:

- **Undertale** — black background, white borders, dialogue box, red heart, battle-menu buttons
- **FrontWars** — green tactical colours, map grid, territory blocks, command panel
- **Minecraft** — grass/dirt/stone/wood colours, square borders, inventory-style grid

Scrolling feels like moving between different worlds because each section has its own visual theme.

## How the Gaster button works

Inside the Undertale section there is a clickable `ENTRY ???` button.

This uses HTML only:

- `<details>` creates expandable content
- `<summary>` is the clickable button

When you click the summary, the Gaster reveal appears. No JavaScript is required.

There may be some hidden Easter eggs around the website.

## Responsive design

Near the bottom of `style.css` there is a media query:

```css
@media (max-width: 768px) {
    /* Phone layout */
}
```

On smaller screens:

- navigation stacks more cleanly
- grids become one column (or two columns where needed)
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
- `<details>` / `<summary>`
- media queries for phones
