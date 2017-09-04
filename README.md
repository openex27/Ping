# Ping
Ping using ICMP(echo)  implement by Golang

---

### Step 1:
compile golang code
 - go build Ping.go (you need install golang first)
 
### Step 2:
Run Binary Program
- ./Ping www.so.com 100 3

### Usage
Ping [domain] [Package Size] [Count]
 - **domain**: Designation trace domain
 - **Package Size**: ICMP date size (Does not include IP headers and ICMP headers 20 + 8) 
 - **Count**: Trace times
