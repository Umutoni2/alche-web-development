# CSS Basics

## Project Overview
This project applies basic **CSS styling** and **Flexbox layout** to improve HTML pages from the previous project. It also introduces **responsive design** for smartphones.

## Files
- `index.html`
- `tweets.html`
- `base.css`
- `styles.css`

## Steps
1. **Early Styling**
   - Link CSS files in `<head>`:
     ```html
     <link href="base.css" rel="stylesheet">
     <link href="styles.css" rel="stylesheet">
     ```

2. **Flexbox Layout**
   - `body` → `display: flex; flex-direction: column;`
   - `main` → `display: flex; flex-direction: row; flex: auto;`
   - `article` → `flex: 2; overflow-y: auto;`
   - `aside` → `flex: 1; overflow-y: auto;`

3. **Responsive Design**
   - Add in `<head>`:
     ```html
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     ```
   - Add class in `<body>`:
     ```html
     <body class="works_on_smartphone">
     ```

4. **Extra Styling**
   - Customize colors, fonts, and backgrounds.
   - Add a logo in `<header>` using a Unicode character.

## Author
**sylvie UMUTONI RUTAGANIRA**
