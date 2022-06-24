#up/project/uplift project_uplift

[😊#up/project/uplift](https://47.111.95.20:6001/user/1/md?prefill=%23up%2Fproject%2Fuplift)

- [ ] [[Servers]]
- [ ] [[wsl firewall]]


[[2022-06-25]]
----------------------

- [x] fix md trailing brackets
- [x] make links to md page with task name
	- [x] another text area that generates md link 



### [[2022-06-12]]
- [ ] [Advanced Installation Instructions | Electron](https://www.electronjs.org/docs/latest/tutorial/installation)
- [ ] [How to set badge text on tray icon?? · Issue #7322 · electron/electron](https://github.com/electron/electron/issues/7322)
- [ ] put a week of listing in pane
	%%- [ ] script to copy produciton db to dev db%% 

### [[2022-06-10]]
- [ ] put number of done in dates
- [ ] systray app

### [[2022-06-09]]
- [x] circle progress with every minute
	- [x] changes color for each bar type
- [ ] when restoring states, don't fetch the ones less than 5 minutes long


### [[2022-06-07]]
- [x] use docker node:16 for development
- [x] put project to aliyun 
	- [x] set up production config
- [x] fix /user/1/md

### [[2022-06-06]]

- [x] fix missing user_id when redirecting

### [[2022-06-05]]
- [x] remove date if no bars
- [x] complete title for running task
- [x] put bars for the running task under title
- [ ] stop the task using double click on coutndown
- [ ] deploy using docker on aliyun
- [ ] make circle pregressbar reflect task state


### [[2022-06-02]]

	UPDATE ULTBL_task SET created_at = ADDTIME( created_at, "24:00:00");
	UPDATE ULTBL_task SET updated_at = ADDTIME( created_at, "24:00:00");
	
	

### [[2022-05-30]]
- [x] displaying two days worth of done tasks
	- [x] done tasks for two days from server
	- [x] [How to Format Dates in JavaScript with One Line of Code](https://www.freecodecamp.org/news/how-to-format-dates-in-javascript/)
		- [x] toLocaleDateString('en-us', { weekday:"long", year:"numeric", month:"short", day:"numeric"}) 
- [ ] routine that checks if UI needs update
	- [ ] check every second to see if the bar the running task is updated with new color
		- [ ] needs to include running task in the chart
		- [ ] update the bars for running task when it gets to a point
- [ ] actually using the dev version


### [[2022-05-29]]
- [ ] actually using the dev version
- [x] fetch all tasks for the today
	- [x] display using bars, grouped by tasks
- [x] able to resume running task with done tasks
	- [x] if running task is longer than 2hrs, set it to done and put it to be 2hrs 


### [[2022-05-27]]
- [x] start a task for user id 1
- [x] display countdown for such task
	- [x] restore timer state
	- [x] [timezone - How do I get the current time zone of MySQL? - Stack Overflow](https://stackoverflow.com/questions/2934258/how-do-i-get-the-current-time-zone-of-mysql)
	- [x]  SELECT EXTRACT(HOUR FROM (TIMEDIFF(NOW(), UTC_TIMESTAMP))) AS `timezone`
- [ ] timer expires after 1hr
	
### [[2022-05-25]]
- [x] start a task for user id 1
- [ ] display countdown for such task
	- [ ] restart timer action


### [[2022-05-24]]
- [ ] starting a task for user id 1
	- [ ] can't start a task when there is a task running

### [[2022-05-23]]

- [ ] starting a task for user id 1
	- [x] success/fail page for the startlink
	- [x] [Alerts · Bootstrap v5.0](https://getbootstrap.com/docs/5.0/components/alerts/)
	- [ ] [Using EJS Template Engine With Express.js](https://www.topcoder.com/thrive/articles/using-ejs-template-engine-with-express-js)
	- [ ] [How to use EJS to template your Node.js application - LogRocket Blog](https://blog.logrocket.com/how-to-use-ejs-template-node-js-application/)
	
- [ ] user page design 
	- [ ] [Rounded Clock](file:///D:/Users/Guoping%20Huang/Downloads/rounded-clock-main/index.html)
	- [ ] making countdown work
		- [x] local countdown with vuex
		- [x] [Quickly pause JavaScript execution - Chrome DevTools - Dev Tips](https://umaar.com/dev-tips/178-quick-pause-script-execution/#:~:text=Alternatively%2C%20you%20can%20pause%20on,Windows%3A%20F8%20or%20_Control%20%2B%20%5C_) 
	- [ ] [Vuex showdown: Mutations vs. actions - LogRocket Blog](https://blog.logrocket.com/vuex-showdown-mutations-vs-actions/)
		- [x] This reasoning is the same as the recommendation that [CSS classes not be named](https://blog.logrocket.com/5-things-to-consider-when-creating-your-css-style-guide-7b85fa70039d/) ==for the style they apply, but rather the meaning of the style  —  i.e., don’t call it `redAndBold`, but rather `activeMenuItem`.==
		- [x] ==Another aspect of mutations that contributes to their transactional nature is that they are intended to be pure functions. Mutations are intended to receive input only via their payload and to not produce side effects elsewhere. While actions get a full context to work with, mutations only have the `state` and the `payload`.==
		- [x] ==To ensure this doesn’t happen, always remember that actions should also serve a functional role. If what your action does can be done with a simple mutation, keep it like that. Only use actions when your state-changing code:==
			 -  Outgrows a mutation
			 -  Requires committing a few mutations in certain order
			 -  Deals with async code

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