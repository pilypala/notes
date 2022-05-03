 [[2022-05-04]]

- [ ] [A Guide To CSS Debugging — Smashing Magazine](https://www.smashingmagazine.com/2021/10/guide-debugging-css/)
	- common causes for bugs
		- overflow content
		- browser inconsistency
		- unexpected casacading
		- DOM changes
	- debugging tips
		-   toggle off rules one at a time
		-   toggle all rules off and bring them back one at a time
		-   remove or relocate elements	
	- DevTools will display the rules most applicable to the element based on specificity at the top of the pane and then provide a stack trace of the cascade and inherited styles.
	- You can also try to isolate the specific layout issue by either placing only that part into a local file or using an online editor like CodePen or CodeSandbox.
	- copy styles from elements
	- ### overflow
	
	* {
		  outline: 1px solid red;
		}
		- max-width: 100%
		```css
		p:first-of-type {
		  width: 800px;
		  max-width: calc(100% - 6rem);
		  margin: 3rem;
		}
		```
		- by removing both the `width` and `max-width` values, which allows the paragraph’s default behavior to let it appropriately adjust within the available space of the `main` parent.
		- To simplify this behavior, a best practice is to ensure your styles include resetting all elements to use `border-box`.