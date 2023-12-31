# AWS-for-Beginners

---

# IT FUNDAMENTALS 


### CLIENT SERVER COMPUTING

Examples: 
- phones
- laptops/notebooks
- desktops

#### Basic Architecture of a Computer

1. **Central Processing Unit (CPU)** : The processor that actually preforms processing data.

2. **Random Access Memory (RAM)** : This is non persistent storage. It has really high preformance and it's used for keeping data that the actual CPU and computer operating system need to access quickly. 

3. **Hard Disk Drives (HDD) or Solid State Driver SD** : This is where files and videos are stored and can be stored for a long periods of time. You *shouldn't* lose them.

4. **Network Interface Cards (NICs)** : Connects you to the internet or other computers on a network. 

#### Measurements for Components  

1. **CPU** - typically measured in gigahertz (GHz - Billions of Cycles per second)
2. **RAM** - Gigabytes (GB)
3. **Hard Disk** - Gigabytes (GB)
4. **Network Interface Card** - Megabytes per second. Gigabytes per second. Measured in terms of its performance, how much data it can actually transmit and receive over a network, and that's usually megabits per second or gigabits per second.

#### Servers Vs Desktops/Laptops 

Servers are a little bit more behind the scenes for most people.

There are different types of servers that serve different purposes. 
- Web servers
- Email servers 

Inside the server, the inside components are pretty much identical to a CPU the difference is servers are designed so that many users can connect to them. 

Server Hardware Build 
- Hardware is more specialized 
- Much higher prices compared to desktops and laptops 
- Includes redundancy 

#### Clients and Servers 

Desktops, phones, and tablet devices. There are laptops, and then there are  devices which are installed in cars, washing machines, and manufacturing equipment.

And each of these client devices is able to communicate over a network to a server.

And the servers are running in the cloud and they offer services such as applications and processing of data and data storage.

Client devices are connected over a network such as the Internet, and they can be connected through a wired connection, a wireless connection, or a cellular network.

Sometimes we call the internet the cloud which is cloud networking. 

Cloud computing is the servers in the data center. 

#### Connecting to Servers 

_**Q: How does the computer find the web server on the internet?**_

_A: the client application finds the server by its IP address._

when the user enters something like Amazon.com into their browser, a answer comes back from a DNS server with an IP address. And that address is used by the computer to connect to the web server.

##### HTTP Protocol

the protocol after connecting to the IP address is the Hypertext Transfer Protocol HTTP, and that uses a specific port.

Think of a port as a door into the server.

#### Server to Server Connectivity 

example, application servers will often need to store information in a database.

So here in this example, the protocol for MySQL is being used and that uses a free, free zero six

so the application server can connect to the database server using a specific protocol and port and

then store information in the database.

---

Something Changed
