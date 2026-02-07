#Day 1 --- Introduction of Cyber Security & OSI Model

## Learning Objectives
- Get to known the basic idea of Cyber Security
- Learn the OSI Model

## Key Concepts
- OSI Model --- It is a "guide" to explain the process of how network works and how information transit between devices
- Layers of OSI Model:
    - Layer 7 **Application**   - human interact layer, which provide network service to applications and defines the way of how applications are comminucating
                                - **common protocols** --- HTTP/HTTPS, SMTP, DNS etc.

    - Layer 6 **Presentation**  - works like a translator, does data format conversion, data encryption/decryption, and compression

    - Layer 5 **Session**       - a management of communication between devices, considering something like "are we still talking?"

    - Layer 4 **Transport**     - works like a post officer, which forcus on how the data is sent
                                - key protocols --- TCP & UDP

    - Layer 3 **Network**       - by using IP address, moving data from one network to another
                                - **IP Address** --- the actual address of the device in the network
                                - **Routing** --- deciding where to send the packets next, and what is the *best* path, this processing is done by *Routers* 
                                - breaks data into *packets* and forwards from *local LAN* through nultiple routers to the destination network (each router only knows what is the next hop)

    - Layer 2 **Data Link**     - controlling the data communication between two devices on the **same** local network
                                - **Framing** --- layer 2 takes raw bits from layer 1 and package them into *frames*
                                              --- containing: source MAC address, destination MAC address, data, Error-Checking info
                                - **MAC Address** --- the actual *hardware* address

    - Layer 1 **Physical**      - physics of the network, like the actual component of the devices, signaling, cabling, connectors etc.