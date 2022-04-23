- [javascript - What is the difference between .js and .mjs files? - Stack Overflow](https://stackoverflow.com/questions/57492546/what-is-the-difference-between-js-and-mjs-files)

		Node.js will treat `.cjs` files as CommonJS modules and `.mjs` files as ECMAScript modules. It will treat `.js` files as whatever the default module system for the project is (which is CommonJS unless _package.json_ says `"type": "module",`).
		
		
- [Node.js shebang. JavaScript is an interpreted language… | by Alex Ewerlöf | Medium](https://alexewerlof.medium.com/node-shebang-e1d4b02f731d)

		## The short answer

		This is the most common shebang for Node scripts:

		#!/usr/bin/env node

		However, `env` has a few other tricks up its sleeve that we can use.
		
		
- [javascript - Are the angle brackets (< or >) special in a regular expression? - Stack Overflow](https://stackoverflow.com/questions/10095039/are-the-angle-brackets-or-special-in-a-regular-expression)

```javascript
'<foo> and <bar>'.match(/<[^>]*>/g); // ["<foo>", "<bar>"]
```