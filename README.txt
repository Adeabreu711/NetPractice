This project has been created as part of the 42 curriculum by <alde-abr>.

# Description

This project is a practical introduction to computer networking using the NetPractice training interface.  
The goal is to understand and apply fundamental networking concepts such as IP addressing, subnet masks, routing, switches, and routers by configuring multiple network topologies.

Through a series of progressive levels, the project focuses on building functional networks, ensuring correct packet forwarding, and solving routing issues such as missing forward or reverse paths.

---

# Instructions

## Running the project
- Open the NetPractice training interface by launching `index.html` in a web browser.
- Each level presents a network topology that must be configured correctly.
- Configure IP addresses, subnet masks, gateways, and routing tables as required.
- Use the built-in test button to verify connectivity.

## Exporting configurations
- Once a level is successfully completed, export the configuration using the [Get my config] button.
- Each level generates one configuration file.

## Submission requirements
- **10 exported configuration files** (one per level) must be placed at the **root of the repository**.
- The repository must also contain this `README.md` file at its root.

---

# Resources

## Networking concepts studied

- [TCP/IP addressing]
  The system used to uniquely identify devices on a network and enable communication between them using IP addresses.

- [Subnet masks and CIDR notation]
  Methods used to define the network and host portions of an IP address, allowing networks to be divided into smaller subnets.

- [Network and broadcast addresses]
  Special addresses used to identify a subnet itself (network address) and to communicate with all devices within that subnet (broadcast address).

- [Default gateway]
  The router address used by a host to send traffic to destinations outside its local network.

- [Static routes and default routes]
  Manually configured routing rules that define how packets are forwarded to remote networks, including a fallback route for unknown destinations.

- [Routers and switches]
  Network devices used to connect hosts: switches operate within a local network, while routers interconnect different networks and forward packets between them.

- [Forward path and reverse path routing]
  The requirement for network communication to have a valid route both to the destination and back to the source in order to succeed.

- [OSI model layers (focus on Layers 2 and 3)]
  A conceptual model describing network communication, with emphasis on Layer 2 (data link and switching) and Layer 3 (networking and routing).

## References
- RFC 791 – Internet Protocol (IP)
- RFC 1918 – Address Allocation for Private Internets
- Cisco Networking Basics Documentation
- Subnetting tutorials (CIDR, /30, /24, /16, etc.)

https://datatracker.ietf.org/doc/html/rfc791
https://datatracker.ietf.org/doc/html/rfc1918
https://www.cloudflare.com/fr-fr/learning/network-layer/what-is-a-subnet/

## Use of AI
AI tools were used as a learning assistant to:
- Explain networking concepts (IP addressing, subnetting, routing logic)
- Clarify NetPractice error messages (e.g. forward and reverse routing issues)

---

## Notes

This project is intended as a learning exercise.  
The focus is on understanding why a network works, not only making it work.

