# [[天下武功，为快不破]]

## [[2022-05-04]]
- [ ] [(33) How I stay ‘in shape’ as a food vlogger - YouTube](https://www.youtube.com/watch?v=4sXwc-90YE4)
	- bialetti
	
[[book-debugging-css]]

## [[2022-05-03]]
- [ ] [(36) [街機遊戲]13分鐘看完：吞食天地2赤壁之戰，全劇情、全結局、彩蛋 - YouTube](https://www.youtube.com/watch?v=kp-0bSzVYt8)

## [[2022-05-02]]
- [ ] [(269) 2021年是自学游戏开发最好的年代！首先，选Unity还是虚幻引擎？答案已经被你想复杂了！ - YouTube](https://www.youtube.com/watch?v=NEWjDP14NBk)
- [ ] [(270) 学做游戏6年，做不出游戏5年半！不想跟教程！2022如何做出自己想要的游戏？Unity自学坑+分析 - YouTube](https://www.youtube.com/watch?v=9joWiHbfsCc)
	- 零基础要日久生情
- [ ] [(40) TC Helicon VoiceLive Play Acoustic - Review and Demo - YouTube](https://www.youtube.com/watch?v=bSoC2ivmmv8)

## [[2022-04-30]]

[[在泰国买房，这几个缺点你看不到，有人可能在对你刻意隐瞒什么，要小心]]

- [ ] [(8) This Electronic Drum Kit is CHEAP! - YouTube](https://www.youtube.com/watch?v=wDCGZgTBd5k)
- [ ] [(6) Top 5 Best Cheap Electronic Drum Kits That Don't Suck - All Under £500 - YouTube](https://www.youtube.com/watch?v=AcjZAzWgdNc)
- [ ] [(6) TOURTECH TT-12S Electronic Drum Kit - A Beginner Kit For £199 - YouTube](https://www.youtube.com/watch?v=dnN7Mm5mTko)
- [ ] [(10) Affordable Electronic Drum Sets Pt. 2! Which one did I pick and WHY? - YouTube](https://www.youtube.com/watch?v=8wg8Cjc5HWQ&t=37s)
- [ ] [Donner DED-200 Electronic Drum Kit in depth demo and review - Insanely Cheap e-drum drum set! - YouTube](https://www.youtube.com/watch?v=BgZOqVIX02c)
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



