# NSA-Resarch-Cybersecurity-and-Firewalls-SonicWall-vs-pfSense
In the field of Cybersecurity, Firewall is a network security device that filters incoming and outgoing traffic based on security policies that has already been set in advance to secure the network for an organization and decides whether to accept, deny or drop traffic based on those security policies. In simpler words Firewall acts like a wall between a private internal network and a open Internet.
![Firewall](./Firewall.png)
In this project we had the oppurtunity to compare SonicWall, a commercial firewall with pfSense a strong open-source alternative. We based our resarch on the internet and learnt about the key differneces in interfaces,configurations,security features and learning value between these two firewalls and here is the comparison.
## Learning Value Comparison: SonicWall vs. pfSense

**SonicWall** – This provides a commercial firewall solution with a user-friendly interface and integrated security features. While it offers robust protection and is widely used in enterprise environments, its closed-source nature limits the ability for users to modify and experiment with underlying configurations.

**pfSense** – It is an open-source firewall/router software distribution based on FreeBSD. It offers extensive customization options, allowing users to delve deep into networking concepts and configurations. This flexibility makes it ideal for those seeking hands-on experience and a comprehensive understanding of firewall functionalities.

### References:
- [Netgate Official Site](https://www.netgate.com)
- [pfSense - Wikipedia](https://en.wikipedia.org/wiki/PfSense)

# Configuring pfSense vs SonicWall Firewall
Both firewalls can be configured by CLI, but if users configure pfSense via CLI, then they can get more configuration options, like they could configure it by directly changing the configuration files, whereas in SonicWall Firewall, there are very few configuration options via CLI, due to which it is used to troubleshoot only. More particularly, users can get full root access and get to use all shell commands in CLI in pfSense, whereas users can use troubleshooting commands like ping in SonicWall.
