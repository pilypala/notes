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


- [How can I extract audio from video with ffmpeg? - Stack Overflow](https://stackoverflow.com/questions/9913032/how-can-i-extract-audio-from-video-with-ffmpeg)

		```
		ffmpeg -i sample.avi -ss 00:03:05 -t 00:00:45.0 -q:a 0 -map a sample.mp3
		```
		-   The timestamps need to be in HH:MM:SS.xxx format or in seconds.
		-   If you don't specify the **-t** option it will go to the end.
		-   You can use the **-to** option instead of the **-t** option, if you want to specify the range, eg for 45 seconds: `00:03:05 + 45 = 00:03:50`

- [(117) Build a cross-platform Electron App in Windows with WSL and Ubuntu - YouTube](https://www.youtube.com/watch?v=3chPglHV4lQ)