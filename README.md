# HTML Boilerplate - Minimal

-   HTML template with minimal placeholder files and structure
-   Ideal for quickly starting a simple project

<br>

## Includes

-   Minimal project directory structure
-   Minimal HTML file
-   Minimal meta data
-   Minimal CSS Reset file
-   Placeholder CSS and JavaScript files
-   .gitignore file

<br>

## Details

-   Minimal project directory structure

          .
          ├── README.md
          ├── index.html
          ├── css
          │   ├── reset.css
          │   └── style.css
          └── js
              └── scripts.js

<br>

-   Minimal HTML file

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

<br>

-   Minimal meta data

    -   Character encoding - required for consistent special characters

              <meta charset="UTF-8" />

    <br>

    -   Viewport info - sets the viewport to the width of the screen, and sets the default zoom

            <meta name="viewport" content="width=device-width, initial-scale=1.0" />

<br>

-   Minimal CSS Reset file

        html,
        body,
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
        li {
            border-style: none;
            box-sizing: border-box;
            font-style: normal;
            list-style: none;
            margin: 0;
            padding: 0;
        }

<br>

-   Placeholder CSS and JavaScript files

        /* style.css */

        h1 {
            color: darkgreen;
        }

    <br>

        // scripts.js

        console.log('hello from scripts.js');

<br>

-   .gitignore File

        .DS_Store
