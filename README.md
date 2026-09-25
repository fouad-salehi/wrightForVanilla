# WRIGHT

![WRIGHT](https://img.shields.io/badge/version-1.1.0-important)
![Platform](https://img.shields.io/badge/platform-Node.js-green)
![Language](https://img.shields.io/badge/language-JavaScript-yellow)
![Purpose](https://img.shields.io/badge/purpose-folder%20generator-blue)
![Run](https://img.shields.io/badge/run-node%20wright.js-important)

**WRIGHT — A folder structure generator for web developers.**

## Description

WRIGHT is a simple and practical project structure generator designed for web developers and designers working with HTML, CSS, JavaScript, PHP, and related libraries and frameworks.

It automatically creates a clean and organized project structure, helping developers save time during project setup and avoid manually creating and naming folders and files.

The generated structure includes:

* An `index.html` file for front-end development
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
node wright.js
```

WRIGHT will ask you for a project name and create the project directory using the name you provide.

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

## Templates

WRIGHT is also available with pre-configured templates:

* **Bootstrap:** https://github.com/fouad-salehi/wrightForBootstrap
* **Tailwind CSS:** https://github.com/fouad-salehi/wrightForTailwind

## Philosophy

> Create the structure once. Focus on building.

WRIGHT is designed to make the initial setup of a web project simple, fast, and organized.

## Author

**Fouad Salehi**

GitHub: https://github.com/fouad-salehi

## License

This project is proprietary software.

You may view and run the project for personal or evaluation purposes, subject to the terms of the `LICENSE` file.

Copying, modifying, creating derivative works, incorporating the project into another project, or redistributing modified versions is not permitted.

Redistribution of the original project is permitted only with clear and visible attribution to:

**Fouad Salehi / WRIGHT — Web Project Folder Structure**

Any use beyond the permissions granted by the `LICENSE` requires prior written permission from the copyright owner.

