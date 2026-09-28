# wrightForVanilla

![wrightForVanilla](https://img.shields.io/badge/version-1.1.0-important)
![Platform](https://img.shields.io/badge/platform-Node.js-green)
![Language](https://img.shields.io/badge/language-JavaScript-yellow)
![Purpose](https://img.shields.io/badge/purpose-folder%20generator-blue)
![Status](https://img.shields.io/badge/Status-Active-success)
![Run](https://img.shields.io/badge/run-node%20wrightForVanilla.js-important)

**WRIGHT for Vanilla — A folder structure generator for web developers.**

## Description

WRIGHT for Vanilla is a simple and practical project structure generator designed for web developers and designers working with HTML, CSS, JavaScript, PHP, and related libraries and frameworks.

It automatically creates a clean and organized project structure, helping developers save time during project setup and avoid manually creating folders and files.

The generated structure includes:

* A ready-to-use `index.html` file
* No framework — plain HTML, CSS, and JavaScript
* A `dashboard/assets` directory
* Separate folders for CSS, JavaScript, images, and fonts
* A default `stylesheet.css`
* An empty `app.js`
* A `favicon.ico`
* A project `README.txt`

## Getting Started

Make sure [Node.js](https://nodejs.org/) is installed on your system.

Then run:

```bash
node wrightForVanilla.js
```

WRIGHT for Vanilla will ask you for a project name and create the project directory using the name you provide.

For example:

```text
› Project name: my-website
```

The generated project will have a structure similar to:

```text
my-website/
├── dashboard/
│   └── assets/
│       ├── css/
│       │   └── stylesheet.css
│       ├── js/
│       │   └── app.js
│       ├── images/
│       └── fonts/
├── index.html
├── favicon.ico
└── README.txt
```

## Project Structure

### CSS

Place stylesheets and CSS-related resources inside:

```text
dashboard/assets/css/
```

### JavaScript

Place JavaScript files and related resources inside:

```text
dashboard/assets/js/
```

### Images

Place project images, icons, and other visual assets inside:

```text
dashboard/assets/images/
```

### Fonts

Place custom fonts and font-related resources inside:

```text
dashboard/assets/fonts/
```

## Libraries & Frameworks

If your project uses additional libraries or frameworks, you can create an additional folder inside the appropriate technology directory.

For example:

```text
dashboard/assets/js/
├── libraries/
└── app.js
```

or:

```text
dashboard/assets/css/
├── libraries/
└── stylesheet.css
```

This keeps third-party resources separated from your own project files and helps maintain a clean project structure.

## Philosophy

> Create the structure once. Focus on building.

WRIGHT is designed to make the initial setup of a web project simple, fast, and organized.

## WRIGHT Ecosystem

* [WRIGHT](https://github.com/fouad-salehi/wright)

## Author

**[Fouad Salehi](https://github.com/fouad-salehi)**

## License

WRIGHT is **proprietary software**.

You may view and run the project for personal or evaluation purposes only. Copying, modifying, creating derivative works, incorporating the project into another project, or redistributing modified versions is **not** permitted.

See the [LICENSE](./LICENSE) file for the complete terms.

## Copyright

Copyright © 2026 Fouad Salehi. All rights reserved.

