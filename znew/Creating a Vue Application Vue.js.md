

[[2022-04-26]]

- [Creating a Vue Application | Vue.js](https://vuejs.org/guide/essentials/application.html)
	- The object we are passing into `createApp` is in fact a component.

			import { createApp } from 'vue'
			// import the root component App from a single-file component.
			import App from './App.vue'

			const app = createApp(App)
			app.mount('#app')
			
	- The `.mount()` method should always be called after all app configurations and asset registrations are done. Also note that its return value, unlike the asset registration methods, is the root component instance instead of the application instance.
	- In-DOM Root Component Template
	- App Configurations
	- registering a component:

			app.component('TodoDeleteButton', TodoDeleteButton)
			
	- Multiple application instances