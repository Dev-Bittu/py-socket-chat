# Introduction
### py-socket-chat
This is an Python-based Secure Chat room. The project is entirely based on the Socket Progamming; done using Python. A server is set to the listening mode, with a specific IP Address and Port numner (that can be edited in the script) and clients are made to connect to the server. The messages are then broadcasted to all the clients present.

### How it works?
##### What is socket?
Sockets and the socket API are used to send messages across a network. They provide a form of inter-process communication (IPC). The network can be a logical, local network to the computer, or one that’s physically connected to an external network, with its own connections to other networks. The obvious example is the Internet, which you connect to via your ISP.
![Socket Diagram](https://files.realpython.com/media/sockets-tcp-flow.1da426797e37.jpg)

##### How our program work?
![Python Socket Working Diagram](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRLpOTvR5K2wENHjZF9SXOP_5625fYAbRm7gA&usqp=CAU)
---

# Features
  - Add multiples client
  - Chat parallely

---

# Getting Started
### Prerequisites
  - Python3 with pip
  - threading
  - socket

### Setup
##### Setup in Linux or in Termux
```bash
apt install git python3 -y
git clone https://github.com/Dev-Bittu/py-socket-chat.git
cd py-socket-chat
pip install -r requirements.txt
```

Now, your setup is complete.
So, you can run your server and can chat.

### Run server and connect with clients
##### For starting server
Type this in your terminal,
```bash
python3 server.py
```
if you see the follwing means it working,
```bash
$ python3 server.py
Server running!
```

##### For stopping the server
Press CTRL + c

---

# Authers
  - Bittu (Dev-Bittu)

##### Contact With Us
  - [GitHub](https://github.com/Dev-Bittu "Dev-Bittu")

# License
This project is licensed under the MIT License - see the [LICENSE](LICENSE "Lincense file") for details

# TODO
  - Add kick system
  - Show nickname instead of ip
