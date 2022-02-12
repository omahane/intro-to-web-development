
```mermaid
graph LR
Home_PC[Your PC at local address 192.168.0.101] --  http request from browser--> your_LAN[router at local address 192.168.0.1]
your_LAN --> ISP
ISP --> DNS
DNS --> ISP
ISP --> Internet
```
