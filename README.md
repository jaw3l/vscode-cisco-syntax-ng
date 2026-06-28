# vscode-cisco-syntax

Cisco IOS Syntax Highlighting for [Visual Studio Code](https://code.visualstudio.com/)

## Quick Start

* Install the [extension](https://marketplace.visualstudio.com/items?itemName=jamiewoodio.cisco) with VSCode.

* Save a file with the `.ios` extension and open with VSCode

## Supported Commands

### Interface
`interface`, `shutdown`, `no switchport`, `speed`, `duplex`, `encapsulation`, `cdp enable`, `mtu`, `bandwidth`, `fair-queue`, `media-type`, `clockrate`, `physical-layer`, `async mode`, `routed-port`, `autostate`

Interface types: `Ethernet`, `FastEthernet`, `GigabitEthernet`, `TenGigabitEthernet`, `FortyGigabitEthernet`, `Dialer`, `Dot11Radio`, `ATM`, `BRI`, `Tunnel`, `Loopback`, `Null`, `Port-channel`, `Virtual-Access`, `Virtual-Template`, `Vlan`, `Bundle-Ether`, `BVI`, `MgmtEth`

### IP Addressing & ARP
`ip address`, `ip unnumbered`, `ip proxy-arp`, `ip gratuitous-arp`, `ip local-proxy-arp`, `ip redirects`, `ip unreachables`, `ip directed-broadcast`, `ip route-cache`, `ip split-horizon`, `ip helper-address`, `ip igmp-helper-address`, `ip default-gateway`, `ip default-network`, `ip routing`, `ip domain`, `ip host`, `ip subnet-zero`, `ip classless`, `ip virtual-reassembly`, `ip verify`, `ip inspect`, `ip flow-export`, `ip flow-top-talkers`

### VLAN
`vlan`, `vlan-configuration`, `name`, `mtu`, `state`, `suspend`, `resume`, `said`, `stp`, `mode`, `remote-span`, `private-vlan` (`primary`, `isolated`, `community`, `association`, `secondary`)

### Switchport
`switchport`, `switchport mode` (access, trunk, dynamic auto, dynamic desirable, dot1q-tunnel), `switchport access vlan`, `switchport access voice`, `switchport trunk encapsulation`, `switchport trunk allowed`, `switchport trunk native`, `switchport trunk pruning`, `switchport nonegotiate`, `switchport block`, `switchport voice vlan`, `switchport voice dot1p`, `switchport voice priority`, `host-mode`, `protected`

### VTP
`vtp`, `vtp mode` (server, client, transparent, off), `vtp domain`, `vtp version`, `vtp password`, `vtp pruning`

### Spanning Tree
`spanning-tree`, `spanning-tree vlan`, `spanning-tree mst`, `spanning-tree mode` (pvst, rapid-pvst, mst), `spanning-tree extend system-id`, `spanning-tree guard` (loop, root), `spanning-tree portfast`, `spanning-tree portfast default`, `spanning-tree bpduguard`, `spanning-tree bpdufilter`, `spanning-tree backbonefast`, `spanning-tree uplinkfast`, `spanning-tree cost`, `spanning-tree priority`, `spanning-tree root` (primary, secondary), `spanning-tree hello-time`, `spanning-tree forward-time`, `spanning-tree max-age`, `spanning-tree transmit-hold-count`, `spanning-tree pathcost`, `spanning-tree link-type`, `loopguard`, `bpduguard`, `bpdufilter`, `guard`, `filter`, `stp`, `rstp`, `mstp`, `pvst`, `rapid-pvst`

### MST
`instance <id> vlan <range>`, `region`, `name`, `revision`, `max-hops`

### SVI / Routed Port
`ip routing`, `ip default-gateway`, `ip default-network`, `ip helper-address`, `ip directed-broadcast`, `ip redirects`, `ip unreachables`, `ip proxy-arp`, `ip local-proxy-arp`, `ip split-horizon`, `ip route-cache`, `ip igmp-helper-address`, `ip nat inside`, `ip nat outside`, `ip virtual-reassembly`, `ip tcp-adjust-mss`, `ip pim sparse-mode`, `ip pim dense-mode`, `ip pim sparse-dense-mode`, `ip pim neighbor-filter`, `ip pim passive`, `ip pim dr-priority`, `ip virtual-router mac-address`, `no switchport`, `routed-port`

### HSRP
`standby`, `standby version`, `standby timers`, `standby priority`, `standby preempt`, `standby ip`, `standby name`, `standby track`, `standby authentication`, `standby mac-address`, `standby msec`, `standby delay minimum`, `standby delay reload`

### VRRP
`vrrp`, `vrrp version`, `vrrp timers`, `vrrp priority`, `vrrp preempt`, `vrrp ip`, `vrrp description`, `vrrp authentication`, `vrrp track`, `vrrp delay reload`

### GLBP
`glbp`, `glbp timers`, `glbp priority`, `glbp preempt`, `glbp ip`, `glbp name`, `glbp weight`, `glbp load-balancing` (round-robin, weighted, host-dependent), `glbp authentication`, `glbp track`, `glbp forwarder`, `glbp mac-address`

### Routing Protocols
`router`, `network`, `passive-interface`, `redistribute`, `auto-summary`, `synchronization`, `bgp`, `neighbor`, `default-information`, `address-family`, `route-map`

### ACLs
`access-list`, `ip access-list extended`, `ip access-list standard`, `permit`, `deny`, `remark`, `log`, `established`, `evaluate`, `object-group`, `object`, `host`, `any`, `any4`, `any6`

### NAT
`ip nat`, `ip nat inside`, `ip nat outside`, `ip nat source`, `ip nat pool`, `static`, `ip nat inside source`, `ip nat outside source`, `route-map`

### DHCP
`ip dhcp pool`, `ip dhcp excluded-address`, `domain-name`, `default-router`, `dns-server`, `client-name`, `client-identifier`, `host`, `option`

### AAA & Security
`aaa`, `authentication`, `authorization`, `accounting`, `login`, `password`, `username`, `enable`

### VPN & Crypto
`crypto`, `crypto pki`, `crypto keyring`, `crypto isakmp profile`, `crypto isakmp policy`, `crypto isakmp client configuration`, `crypto ipsec profile`, `crypto ipsec transform-set`, `crypto map`, `crypto dynamic-map`, `tunnel-group`, `crypto ikev2`, `crypto ssl`

### VoIP & Telephony
`telephony-service`, `ephone`, `ephone-dn`, `dial-peer`, `voice-port`, `voice-card`, `voice translation-rule`, `voice translation-profile`, `voice register global`, `voice register pool`, `voice register dn`, `voice service`, `ssid`, `station-role`

### QoS
`class-map`, `policy-map`, `route-map`, `map-class`, `match ip precedence`, `match protocol`, `match access-group`, `set ip dscp`, `class`, `class-default`, `priority`, `service-policy`, `frame-relay`, `bandwidth`, `fair-queue`

### Services
`service`, `clock`, `boot`, `logging`, `ntp`, `snmp-server`, `tftp-server`, `radius-server`, `control-plane`, `archive`, `banner`, `line`, `session-timeout`, `exec-timeout`, `stopbits`, `access-class`, `transport input`, `transport output`, `access-list`, `dialer-list`, `bridge`

### IP SLA / Monitoring
`ip sla`, `ip sla monitor`, `ip sla schedule`, `ip sla responder`, `snmp-server`, `logging`, `ntp`

### UDLD
`udld enable`, `udld disable`, `udld aggressive`

### Storm Control
`storm-control broadcast level`, `storm-control broadcast pps`, `storm-control multicast level`, `storm-control multicast pps`, `storm-control unicast level`, `storm-control unicast pps`

### Errdisable
`errdisable recovery cause`, `errdisable recovery interval`, `errdisable detect cause`

### IOS-XR Commands
`ipv4 address`, `ipv6 address`, `ipv4 address-family`, `ipv6 address-family`, `bundle`, `vrf`, `lacp`, `bfd`

## Links

[GitHub](https://github.com/woodjme/vscode-cisco-syntax)

[Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=jamiewoodio.cisco)