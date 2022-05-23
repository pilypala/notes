#up/project/uplift project_uplift

[[2022-05-15]] [[2022-05-17]][[2022-05-17]] [[2022-05-18]]
[[2022-05-22]] [[2022-05-22]][[2022-05-22]]

[😊start](http://localhost:6001/user/1/start/%23up%2Fproject%2Fuplift%20project_uplift%0D%0A)
[[Servers]]
[[wsl firewall]]


### [[2022-05-23]]
- [ ] user page design 
	- [ ] [Rounded Clock](file:///D:/Users/Guoping%20Huang/Downloads/rounded-clock-main/index.html)
	- [ ] making countdown work
		- [ ] local countdown with vuex
		- [ ] [Quickly pause JavaScript execution - Chrome DevTools - Dev Tips](https://umaar.com/dev-tips/178-quick-pause-script-execution/#:~:text=Alternatively%2C%20you%20can%20pause%20on,Windows%3A%20F8%20or%20_Control%20%2B%20%5C_) 
	- [ ] [vue.js - Vuex Action vs Mutations - Stack Overflow](https://stackoverflow.com/questions/39299042/vuex-action-vs-mutations#:~:text=Mutations%2C%20as%20the%20name%20suggests,asynchronous%20code%20or%20business%20logic.)
		- [ ] However, by doing this you're scattering your state mutations all over the place. You lose the ability to simply just open a single module housing the state and at a glance see what kind of operations can be applied to it. Having centralized mutations solves this, albeit at the cost of some boilerplate.
		- [ ] the state, with almost no business logic. In other words, mutations are meant to be mostly used like setters.

### [[2022-05-22]]
- [ ] user page design 
	- [ ] [Progress · Bootstrap v5.0](https://getbootstrap.com/docs/5.0/components/progress/)
	- [ ] [Rounded Clock](file:///D:/Users/Guoping%20Huang/Downloads/rounded-clock-main/index.html)
	- [ ]  [CSS { In Real Life } | Finding an Element’s Nearest Relative Positioned Ancestor](https://css-irl.info/finding-an-elements-nearest-relative-positioned-ancestor/)
		- [ ]  $0.offsetParent
		- [ ]  getComputedStyle($0.offsetParent).position
		- [ ]  getComputedStyle($_).position
	- [ ] [stroke-dasharray | CSS-Tricks - CSS-Tricks](https://css-tricks.com/almanac/properties/s/stroke-dasharray/)
		- [ ] This will override a presentation attribute <path stroke-dasharray="5" ... />
		- [ ] This will not override an inline style e.g. <path style="stroke-dasharray: 5;" ... />
		- [ ] [How SVG Line Animation Works | CSS-Tricks - CSS-Tricks](https://css-tricks.com/svg-line-animation-works/)

### [[2022-05-18]]
- [ ] user page design 
	- [ ] [Progress · Bootstrap v5.0](https://getbootstrap.com/docs/5.0/components/progress/)
	- [ ] [Rounded Clock](file:///D:/Users/Guoping%20Huang/Downloads/rounded-clock-main/index.html)
	- [x] parcel vue


### [[2022-05-17]]
- [ ] user page design 
	- [x] parcel vue
	
- [ ] start and stop a count down
	
### [[2022-05-15]]

 - [x] start counter on task for user id
- [ ] Page showing successful start or failure 
	- [ ] start a count down
	
### [[2022-05-14]]
 - [x] add status column to task
	 - [x] running or done enum

### [[2022-05-13]]
- [x] db table for user and task
	- [x] id, name, createdAt
	- [x] http://47.111.95.20/padn
	- [x] [node-mysql2/Promise-Wrapper.md at master · sidorares/node-mysql2](https://github.com/sidorares/node-mysql2/blob/master/documentation/Promise-Wrapper.md)
- [ ] Page showing successful start or failure 
	- [ ] start a count down
- [x] [SSH keygen best practice for cmder – Luke Scammell's Personal Blog](https://www.scammell.co.uk/2017/09/18/ssh-keygen-best-practice-for-cmder/)
- [x] [[Servers]]

### [[2022-05-12]]
- [x]  URL encoder for obsidian
	- [x]  [WSL2/UbuntuのIPアドレスを取得したい - Qiita](https://qiita.com/neko_the_shadow/items/25b797cb436078b9e832)
	- [x]  [[wsl firewall]]
	- [x]  [Performing port-proxying and port-forwarding on Windows · Embrace The Red](https://embracethered.com/blog/posts/2020/windows-port-forward/)
		- [x]  `netsh interface portproxy reset`
		- [x]  `netsh interface portproxy show all`
	- [x]  user link for md 
- [ ] Page showing successful start or failure 
	- [ ] start a count down

### [[2022-05-11]]

- [ ] special link format http:://47.111.95.20:6000/userid/start/url-encoded-name
	- [ ] expressjs server get page to intepret the link
		-  [WSL Port Forwarding - DEV Community](https://dev.to/vishnumohanrk/wsl-port-forwarding-2e22)
		-  https://expressjs.com/en/starter/hello-world.html
		-  [Serving static files in Express](https://expressjs.com/en/starter/static-files.html)
	- [ ]  URL encoder for obsidian
		- [ ]  
	- [ ] Page showing successful start or failure


### [[2022-05-10]]

- [ ] systray with timer countdown
	- [ ] click to show name and circle timer
- [ ] special link format http:://47.111.95.20:6000/userid/start/url-encoded-name
	- Page showing successful start or failure

- [ ] [javascript - Electron.js How to minimize/close window to system tray and restore window back from tray? - Stack Overflow](https://stackoverflow.com/questions/37828758/electron-js-how-to-minimize-close-window-to-system-tray-and-restore-window-back)

- [ ] [Quick Start | Electron](https://www.electronjs.org/docs/latest/tutorial/quick-start)
- [ ] trayIcon
	- [ ] https://www.google.com/imgres?imgurl=https%3A%2F%2Fst3.depositphotos.com%2F1032749%2F17477%2Fv%2F1600%2Fdepositphotos_174771280-stock-illustration-clock-icon.jpg&imgrefurl=https%3A%2F%2Fdepositphotos.com%2F174771280%2Fstock-illustration-clock-icon.html&tbnid=A075Ge41y13ePM&vet=10CBQQxiAoBGoYChMI8P2inr_T9wIVAAAAAB0AAAAAEIAB..i&docid=qVRA9SWJHXDQWM&w=1600&h=1700&itg=1&q=clock%20icon&ved=0CBQQxiAoBGoYChMI8P2inr_T9wIVAAAAAB0AAAAAEIAB

- [ ] [(5) Electron js Tutorial - 11 - Tray Module - YouTube](https://www.youtube.com/watch?v=6guMb33u7Kg)