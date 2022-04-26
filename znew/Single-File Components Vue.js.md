[[2022-04-26]]

- [ ] [Single-File Components | Vue.js](https://vuejs.org/guide/scaling-up/sfc.html)
	-  SFC is a defining feature of Vue as a framework, and is the recommended approach...
	-  If you are just looking for enhancing largely static HTML with light interactions, you can also check out [petite-vue](https://github.com/vuejs/petite-vue), a 6kb subset of Vue optimized for progressive enhancement.
	-  Vue SFC is a framework-specific file format and must be pre-compiled by [@vue/compiler-sfc](https://github.com/vuejs/core/tree/main/packages/compiler-sfc) into standard JavaScript and CSS. A compiled SFC is a standard JavaScript (ES) module - which means with proper build setup you can import an SFC like a module:

			import MyComponent from './MyComponent.vue'
			
			export default {
			  components: {
				MyComponent
			  }
			}