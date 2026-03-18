1. What is an IP address?

it is a way to identify every device connected to a network 

1.1 Why do we need IP addresses?
We need them make connections between devices in a network, so that when sending data between devices, we have a way to identify the destination device.

1.2 What is the relation between TCP and IP?
The TCP makes sure that the data is send and recived as inteded, and the IP makes sure that it ends up in the right place.

1.3 What is a socket? Have you heard of different types of sockets?
A socket is a way of communicating between to programs running on the same network.
We haven't heard of different types of cool sockets 

1.4 What is up with the address: 127.0.0.1?
It is the local ip address for a device. It can be used to run a network locally on the device.

2. What does a client-server architecture mean?
It is a architecture where the client sends reqeusts to a server, to get data, do computations or store data. The server then does what is requested of it, and sends back the result to the client.

2.1 Give a concrete example of where you would encounter this in real life.
An example could be when you browse the internet. In this case the browser on your computer acts like the client, so when you go on a website the client sends a reqeust to the webserver to get the data of the website. Then the server sends back the data of the website to the client, then the client uses that data to show the website in the browser.

2.2 How do you decide who is the server and who is the client?
The role is decided in the software, so it is preemptively decided. The main part which distinguishes the server from the client, is that the server is passivly waiting for request from clients, and then answering the reqeusts when getting them. The klient connects to the server and sends reqeust to the server, when it needs to ressources from the server.

3. What is the difference between client-server architecture and the broker architecture?
The difference between client-server architecture and broker architecture, is that in the client-server architecture the communication between the server and client is direct, the client and server needds to know of each other. In the broker architecture the communication between the server and client goes through a broker, the broker is accountable for routing the communication between the client and the server, so the server and client don't know of each other.

3.1 What are the benefits to the broker pattern?
The benefits of the broker pattern is that the server and client is independent of each other. This means the broker pattern is more fleksible, you can change components in the system freely, as long as the broker is knows of the new components.

3.2 What could be potential downsides?
A downside could be that the broker pattern adds complexity to the system.
Another downside could be that, if the broker crashed then the whole system is crashed.

4. What does Peer-to-Peer mean?
