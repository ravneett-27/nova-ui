# Nova UI

## Overview

Nova UI is a lightweight CSS framework built using Sass. It provides a modular structure with reusable components, utility classes, and a customizable theme system.

---

## Features

- Sass-based architecture
- Utility classes (spacing, colors, typography)
- Reusable components (buttons, forms, tables)
- Customizable variables
- Compiled CSS included

---

```md id="fix3"
## Project Structure


scss/
├── base/
├── components/
├── utilities/
├── variables.scss
└── main.scss

css/
└── main.css

demo/
└── index.html
---

## Installation

Clone the repository:

```bash
git clone https://github.com/ravneett-27/nova-ui.git

Link CSS in your HTML

<link rel="stylesheet" href="css/main.css">

Usage Examples
Button
<button class="btn btn-primary m-2">Primary Button</button>
Spacing
<div class="m-2 p-3">Box with spacing</div>
Typography
<h1 class="text-bold text-lg">Heading</h1>
<p class="text-sm">Paragraph text</p>
Input
<input class="input m-2" type="text" placeholder="Enter text">
Customization

Edit variables in scss/variables.scss:

$primary-color: #4f46e5;
$secondary-color: #6b7280;
$font-size-base: 16px;
$border-radius: 6px;

Then compile:

sass scss/main.scss css/main.css
Build

Watch Sass:

sass --watch scss/main.scss css/main.css

---
