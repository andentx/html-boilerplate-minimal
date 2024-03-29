# HTML Boilerplate - Minimal

- HTML template with minimal placeholder files and structure
- Ideal for quickly starting a simple project

<br>

## Purpose

- To use as a template to quickly get started on a new idea
- To test HTML, CSS and JavaScript in the browser instantly by skipping the setup steps
- To have a published document to refer to and update over time
- To only include the bare minimum required for running in the browser, limiting distractions and setup

<br>

## Includes

- Minimal project directory structure
- Minimal HTML file
- Minimal meta data
- Minimal CSS Reset file
- Empty CSS and JavaScript files
- .gitignore file

<br>

## Details

- Minimal project directory structure

        .
        ├── README.md
        ├── index.html
        ├── css
        │   ├── reset.css
        │   └── style.css
        └── js
            └── scripts.js

<br>

- Minimal HTML file

  ```html
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <meta charset="UTF-8" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />

      <title>Page Title</title>

      <link rel="stylesheet" href="css/reset.css" />
      <link rel="stylesheet" href="css/style.css" />
    </head>
    <body>
      <h1>HTML Boilerplate - Minimal</h1>

      <script src="js/scripts.js"></script>
    </body>
  </html>
  ```

<br>

- Minimal meta data

  - Character encoding - required for consistent special characters

    ```html
    <meta charset="UTF-8" />
    ```

  <br>

  - Viewport info - sets the viewport to the width of the screen, and sets the default zoom

    ```html
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    ```

<br>

- Minimal CSS Reset file

  ```css
  html,
  body,
  button,
  header,
  main,
  menu,
  nav,
  footer,
  section,
  article,
  pre,
  div,
  h1,
  h2,
  h3,
  h4,
  h5,
  h6,
  p,
  ol,
  ul,
  li,
  a {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border-style: none;
    font-style: normal;
    font-weight: normal;
    list-style: none;
    text-decoration: none;
    scroll-behavior: smooth;
  }
  ```

<br>

- .gitignore File

      .DS_Store
