# Enterprise-Dual-ISP-Failover-EVE-NG

Enterprise Dual-ISP WAN Failover Lab using EVE-NG, Cisco IOS, HSRP, IP SLA, Object Tracking , EtherChannel , PAT, Route Maps and EEM.

The network is designed to use only one ISP at a time. IP SLA and object tracking continuously monitor the primary ISP. If ISP-1 fails, traffic is automatically rerouted to ISP-2, ensuring uninterrupted Internet connectivity.

Designed and implemented a dual-ISP enterprise network with automatic WAN failover.

Configured ISP-1 as the primary ISP and ISP-2 as the backup ISP, ensuring only one ISP is active for Internet traffic at a time.

Implemented IP SLA and Object Tracking to continuously monitor ISP availability.

Configured floating static routes to automatically redirect traffic to ISP-2 when ISP-1 becomes unavailable.

Implemented automatic failback to ISP-1 after the primary ISP recovers.

Configured HSRP between R1 and R2 for default-gateway redundancy.

Implemented Router-on-a-Stick using 802.1Q subinterfaces for inter-VLAN routing.

Created separate VLANs for users and configured HSRP virtual gateways.

Implemented PAT/NAT Overload with route maps for ISP-specific Internet access.

Configured EEM (Embedded Event Manager) to automatically clear stale NAT translations during ISP failover/failback.

Implemented LACP EtherChannel between switches for increased bandwidth and link redundancy.

Configured 802.1Q trunking between routers and switches.

Performed end-to-end troubleshooting using ping, routing tables, IP SLA, HSRP, NAT and traffic verification commands.

Built and tested the complete topology in EVE-NG.
