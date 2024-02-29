# TypeScript Slugify

![GitHub package.json version](https://img.shields.io/github/package-json/v/code-parth/typescript-slugify)

TypeScript Slugify is a lightweight npm package that provides a simple function for converting strings into URL-friendly slugs.

## Installation

You can install TypeScript Slugify via npm:

```bash
npm install typescript-slugify
```
or
```bash
yarn add typescript-slugify
```

## Usage

```javascript
import slugify from 'typescript-slugify';

const originalString = "Hello World!";
const slug = slugify(originalString);
console.log(slug); // Output: hello-world
```

## API

### slugify(input: string): string

This function takes a string input and returns a slugified version of it, making it suitable for URLs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
