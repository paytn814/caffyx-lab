# network analysis lab

## objective

Analyze network traffic to understand communication patterns, protocol behavior, and indicators of normal versus abnormal activity.

---

## scope

- packet inspection  
- protocol identification  
- traffic filtering  
- behavioral analysis  

---

## tools

- wireshark  
- tcpdump  

---

## methodology

1. capture traffic  
2. apply filters  
3. identify endpoints  
4. analyze patterns  
5. document findings  

---

## filters used

```text
dns
http
tcp
udp
ip.addr == x.x.x.x
tcp.port == 443
