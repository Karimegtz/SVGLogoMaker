# SVG Logo Maker

## Description

SVG Logo Maker is a Node.js command-line application that allows users to generate simple logos in SVG format. Users can customize their logo by choosing a text color, selecting a shape (circle, triangle, or square), and specifying a color for the shape. The generated logo is saved as a `.svg` file that can be viewed in any compatible web browser.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Tests](#tests)
- [Additional Resources](#additional-resources)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/Karimegtz/SVGLogoMaker.git
2. Navigate to the project directory
   ```bash
   cd SVGLogoMaker
3. Clone the repository to your local machine:
   ```bash
   npm install
 

## Usage

You will be prompted to input the following:

* **Text**: You can enter up to three characters.
* **Text Color**: You can enter a color keyword or a hexadecimal value.
* **Shape**: Select one of the following options: circle, triangle, or square.
* **Shape Color**: You can enter a color keyword or a hexadecimal value.

After entering all the prompts, an SVG file named `logo.svg` will be created in the root directory of the project.

## Examples

Below is an example of what a generated SVG file might look like:

![SVG Logo Example](logo.svg)

## Tests

This project includes a suite of unit tests using Jest to verify the functionality of the `Triangle`, `Circle`, and `Square` classes.

To run the tests, use the following command:

```bash
npm test
```

## Additional Resources

- [Jest Documentation](https://jestjs.io/)
- [Inquirer Documentation](https://www.npmjs.com/package/inquirer)
- [MDN SVG Tutorial](https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial)

## Contributing

Contributions are welcome! If you would like to contribute to this project, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
