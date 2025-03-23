## **Instructions**  
**Objective:** The goal of this exercise is to help you develop a foundational understanding of computer networks, specifically focusing on TCP/IP and the OSI model, which are critical for understanding how data is transmitted over networks.

By the end of this exercise, you will have a clear understanding of the fundamental concepts of networking, which will aid in troubleshooting network issues and improving your overall knowledge of web scraping and other network-related tasks. 🚀  

---

## **Questions**  
1. **What is TCP/IP, and why is it important for computer networks?**  

    TCP stand for Transmission Control Protocol and IP stand for Internet Protocol both are suite of a communication protocols used to interconnect network devices on the internet. Both also used as a communication protocol in a private computer network

2. **What are the main functions of TCP in a network?**  

    To deliver the data to the respective destination

3. **What role does IP play in a computer network?**  

    To find the address to which the data is supposed to be delivered

4. **What is the difference between TCP and UDP, and when would you use each?**  

    TCP is a connection-oriented, used when prioritize reliability of sending data. UDP is a connectionless protocol and choosen while prioritize speed of sending data

5. **What is the OSI model, and why is it important in networking?**  

    OSI stand for Open System Interconnection is a set of rules that expalins how different computer systems communicate over a network.
    The OSI model allows equipment manufactures to define their standards and protocols while maintain interconnectivity with other manufacturers.

6. **What is the first layer of the OSI model, and what is its function?**  

    First layer is Physical layer, it is responsible for the physical connection between devices

7. **What does the transport layer (Layer 4) of the OSI model do?**  

    It provides end-to-end communication service for applications. It ensures complete data transfer, error recovery, and flow control between hosts

8. **What is the network layer (Layer 3) of the OSI model, and how does it work?**  

    This layer enables the communications between mulitple networks. It receives data segments from the layer above, further broken down into smaller package at the sender side. On the receiver side, this layer reassambeles the data together.

9. **What is the role of the application layer (Layer 7) in the OSI model?**  

    This is a layer that establishes communication between the application on the network and the end user by defining the protocols for successful user interaction

10. **How does understanding TCP/IP and the OSI model help in troubleshooting network issues?**  

    Because the problem might come from one of those layer. So, with understanding what the problem is we can define on which layer the problem come from 