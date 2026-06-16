# NovaUI

NovaUI is a lightweight customizable CSS framework built using Sass. It provides reusable UI components and utility classes for rapid frontend web development.

---

## Features

* Built with Sass and Sass partials
* Reusable utility classes
* Styled HTML elements
* Responsive and modern design
* Easy customization using variables

---

## Included Components

### Buttons

* Primary Button
* Secondary Button

### Forms

* Input fields
* Textareas
* Form spacing and styling

### Tables

* Styled table headers
* Responsive spacing
* Border styling

### Utility Classes

#### Spacing

* `.mt-1`
* `.mt-2`
* `.p-1`
* `.p-2`

#### Typography

* `.text-center`
* `.fw-bold`

#### Layout

* `.rounded`

---

## Installation

Clone the repository:

```bash
git clone https://github.com/ravneett-27/nova-ui.git
```

---

## Project Structure

```plaintext
nova-ui/
│
├── scss/
│   ├── abstracts/
│   ├── base/
│   ├── _buttons.scss
│   ├── _forms.scss
│   ├── _tables.scss
│   ├── _utilities.scss
│   └── main.scss
│
├── css/
│   └── main.css
│
├── demo/
│   └── index.html
│
└── README.md
```

---

## Usage

Include the compiled CSS file in your HTML document:

```html
<link rel="stylesheet" href="css/main.css">
```

---

## Sass Compilation

To compile Sass into CSS:

```bash
sass scss/main.scss css/main.css
```

---

## Customization

Modify variables inside:

```plaintext
scss/abstracts/_variables.scss
```

Example:

```scss
$primary-color: #2c3e50;
$secondary-color: #3498db;
$text-color: #333;
$font-family: Arial, sans-serif;
```

---

## Demo

Open the demo page using Live Server:

```plaintext
demo/index.html
```

---

## Technologies Used

* HTML5
* CSS3
* Sass
* Git
* GitHub
* Visual Studio Code

---

## Contributors

* Bimbola Coker
* Ravneet Kaur

---

## License

This project was created for educational purposes.
