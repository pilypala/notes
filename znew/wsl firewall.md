
[[2022-05-12]]

[[project_uplift]]

[[2022-05-11]]

		netsh interface portproxy add v4tov4 listenport=6001 listenaddress=0.0.0.0 connectport=6001 connectaddress=172.28.35.96


- [x] [Allow Server Running Inside WSL To Be Accessible Outside Windows 10 Host - NEXTOFWINDOWS.COM](https://www.nextofwindows.com/allow-server-running-inside-wsl-to-be-accessible-outside-windows-10-host)

		netsh interface portproxy add v4tov4 listenport=1234 listenaddress=0.0.0.0 connectport=1234 connectaddress=172.28.35.96
				
		netsh advfirewall firewall show rule status=enabled name=all | select-string -pattern "(LocalPort.*1234)" -context 9,4