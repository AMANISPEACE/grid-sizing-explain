# grid-sizing-explain

This is the website that I have made to showcase how frid Sizing Actually works.
![image](https://github.com/AMANISPEACE/grid-sizing-explain/assets/97402085/0dd629e9-38c5-497b-b409-1a65e3e5ca88)

#Try Now :
https://amanispeace.github.io/grid-sizing-explain/

Grid Sizing is the important concept while learning CSS.

# CSS Grid Sizing Explained

Welcome to the **CSS Grid Sizing** project! This project aims to provide a comprehensive explanation of grid sizing in CSS, including practical examples and usage tips.

![CSS Grid Layout](![image](https://github.com/AMANISPEACE/grid-sizing-explain/assets/97402085/461ccd78-913f-46fb-9b77-13598feacc0a))

## Table of Contents

- [Introduction](#introduction)
- [What is CSS Grid Sizing?](#what-is-css-grid-sizing)
- [How to Use CSS Grid](#how-to-use-css-grid)


## Introduction

CSS Grid Layout is a powerful layout system available in CSS. It allows developers to create complex and responsive web designs easily. This project focuses specifically on grid sizing within the CSS Grid Layout, helping you understand how to control the size of grid items.

## What is CSS Grid Sizing?

CSS Grid Sizing refers to the methods used to control the size of the rows, columns, and grid items within a CSS Grid Layout. The main properties used for grid sizing include:

- `grid-template-columns`
- `grid-template-rows`
- `grid-auto-columns`
- `grid-auto-rows`
- `grid-column`
- `grid-row`

### Key Concepts

- **Grid Tracks:** The columns and rows of the grid.
- **Grid Lines:** The dividing lines that create the grid structure.
- **Grid Areas:** The rectangular space defined by grid lines.

### Sizing Units

- **Fraction (`fr`):** A flexible unit that represents a fraction of the available space.
- **Pixels (`px`), Percentages (`%`), and other CSS length units:** Fixed units for more precise control.
- **Auto:** Automatically adjusts size based on content.

## How to Use CSS Grid

To use CSS Grid, you need to define a container as a grid using the `display: grid;` property. Then, you can define the structure of your grid using the grid sizing properties.

### Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Grid Sizing Example</title>
    <style>
        .grid-container {
            display: grid;
            grid-template-columns: 1fr 2fr 1fr;
            grid-template-rows: auto;
            gap: 10px;
        }
        .grid-item {
            background-color: #ddd;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="grid-container">
        <div class="grid-item">1</div>
        <div class="grid-item">2</div>
        <div class="grid-item">3</div>
    </div>
</body>
</html>


