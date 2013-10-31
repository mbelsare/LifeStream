LifeStream
==========

CmpE 275 - Enterprise Software Components (LifeStream Project)


The CMPE 275 Project 1
Photographs are glimpses of time as it streams towards an unknown sea. LifeStream’s mission is to preserve, share, remember and reflect through pictures. The architecture of the application is based on Netty communication package that is built upon JAVA NIO. In case of message communication using Netty, communication payloads are passed through a pipeline to convert from communications protocol to application data. Netty uses a pipeline encoding/decoding concept where messages are passed along a stack to either retrieve from a Channel (Socket) or to write to it. The flow of operation is initiated from the server side where an overlay network is set up to achieve communication between servers which is done by accepting connection request of one server with other servers by sending a heartbeat through the management port. Every server is connected to a client or set of clients that sends messages across multiple servers associated with each other in the overlay network to other clients by creating hops between them. The client has a user account associated with it that uniquely identifies it. The project is developed by implementing various kinds of technologies like JAVA, Python, Google Protobuf, C++, JSON, JPA, PostGIS.

Few of the principles our team follower as Design Decisions:
Our design was based on creating of a star topology in-order to transfer images from one user to another in order to have a collection of images.

Flooding algorithm was implemented in order to decide the shortest path whenever two or more servers would respond with the image.

Contributors
============
* Kunal Vora
* Manan Shah
* Sahil Gupta
* Manish Belsare
