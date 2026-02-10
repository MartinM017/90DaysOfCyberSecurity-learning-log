# Day 4 --- Cloud Designing & Cloud Model

# Learning Objective
- Learn what is Cloud, get the general knowlegde of Cloud
- What can Cloud do, what is the effect of Cloud

# Key Concept
- # Cloud Design #
    - Virtual Network --- run multiple #Virtual Servers# in a large physical server, reduce redundency
    - Network Function Virtualization (NFV) --- replace the physical network devices with virtual version, remaining the    same functionality, but provide much quick and easy deployment network funcitons
    - Virtual Private Cloud (VPC) --- a private resource pool created by personal purpose in the public cloud
        - #connection methods#:
            - VPN --- using a site-to-site VPN through the internet to get access to VPC in case of security
            - Internet Gateway --- allows the VPC network connect to the public network
            - VPC NAT Gateway --- allows the VPC outbound connection to external network, but reject the inbound connection from the external
            - VPC Endpoint --- a direct connection between the VPC and Cloud provider networks, skip the public network
    - Security Group and list --- a firewall for the cloud, control inbound and outbound traffic flow
    - Network Security List and Group --- a security rule to an entire IP subnet/specific virtual NIC, provide security
- # Cloud Model #
    - Software as a Service (SaaS)
        - you --- just use the app or software, nothing else to do
        - provider --- everything else, data center, security, development etc.
    - Infrastructure as a Service (IaaS)
        - you --- manage almost everything, like operation system, firewall, application etc.
        - provider --- only manage the data centers, physical servers & networking, power and cooling
    - Platform as a Service (PaaS)
        - you --- focus on the code development of the application
        - provider --- everything else
