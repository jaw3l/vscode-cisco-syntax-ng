# Changelog

## [1.12.0] - 06-19-2026

### Added

* Add expanded STP syntax: spanning-tree mode (pvst/rapid-pvst/mst), vlan, mst, extend, guard, link-type, transmit-hold-count, pathcost
* Add MST configuration: instance, region, name, revision, max-hops
* Add UDLD commands: udld enable, udld disable, udld aggressive
* Add Storm Control: storm-control broadcast/multicast/unicast level/pps
* Add Errdisable: errdisable recovery cause/interval, errdisable detect cause

### Changed

None

### Removed

None

## [1.11.0] - 06-19-2026

### Added

* Add Syntax for SVI (Switched Virtual Interface) configuration
* Add Syntax for HSRP (Hot Standby Router Protocol): standby, timers, priority, preempt, track, authentication
* Add Syntax for VRRP (Virtual Router Redundancy Protocol): vrrp, timers, priority, preempt, authentication, track
* Add Syntax for GLBP (Gateway Load Balancing Protocol): glbp, timers, priority, preempt, weight, load-balancing, forwarder
* Add Syntax for IP routing commands: ip routing, ip default-gateway, ip helper-address, ip directed-broadcast, ip redirects, ip unreachables
* Add Syntax for PIM on SVI: ip pim (sparse-mode|dense-mode|sparse-dense-mode)
* Add Syntax for NAT on SVI: ip nat inside/outside, ip virtual-reassembly
* Add Syntax for routed port (no switchport)

### Changed

None

### Removed

None

## [1.10.0] - 06-19-2026

### Added

* Add Syntax for VLAN configuration (vlan, private-vlan, remote-span)
* Add Syntax for VTP (mode, domain, version, password, pruning)
* Add Syntax for Switchport (mode access/trunk/dynamic/dot1q-tunnel, trunk allowed/native, voice vlan)
* Add Syntax for VLAN interface (autostate)
* Add Syntax for Spanning Tree (portfast, bpduguard, bpdufilter, root, cost, priority, loopguard)

### Changed

None

### Removed

None

## [1.9.1] - 07-12-2021

### Added

Folding for interfaces, DHCP pools and SSIDs

### Changed

None

### Removed

None

## [1.9.0] - 26-09-2020

### Added

None

### Changed

Logo as per Cisco Guidelines

### Removed

None

## [1.6.0] - 14-05-2019

### Added

* Add Syntax for ^C Quoted Strings from [@MoreThanHidden](https://github.com/MoreThanHidden/vscode-cisco-syntax)

### Changed

None

### Removed

None
