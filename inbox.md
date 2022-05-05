# [[天下武功，为快不破]]
# 慢工出细活，欲速则不达
## [[2022-05-06]]
- [ ] [(156) $375 donner electric drum set review! - YouTube](https://www.youtube.com/watch?v=gKBsomvgu_o)
	- Good drumer DED200

## [[2022-04-30]]

- [ ] [Vue: Using localStorage with Vuex store - Mike Street - Lead Developer and CTO](https://www.mikestreety.co.uk/blog/vue-js-using-localstorage-with-the-vuex-store/)
	- `localStorage` can _only_ contain strings. This means that any objects or arrays you wish to store in `localStorage` must be converted to a JSON string, and then re-formatted when you retrieve them.
	- ### Initialise the store
	- ### Storing data
		- We now wish to cache the data whenever the store updated. Fortunately, Vuex offers a `subscribe` function which triggers whenever the store updates.
	- ### retrieving data
		- Create a new mutation called `initialiseStore`. Inside this mutation, check if the `localStorage` item exists
- [ ] [Vuex showdown: Mutations vs. actions - LogRocket Blog](https://blog.logrocket.com/vuex-showdown-mutations-vs-actions/)
	- The only problem with Vuex mutations and actions is that it can be confusing to determine when and how they should be used. This can lead to unnecessary boilerplate, using anti-patterns, and other undesired consequences.
		-==Instead of mutating the state, actions commit mutations==
		-==Actions can contain arbitrary asynchronous operations==
	-[CSS classes not be named](https://blog.logrocket.com/5-things-to-consider-when-creating-your-css-style-guide-7b85fa70039d/) ==for the style they apply, but rather the meaning of the style  —  i.e., don’t call it `redAndBold`, but rather `activeMenuItem`.==
	- ### Why can’t mutations have access to getters?
		- While actions get a full context to work with, mutations only have the `state` and the `payload`.
	- ### An abstracted fix
	
			This may not be a serious anti-pattern, but it’s worth pointing out that if a dev treats mutations as a layer without abstraction, it reduces the responsibility of the layer and is much more likely to represent pure boilerplate rather than anything of value. If each mutation is a single assignment with a `set<Property>` name, the `setName` example from the top of this article will be how a lot of store code looks, and devs will be frustrated.
			
	- To ensure this doesn’t happen, always remember that actions should also serve a functional role. If what your action does can be done with a simple mutation, keep it like that. Only use actions when your state-changing code:
		-   Outgrows a mutation
		-   Requires committing a few mutations in certain order
		-   Deals with async code
	-   As mentioned, mutations are pure functions and synchronous. Just because the task needed right now can be handled via mutations doesn’t mean next month’s feature won’t need more than a mutation can provide. Wrapping mutations in actions is a practice that allows room for future development without a need to change all the calling code  —  much the same concept as the mutation abstraction in Alex’s fix.
	- ### Benefits of Vuex actions
		- Actions are a very open, logical layer; there’s nothing done in actions that couldn’t be done outside the store, simply that actions are centralized in the store.

- [x] [Why Getters, Mutations, Actions in Vuex Store | by Emad Aldeen Mukhtar | Medium](https://medium.com/@abuoop123/why-getters-mutations-actions-in-vuex-store-77069710d2d5)
- [ ] [Managing State in Vue with Vuex - Ionic Blog](https://ionicframework.com/blog/managing-state-in-vue-with-vuex/)


## [[2022-04-28]]



