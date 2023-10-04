# Installation

codellins supports _npm_ under the name **codellins**

`npm i codellins`

The Npm Package Supports ES Modules, allows you to setCookies getCookies removeCookie and many other functionalities

Sure, here's a Markdown documentation template for your `codellins` npm package:

````markdown
# codellins NPM Package Documentation

## Introduction

`codellins` is a JavaScript package that provides utility functions for working with cookies and the clipboard in web applications. This package is designed to simplify common tasks related to managing cookies and interacting with the clipboard.

## Installation

To use `codellins` in your project, you can install it using npm or yarn:

```bash
npm install codellins
# or
yarn add codellins
```
````

Replace `'codellins'` with the actual name of your npm package.

## Usage

### Cookies

#### `Cookies.set(name, value, days)`

Sets a cookie with the specified name, value, and optional expiration days.

- `name` (string): The name of the cookie.
- `value` (string): The value to store in the cookie.
- `days` (number, optional): The number of days until the cookie expires. If not provided, the cookie will expire in 100 days by default.

Example:

```javascript
import codellins from "codellins";

codellins.Cookies.set("myCookie", "cookieValue", 7);
```

#### `Cookies.get(cookieName)`

Retrieves the value of a cookie by its name.

- `cookieName` (string): The name of the cookie to retrieve.

Example:

```javascript
import codellins from "codellins";

const value = codellins.Cookies.get("myCookie");
```

#### `Cookies.remove(name)`

Removes a cookie by its name.

- `name` (string): The name of the cookie to remove.

Example:

```javascript
import codellins from "codellins";

codellins.Cookies.remove("myCookie");
```

### Clipboard

#### `Clipboard.write(text)`

Writes the specified text to the clipboard.

- `text` (string): The text to copy to the clipboard.

Example:

```javascript
import codellins from "codellins";

codellins.Clipboard.write("Hello, clipboard!");
```

#### `Clipboard.read()`

Reads text from the clipboard asynchronously.

Example:

```javascript
import codellins from "codellins";

const readClipboard = async () => {
  const text = await codellins.Clipboard.read();
  console.log("Clipboard content:", text);
};

readClipboard();
```

## License

This package is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

- Author: Collins Adi
- GitHub: [GitHub Profile](https://github.com/collinsadi/codellins)
- Portfolio: [Portfolio Website](https://https://collinsadi.vercel.app)

## Contribution

<!-- Contributions are welcome! If you'd like to contribute to this project, please submit a pull request. -->

Contributions Would Be Open Soon Stay Tuned

## Issues

If you encounter any issues or have questions about this package, please [open an issue](https://github.com/collinsadi/codellins/issues) on GitHub.




This is the first Version More Features Rolling out Soon


