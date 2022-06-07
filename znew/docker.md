- [x] notes
	- [ ] docker build -t pilypala/uplift/dev .
	- [ ] [Docker Build: A Beginner's Guide to Building Docker Images](https://stackify.com/docker-build-a-beginners-guide-to-building-docker-images/)
		- [ ] docker run -p6001:6001 pilypala/uplift/dev
	- [ ] [Interactive shell using Docker Compose - Stack Overflow](https://stackoverflow.com/questions/36249744/interactive-shell-using-docker-compose)
		- [ ] docker-compose run --rm servicename

		
		
```
curl -L https://github.com/docker/compose/releases/download/v2.6.0/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose
```


- [ ] [Docker run vs docker-compose: What's the difference?](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/Docker-run-vs-docker-compose-Whats-the-difference)
	

- [x] [Docker CMD vs ENTRYPOINT: What’s The Difference & How To Choose – BMC Software | Blogs](https://www.bmc.com/blogs/docker-cmd-vs-e}ntrypoint/).
	- [ ] Commands in a containerized setup are essential instructions that are passed to the operating environment for a desired output. It is of utmost importance to use the right command form for passing instructions in order to:
	- [ ] CMD
		- [ ] multiple CMDs are ignored except the last one
		- [ ] CMD is overrideable
		- [ ] 

	

- [ ] [Get started with Docker Compose | Docker Documentation](https://docs.docker.com/compose/gettingstarted/)
	- [ ] [Install Docker Engine on Ubuntu | Docker Documentation](https://docs.docker.com/engine/install/ubuntu/)
- [ ] [(23) Docker Compose Tutorial - YouTube](https://www.youtube.com/watch?v=HG6yIjZapSA)
	- [ ] docker image ls
	- [ ] docker ps
	- [ ] docker image ls -q
	- [ ] docker image rm $(docker image ls -q)
	- [ ] docker container rm -f $(docker container ls -aq)
	- [ ] docker network ls
	- [ ] docker exec  -it  8cb sh
		- [ ] ping api
		- [ ] docker exec  -it -u root 8cb sh

- [ ] [(2) you need to learn Docker RIGHT NOW!! // Docker Containers 101 - YouTube](https://www.youtube.com/watch?v=eGz9DS-aIeY)
	- [ ] solar putty
	- [ ] docker pull centos
	- [ ] docker -d -t -name name centos
	- [ ] docker ps
	- [ ] docker exec -it name bash
	- [ ] -p 80:80
	- [ ] docker stats

- [ ] [(2) Docker Tutorial for Beginners [FULL COURSE in 3 Hours] - YouTube](https://www.youtube.com/watch?v=3c-iBn73dDE)
- [ ] ![[docker basic commands.png]]
- [ ] docker ps -a
- [ ] debugging
	- [ ] docker logs id/name
- [ ] docker network
	- [ ] docker network ls
	- [ ] docker network create network_name
- [ ] docker compose
	- [ ] ![[Pasted image 20220606031531.png]]
	- [ ] ![[Pasted image 20220606033238.png]]
	- [ ] ![[Pasted image 20220606033456.png]]
- [ ] blueprint for building images -> docker file
	- [ ] FROM
	- [ ] ENV
	- [ ] RUN
	- [ ] COPY
	- [ ] CMD
	- [ ] docker build -t myapp:1.0 . 
	- [ ] docker run --rm flag

- [ ] [(162) Docker Volumes with Persistent Data in Containers | Beginners Tutorial - YouTube](https://www.youtube.com/watch?v=OrQLrqQm4M0)
	- [ ] docker volume --help
	- [ ] docker run -itd --name voltest --mount source=myvol,target=/vol alpine
	- [ ] docker system prune
	- [ ] 
	