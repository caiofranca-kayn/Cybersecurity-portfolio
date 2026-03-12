2️⃣ meow/README.md — Máquina Meow
# 🐱 Meow — Hack The Box Writeup

**Platform:** Hack The Box  
**Machine:** Meow  
**Difficulty:** Very Easy  
**Operating System:** Linux  

---

## 🎯 Objective

Introduce beginners to the basic penetration testing workflow:

- Connecting to the lab environment
- Performing basic enumeration
- Interacting with open services

---

## 🔎 Enumeration

Port scan using **nmap**:


23/tcp open telnet


---

## 📡 Service Interaction

Connect via Telnet:


telnet <target-ip>


Login credentials:


username: root
password: (blank)


---

## 🔓 Exploitation

Weak authentication allowed direct access.

---

## 🏁 Flag Capture


cat /root/root.txt


---

## 💡 Skills Learned

- Basic enumeration  
- Service identification  
- Connecting to remote services  
- Exploiting weak authentication
