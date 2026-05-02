# linux hardening lab

## objective

Evaluate and apply baseline hardening techniques to reduce the attack surface of a Linux system and improve overall system security posture.

---

## scope

- user and permission management  
- service exposure  
- system updates  
- logging awareness  
- privilege control  

---

## methodology

1. enumerate system state  
2. identify weaknesses  
3. apply hardening measures  
4. verify changes  

---

## commands used

```bash
whoami
id
cat /etc/passwd
cat /etc/group
sudo -l
chmod
chown
systemctl list-units --type=service
apt update && apt upgrade
