# Redeemer

![Redeemer HTB machine banner](../../assets/redeemer-banner.png)

---

## :fontawesome-solid-computer: Machine information

* :material-server-security: **Machine:** Redeemer
* :simple-hackthebox: **Platform:**  HackTheBox
* :simple-linux: **Operating system:** Linux
* :fontawesome-solid-brain: **Difficulty:** Very easy
* :material-tools: **Used tools:**  `nmap`, `ping`
* :material-ip-network: **IP address:** 
* :octicons-cross-reference-16: **Study topics:**
    - [Internet Control Message Protocol (ICMP)](https://hollowdragonx.github.io/cybersecurity-notes/)
    - [Network Enumeration with Nmap](https://hollowdragonx.github.io/cybersecurity-notes/network-enumeration/nmap/nmap-cheatsheet/)

---

## :material-note-text: Write up

---

## :fontawesome-solid-tasks: Task resolution

### Task 1

**Task**

```
Which TCP port is open on the machine? 
```

**Answer**
```
6379
```

### Task 2
**Task**

```
Which service is running on the port that is open on the machine?
```

**Answer**
```
redis
```

### Task 3

**Task**

```
What type of database is Redis? Choose from the following options: (i) In-memory Database, (ii) Traditional Database 
```

**Answer**
```
In-memory Database 
```


### Task 4

**Task**

```
Which command-line utility is used to interact with the Redis server? Enter the program name you would enter into the terminal without any arguments. 
```

**Answer**
```
redis-cli 
```


### Task 5

**Task**

```
Which flag is used with the Redis command-line utility to specify the hostname? 
```

**Answer**
```
-h 
```


### Task 6

**Task**

```
Once connected to a Redis server, which command is used to obtain the information and statistics about the Redis server?
```

**Answer**
```
info
```


### Task 7

**Task**

```
What is the version of the Redis server being used on the target machine?
```

**Answer**
```
5.0.7 
```


### Task 8

**Task**

```
Which command is used to select the desired database in Redis? 
```

**Answer**
```
select
```


### Task 9

**Task**

```
How many keys are present inside the database with index 0? 
```

**Answer**
```
4
```


### Task 10

**Task**

```
Which command is used to obtain all the keys in a database? 
```

**Answer**
```
keys *
```