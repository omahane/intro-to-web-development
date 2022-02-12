# Internet Graph (Single User)

How a single request from your computer gets to the internet
Source [Open.edu](https://www.open.edu/openlearncreate/mod/oucontent/view.php?id=129584&printable=1)

```mermaid
graph TD
Home_PC[Your PC at local address 192.168.0.101] --  http request for "https://google.com" from browser--> your_LAN[router at local address 192.168.0.1]
your_LAN -- from address 82.10.250.19  --> ISP[Internet Service Provider]
ISP -- sends "https://google.com" to 82.10.25.02 --> DNS[Domain Name Services (DNS) Server, which looks up IP address]
DNS -- returns "142.250.191.142" --> ISP
ISP -- sends "142.250.191.142" --> Internet
```
