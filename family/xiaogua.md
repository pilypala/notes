#xiaogua/up/project/courses
#xiaogua/up/math

- [ ] [😊#xiaogua/up/math](https://47.111.95.20:6001/user/17/md?prefill=%23xiaogua%2Fup%2Fmath)


#xiaogua/up/typing tipp10
[😊#xiaogua/up/typing tipp10](https://47.111.95.20:6001/user/17/md?prefill=%23xiaogua%2Fup%2Ftyping%20tipp10)
[😊#azhe/up/typing tipp10](https://47.111.95.20:6001/user/2/md?prefill=%23azhe%2Fup%2Ftyping%20tipp10)

#xiaogua/up/drum rudiments
[😊#xiaogua/up/drum rudiments](https://47.111.95.20:6001/user/17/md?prefill=%23xiaogua%2Fup%2Fdrum%20rudiments)

[😊#xiaogua/up/drum djembe](https://47.111.95.20:6001/user/17/md?prefill=%23xiaogua%2Fup%2Fdrum%20djembe)

#xiaogua/up/english
[😊#xiaogua/up/english](https://47.111.95.20:6001/user/17/md?prefill=%23xiaogua%2Fup%2Fenglish)

#xiaogua/up/pianoAndEar
[😊#xiaogua/up/pianoAndEar](https://47.111.95.20:6001/user/17/md?prefill=%23xiaogua%2Fup%2FpianoAndEar)

[😊#up/project/xiaogua](https://47.111.95.20:6001/user/1/md?prefill=%23up%2Fproject%2Fxiaogua)



----------------------------------

## [[2022-07-02]]
- [ ] deploy to live server
	- [x] swich to /english/1, 2, 3...etc
	- [x] git clone
	- [x] dc up
		- [ ] sudo docker build -t ping:nodemon .
		- [ ] sudo docker run --rm -it -p 7001:7001 --mount type=bind,source="$(pwd)"/../src,target=/project ping:nodemon

## [[2022-06-22]]
- [ ] [(109) (Reading Practice (Improve your pronunciation in English - YouTube](https://www.youtube.com/watch?v=E0APXrppsP4)
- [ ] [Learn English through Story 🔥 The Story of the United States - Graded Reader Level 3 | CiaoEL #10 - YouTube](https://www.youtube.com/watch?v=Y1SDLJLN9DY)

## [[2022-06-20]]
- [x] http://192.168.0.99:7001/ewebplayer.html
- [x] play mp4 file on mobile web browserexit
- [x] [HTML5 Video](https://www.w3.org/2010/05/video/mediaevents.html)
- [x] http://192.168.0.99:7001/ewebplayer.html


## [[2022-06-19]]
- [ ] expressjs docker that shows web page hello work
	- [ ] [How to automatically delete a Docker container after running it | Power CMS Technology](https://www.powercms.in/article/how-automatically-delete-docker-container-after-running-it)	
	- [ ] sudo docker build -t ping:nodemon .
	- [ ] sudo docker run --rm -it -p 7001:7001 --mount type=bind,source="$(pwd)"/../src,target=/project ping:nodemon
	- [ ] https://www.tutorialspoint.com/expressjs/expressjs_hello_world.htm

```
var express = require('express');
var app = express();

app.get('/', function(req, res){
   res.send("Hello world!");
});

app.listen(3000);
```

- [ ] [Serving static files in Express](https://expressjs.com/en/starter/static-files.html)
- [ ] override a command when running an image
	- [ ] sudo docker run --rm -it -p 7001:7001 --mount type=bind,source="$(pwd)"/../src,target=/project ping:nodemon ls