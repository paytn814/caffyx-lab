# networking notes

## core concepts

- networks allow devices to communicate  
- data is sent in packets  
- communication follows protocols  

---

## ip addressing

- private ip = used inside local networks  
- public ip = used on the internet  

example:  
192.168.x.x (private)

---

## ports and protocols

- 80 → http  
- 443 → https  
- 22 → ssh  
- 53 → dns  

---

## protocols

- http/https → web communication  
- dns → domain name resolution  
- tcp → reliable communication  
- udp → faster, connectionless communication  

---

## networking commands

ip a                  # show ip address  
ping google.com       # test connectivity  
traceroute google.com # trace route  
netstat -tuln         # view open ports  
ss -tuln              # modern alternative  

---

## osi model

1. physical  
2. data link  
3. network  
4. transport  
5. session  
6. presentation  
7. application  

---

## key ideas

- client-server model  
- routing between networks  
- packets travel across multiple systems  
- latency affects communication speed  

---

## notes

working on understanding how data flows and how systems communicate across networks
