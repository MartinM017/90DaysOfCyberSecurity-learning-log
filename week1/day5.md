# Day 5 --- Introduction to IP and Common Ports

## Key Concept
- # IP
    - IP (Internet Protocol) --- communication protocol used to send data between devices over the network
    - TCP & UDP --- works like boxes being delivered by the IP
        - TCP (Transmission Control Protocol) --- it is connection-oriented, it creates a formal connection setup before data transfer happens, it provides "reliable" delivery, recover from errors
        - UDP (User Datagram Protocol) --- it is connectionless, no formal open or close to the connection, "unreliable" delivery, no error recovery provided, 
    - Port --- like a specific number belongs to a service
        - Permanent Port Number --- port 0 - 1023, used for common service
        - Temporaray Port Number --- port 1024- 65535, used for any other applications
        - TCP/UDP Ports --- use ports from 0 - 65535, but same port number is different for TCP/UDP, e.g. TCP80 /= UDP80
- # Commom Ports
    - FTP (File Transfer Protocol) --- generic file transfer method, tcp/20 (active mode data) or tcp/21 (control)
    - SSH (Secure Shell) --- a text-based console communication, tcp/22, which is encrypted
    - SFTP (Secure FTP) --- generic file transfer with Security (encrypted network communication), use SSH tcp/22
    - Telnet (Telecommunication Network) --- tcp/23, console access similar to SSH
    - SMTP (Simple Mail Transfer Protocol) --- tcp/25 (plaintext), tcp/587 (TLS encryption)
    - DNS (Domain Name System) --- convert names to IP address
        - upd/53 --- used for small name queries
        - tcp/53 --- used for large transfer of data
    - DHCP (Dynamic Host Configuration Protocol) --- automatically assign IP address and network setting to devices, udp/67 or udp/68
    - TFTP (Trivial File Transfer Protocol) --- udp/69, used for very simple file transfer application, no authentication needed, quick and easy
    - HTTP & HTTPS (Hypertext Transfer Protocol) --- used for communication in the browser, tcp/80 or tcp/443
    - NTP (Network Time Protocol) --- udp/123, used for synchroizing the clocks, automatic update
    - SNMP (Simple Network Management Protocol) --- udp/161, gather statistics from network devices
    - LDAP / LDAPS (Lightweight Directory Access Protocol) --- tcp/389 or tcp/636, store and retrieve information in a network directory
    - SMB (Server Message Block) --- protocol used by Microsoft Windows, used for file sharing etc., it is integrated into the operating system, direct over tcp/445
    - Syslog --- udp/514, standard for message logging, usually a central log collector
    - RDP (Remote Desktop Protocol) --- tcp/3389, share a desktop from a remote location
    - SIP (Session Initiation Protocol) --- tcp/5060 & tcp/5061, used for setup and manage VoIP sessions, like call, ring, hang up etc. 

