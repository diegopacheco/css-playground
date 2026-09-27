# css-playground

Hands-on POCs of CSS. Every project is a plain `index.html` + `style.css`, no frameworks, and opens in the browser with `./run.sh`.
New projects start from [create-css-project.sh](create-css-project.sh).

## 👋 Basics

The smallest possible page and the three ways to attach CSS to it.
Inline styles win over the stylesheet, and `!important` wins over both.

* [hello](hello/) - Hello World page from the project template
* [inline-css](inline-css/) - Styles written in the `style` attribute of each element
* [important](important/) - `!important` beating id and class selectors

## 🎯 Selectors

Selectors pick which elements a rule applies to.
They go from everything (`*`) down to one single element (`#id`).

* [selector-universal](selector-universal/) - `*` styles every element on the page
* [selector-element](selector-element/) - Style every `p` on the page
* [selector-id](selector-id/) - `#id` styles exactly one element
* [selector-class](selector-class/) - `.class` styles every element that carries it
* [selector-2classes](selector-2classes/) - One element with two classes, both rules applied
* [selector-grouping](selector-grouping/) - `h1, h2, p` sharing the same rule

## 🎨 Colors & Backgrounds

Colors can be names, hex, rgb, hsl, with or without transparency.
Backgrounds can also be images and gradients.

* [bg-color](bg-color/) - Named background colors like DodgerBlue and Tomato
* [bg-color-hex](bg-color-hex/) - Shades of gray with hex values
* [bg-color-values](bg-color-values/) - Same color as rgb, hex, hsl, rgba and hsla
* [bg-color-per-element](bg-color-per-element/) - A different background for `h1`, `div` and `p`
* [bg-image](bg-image/) - Fixed background image, no repeat, top right
* [gradient](gradient/) - `linear-gradient` with a solid color fallback
* [vars](vars/) - Custom properties on `:root` reused with `var()`
* [property-annotation](property-annotation/) - `@property` with typed syntax, inheritance and initial values

## 📦 Box Model

Every element is a box: content, padding, border and margin.
`box-sizing` decides whether padding and border count inside the width.

* [box-model](box-model/) - Content, padding, border and margin together
* [box-sizing](box-sizing/) - `border-box` keeping two boxes the same size
* [margins](margins/) - Margins set per side
* [padding](padding/) - Padding set per side
* [borders](borders/) - Solid, dotted and double borders with different widths
* [outline](outline/) - Every outline style: dotted, dashed, groove, ridge, inset, outset
* [rounded-corners](rounded-corners/) - `border-radius` on color, border and image backgrounds
* [border-image](border-image/) - An image stretched as the border
* [shadow](shadow/) - `text-shadow` on headings
* [resize](resize/) - A box the user can resize horizontally

## 📐 Layout

Layout decides where boxes go on the page.
From old-school float to flexbox, grid, columns and responsive breakpoints.

* [float](float/) - Image floated left with text wrapping around it
* [flexbox](flexbox/) - Items in a row with `display: flex`
* [grid](grid/) - Four column grid with `display: grid` and gap
* [multiple-columns](multiple-columns/) - Newspaper text in four columns with `column-count`
* [media-query](media-query/) - Top nav that stacks its links below 600px
* [math-functions](math-functions/) - Sizes computed with `calc()`, `min()` and `max()`

## ✍️ Text, Fonts & Lists

How text looks and how lists are marked.

* [fonts](fonts/) - Serif, sans-serif and monospace font families
* [safe-font](safe-font/) - Georgia with a generic serif fallback
* [link-style](link-style/) - Link states: `:link`, `:visited`, `:hover` and `:active`
* [lists](lists/) - Circle, square, roman and alpha list markers

## 🖼️ Images

Images can be rounded, clipped, masked, blurred and covered with text.

* [image-border](image-border/) - Rounded image with `border-radius`
* [image-shapes](image-shapes/) - Circle crops with `clip-path`
* [image-mask](image-mask/) - Radial gradient `mask-image` fading the edges
* [image-filters](image-filters/) - `filter: blur()` at two strengths
* [image-text-blocks](image-text-blocks/) - Text block placed over an image
* [image-fade-box](image-fade-box/) - Image fades and a label shows up on hover
* [gallery-img](gallery-img/) - Image gallery with captions and hover borders

## 🧩 Components

Common UI pieces built with CSS only, no JavaScript.

* [buttons](buttons/) - Colored buttons
* [button-hover](button-hover/) - Outlined buttons that fill with color on hover
* [dropdown](dropdown/) - Dropdown that opens on hover
* [tooltip](tooltip/) - Tooltip that shows on hover
* [pagination](pagination/) - Page links with an active page and hover
* [form-simple](form-simple/) - Text input, select and submit styled
* [table](table/) - Table with header color, zebra rows and hover
* [table-hover](table-hover/) - Rows highlighted on hover
* [table-responsive](table-responsive/) - Full width table with zebra rows

## 🎬 Motion & Transforms

Things that move: transitions between two states, keyframe animations and 3D rotations.

* [transition](transition/) - Width and height growing at different speeds on hover
* [animmation](animmation/) - `@keyframes` color animation on hover
* [rotatex](rotatex/) - `rotateX` flipping a box on the X axis
* [rotatez](rotatez/) - `rotateZ` turning a box 90 degrees
