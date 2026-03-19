1 What is an IP address?
It is a way to identify every device connected to a network.

1.1 Why do we need IP addresses?
We need them to make connections between devices in a network, so that when sending data between devices, we have a way to identify the destination device.

1.2 What is the relation between TCP and IP?
The TCP makes sure that the data is sent and received as intended, and the IP makes sure that it ends up in the right place.

1.3 What is a socket? Have you heard of different types of sockets?
A socket is a way of communicating between two programs running on the same network.
We haven't heard of different types of cool sockets.

1.4 What is up with the address: 127.0.0.1?
It is the local IP address for a device. It can be used to run a network locally on the device.

2 What does a client-server architecture mean?
It is an architecture where the client sends requests to a server, to get data, do computations, or store data. The server then does what is requested of it, and sends back the result to the client.

2.1 Give a concrete example of where you would encounter this in real life.
An example could be when you browse the internet. In this case, the browser on your computer acts like the client, so when you go on a website, the client sends a request to the webserver to get the data of the website. Then, the server sends back the data of the website to the client, then the client uses that data to show the website in the browser.

2.2 How do you decide who is the server and who is the client?
The role is decided in the software, so it is preemptively decided. The main part which distinguishes the server from the client is that the server is passively waiting for requests from clients, and then answering the requests when getting them. The client connects to the server and sends requests to the server, when it needs resources from the server.

3 What is the difference between client-server architecture and the broker architecture?
The difference between client-server architecture and broker architecture is that, in the client-server architecture, the communication between the server and client is direct; the client and server need to know of each other. In the broker architecture, the communication between the server and client goes through a broker; the broker is accountable for routing the communication between the client and the server, so the server and client don't know of each other.

3.1 What are the benefits to the broker pattern?
The benefits of the broker pattern are that the server and client are independent of each other. This means the broker pattern is more flexible; you can change components in the system freely, as long as the broker knows of the new components.

3.2 What could be potential downsides?
A downside could be that the broker pattern adds complexity to the system.
Another downside could be that, if the broker crashed, then the whole system is crashed.

4 What does Peer-to-Peer mean?
Peer-to-Peer is a network structure where there is no server included; in this architecture, each device acts like both the server and client, and is called peers. The peers communicate directly and share their resources; therefore, there is no need for a central server.

4.1 What are the main characteristics of this architecture?
This architecture is decentralized, which means there is no central server that controls the network.
All the peers are equal; no peer has more control than others.
The peers have shared resources.

4.2 Have you encountered it anywhere online?
It is used in some message services like Signal, which, in that case, is used to make it more secure, because the messages are sent directly from peer to peer without any middleman that can access the messages.

4.3 Does Peer-to-Peer applications mean that there are no servers and only clients?
No, it rather means that each peer acts like both the server and the client.

4.4 What benefits could there be to using this pattern?
Safety is a benefit, because there is no central server, there is no middleman that knows of all the data in the network.
Another benefit is that the network keeps working even though some of the peers stop working.
The network easily grows, and gets stronger when it grows, in contrast to other structures where more clients means a slower network.

4.5 What downsides could there be to this pattern?
A downside could be that, because there is control of the data being sent, there is a risk of downloading hurtful data, and, for the same reason, it is very hard to update the system on all peers.
Another problem can be that the speed and stability rely on the users on the network.