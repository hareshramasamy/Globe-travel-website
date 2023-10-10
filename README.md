# Globe travel website

Welcome to the Globe Travel Website project! This is a sample project showcasing how to integrate HTML and SCSS for a travel website. This repository includes HTML, SCSS and various assets like icons,buttons, and images used for development of a static version of an imaginary Travel Website called "Globe". This page is for understanding the HTML tags and their corresponding SCSS styling elements and does not include any javascript code.

The goal of this assignment is to learn about CSS positioning, Grid layout / Flexbox, and SCSS features like variables, mixins, inheritance, loops, functions, math operations, etc.

SCSS code is organized into multiple files based on UI features, common elements, and themes.

## Table of Contents

- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Usage](#usage)

## Getting Started

To get a copy of this project up and running on your local machine, follow these steps:

1. Clone the repository to your local machine:

   ```bash
    git clone git@github.com:info-6150-fall-2023/assignment-3-hareshramasamy.git
   ```

2. Navigate to the project directory:

   ```bash
   cd assignment-3-hareshramasamy
   ```

3. Open the `index.html` file in your preferred web browser to view the website.

## Project Structure

The project is structured as follows:

```
globe-travel-website/
|-- dist/
|   |-- .css files
|-- scss/
|   |-- .scss files
|-- assets/
|   |-- ...
|-- index.html
|-- README.md
```

- `css/`: Contains the compiled CSS file(s).
- `scss/`: Contains the SCSS source files.
- `assets/`: Store your website assets like images,icons,etc in this directory.
- `index.html`: The main HTML file for the website.
- `README.md`: This file.

## Usage

To make changes to the SCSS and generate the corresponding CSS file, you'll need to have a SCSS compiler installed. You can use tools like Sass to achieve this.

1. Install Sass:

   ```bash
    npm init
   ```

   ```bash
    npm i sass --save-dev
   ```

2. Compile SCSS to CSS:

   ```bash
    npx sass scss/main.scss dist/main.css
   ```

3. Make your changes in the files in the `scss` folder and recompile as needed
