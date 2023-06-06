# Custom CSS Framework

A lightweight and customisable CSS framework built using Sass and Sass partials. This framework provides a set of base styles, custom themes for standard HTML elements, and utility classes for common styling.

## Installation

1. To use the framework, follow these steps:
2. Download or clone the repository.
3. Ensure you have Sass installed globally on your system.

In the project's root directory, run the following command to compile the Sass code:

```bash
sass src/main.scss dist/framework.css
```
4. The compiled CSS file will be available in the dist folder. Include this file in your project.

## Usage
To use the custom CSS framework, include the compiled CSS file in your HTML file:

```python
<link rel="stylesheet" href="path/to/framework.css">

```

## Customization

This CSS framework allows for easy customization using Sass variables. To customize the framework's styles, follow these steps:

1. Open the _variables.scss file in the src folder.

2. Modify the variable values according to your desired customizations. For example:

```css
$primary-color: #ff0000;
$font-size-small: 14px;
// Modify more variables as needed
```
3. Recompile the Sass code using the previous command:

## Custom Themes

This CSS framework provides custom themes for standard HTML elements. Simply include the appropriate classes in your HTML markup to apply the theme styles. For example:

```css
<button class="btn-primary">Primary Button</button>
```

## Utility Classes

The framework also includes utility classes to apply common styling quickly. Here are some examples:

1. .text-primary: Sets the text color to the primary color.
2. .font-bold: Makes the text bold.
3. Add more utility classes as needed.

Refer to the _utilities.scss file in the src folder for a complete list of available utility classes.

## Contributing

Contributions to the custom CSS framework are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

## License

[MIT](https://choosealicense.com/licenses/mit/)