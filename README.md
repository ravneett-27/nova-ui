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

The project is organized into different folders to keep the framework clean and easy to manage.

scss/ → contains all Sass files and partials
abstracts/ → stores variables used across the framework
base/ → contains base styles like reset and typography
_buttons.scss → button component styles
_forms.scss → form and input styles
_tables.scss → table styles
_utilities.scss → reusable utility classes
main.scss → main Sass file importing all partials
css/main.css → compiled CSS file
demo/index.html → demo page showing the framework components
README.md → project documentation and instructions


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
