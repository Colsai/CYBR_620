# CYBERSECURITY NOTES
## Chapter 10

## Routers 
Can come with a lot of internal functions, need to be protected from hackers, because it can give them a lot of control.

## Firewalls
- Firewalls are network devices, software, or a combination of them to set a security policy.
- Heart of a firewall is the security policies involved.
- Traffic should be more sanitized when using a firewall.
- Many different types of firewalls 
- May have multiple firewalls, the topology determines what networks are employed at what parts.
- Perfect firewall policy is one that the end user never sees even a single unauthorized packet enter. 

## How firewalls work... 
- Firewalls work by establishing security policys and enforcing them: Network address translation, basic packet filtering, stateful packet filtering, access control lists, application layer proxies.
- ACLs (access control lists) are a cornerstone of security.
- Firewalls can also act as network traffic regulators
- Firewalls can examine inbound email and determine if it is safe, etc.

## Next generation firewalls
- Based on CONTENT as well
- Deep packet inspection
- Move beyond port/protocol inspection and blocking
- Add application-level inspection
- Add intrusion prevention
- Bring intelligence from outside the firewall

Traffic can be managed based on content, not merely site or URL. 

## Web Application Firewalls vs. Network Firewalls
- Web application firewalls: any software package or appliance that applies rules set to HTTP/HTTPS traffic, they shape the web traffic and filter out SQL injection attacks, malware, cross-site scripting, etc.
- Network firewall is hardware or software that controls packets into and out of the network.

## Concentrators
Network devices that act as traffic management devices

## Wireless Access Point

## Telephony
- A private branch exchange is an exchange of the public telephone network into a business... can be compromised.

## VPN Concentrator
- VPNS are used to provide a secure communication stream
- Usually IPsec, a protocol for IP security. Mandated in IPv6 and optional in IPv4

## Intrusion Detection Seystems:
- Log traffic and respond to unauthorized networks or host use, both in real time and after the fact. 
- These systems are implemented using software. 

## Network Access Control
- Managing endpoints on a case-by-case basis as they connect is a security methodology known as network access control. 

Two main competing methodologies are NAP (Network Access Protection)- Microsoft, which measure sthe health of the host
NAC (Network Admission Control)- CISCO enforces policeis by the network administrator
Both are still in early stages of implementation, but fully implemented and widely available.
Information is sent to a NOC (network operations center) that allows operators to observe and interact with the network, using self reporting and sself-healing nature of network devices to ensure efficient network operation.

- Software enables controllers at NOCs to measure the actual performance of network devices and make changes to the configuration and operation of devices remotely
- SNMP was developed to perform management, monitoring, and fault resolution across networks. 

## Load Balancers
- Load balancers are designed to distribute the processing load over two or more systems. They can be used to help improve resource utilization and throughput but also have the advantage of increasing the fault tolerance of the overall system- a critical process may be split across several systems. If one system faiols, others can pick up the load. 

## Proxy:
Proxies act as a bridge for web traffic
Networking techniques are used to ensure they go through the proxy server

## Web Security Gateways:
Some security vendors combine proxy functions to create web security gateway. They address security threats and pitfalls unique to web-based traffic.

## Web Security Gate

## Internet Content Filters
- Internet content filters protect a corporation from employees' viewing of inappropriate or illegal content at the workplace and the subsequent. 

## Data Loss Prevention
- Data Loss Prevention (DLP) refers to technology used to detect and prevent transfers of data across enterprises. DLP technology scans packets, etc.

## Unified Threat Management
- A unified threat management appliance refers to all-in-one security appliances, many vendors offer that are devices that combine multiple functions into the same hardware appliance.
- Sequence: Proxy, Sandbox, DLP, IPS, AV, URL

## Threats
Magnetic media: hard disks, floppy disks, etc. can have weaknesses to magnetic fields, high temperatures, and exposure to water. Other types: diskettes, tape, etc, Optical media such as CDs, DVDs, Blu-Ray.

Electronic Media: SSDs, which can also fail over time, must be replaced at some point. 

## Security Threats with Transmission Media:
- Must prevent physical access to server by unauthorized individuals.
- Prevent other access to network connection
- Preventing access is costly, but requirement for replacing a server is also costly.

## Physical Safety Concerns:
- Balanced approach is most sensible with physical security.
- Information helps to protect against successful attacks.
- Essential, and essential to prevent unauthorrized contact. Need either a firewall or a VPN.

## Cloud Computing:
- Common term to describe computer services over a network

## Private Cloud:
- Cloud for its own needs, truly dedicated to the organization. More expensive but less exposure. 

## Public Cloud:
- Cloud service that is open for public use. Significantly less restrictions and security than private clouds.

## Hybrid:
- Some elemnents of private, public, and community could structures. 

## Community:
- A community cloud system is one where several organizations with a common interest share a cloud environment for the specific purposes of the endeavor.
- An example is local public entitites and key local firms sharing a community cloud dedicated to the initiatives.

## Types
Software as a service: 
