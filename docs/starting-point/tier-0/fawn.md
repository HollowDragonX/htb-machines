# Fawn

![Fawn HTB machine banner](../../assets/fawn-banner.png)

---

## :fontawesome-solid-computer: Machine information

* :material-server-security: **Machine:** Fawn
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
What does the 3-letter acronym FTP stand for? 
```

**Answer**
```
File Transfer Protocol 
```

### Task 2
**Task**

```
Which port does the FTP service listen on usually? 
```

**Answer**
```
21
```

### Task 3

**Task**

```
FTP sends data in the clear, without any encryption. What acronym is used for a later protocol designed to provide similar functionality to FTP but securely, as an extension of the SSH protocol?
```

**Answer**
```
SFTP
```


### Task 4

**Task**

```
What is the command we can use to send an ICMP echo request to test our connection to the target? 
```

**Answer**
```
ping
```


### Task 5

**Task**

```
From your scans, what version is FTP running on the target?
```

**Answer**
```
vsftpd 3.0.3 
```


### Task 6

**Task**

```
From your scans, what OS type is running on the target? 
```

**Answer**
```
Unix
```


### Task 7

**Task**

```
What is the command we need to run in order to display the 'ftp' client help menu? 
```

**Answer**
```
ftp -?
```


### Task 8

**Task**

```
What is username that is used over FTP when you want to log in without having an account?
```

**Answer**
```
anonymous
```


### Task 9

**Task**

```
What is the response code we get for the FTP message 'Login successful'? 
```

**Answer**
```
230
```


### Task 10

**Task**

```
There are a couple of commands we can use to list the files and directories available on the FTP server. One is dir. What is the other that is a common way to list files on a Linux system. 
```

**Answer**
```
ls
```

### Task 11

**Task**

```
What is the command used to download the file we found on the FTP server? 
```

**Answer**
```
get
```