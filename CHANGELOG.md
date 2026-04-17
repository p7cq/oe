## vyos-1x
- remote: T4732: add VRF option for commit-archive
   - PR: vyos/vyos-1x#5115
- T8459: Fix cron GeoIP update remove unexpected force option
   - PR: vyos/vyos-1x#5118
- T8448: add an option to enable SNMP traps in VRRP
   - PR: vyos/vyos-1x#5108
- vyos-netlinkd: T8486: fix high-cpu utilisation due to excessive CLI calls
   - PR: vyos/vyos-1x#5121
- config-sync: T7784: Add command to diff configuration with secondary node
   - PR: vyos/vyos-1x#5081
- T8478: Fix typo in the firewall template bridge chain name
   - PR: vyos/vyos-1x#5124
- serial: T8375: use boot activation script to define a serial console on the CLI
   - PR: vyos/vyos-1x#5092
- T8490: added typos check workflow
   - PR: vyos/vyos-1x#5126
- T8457: BGP link-state address family
   - PR: vyos/vyos-1x#5111
- dhcp: T8493: Fix sort ordering for remaining time display
   - PR: vyos/vyos-1x#5128
- serial: T8211: fix symlink collisions for multi-port USB serial adapters
   - PR: vyos/vyos-1x#5113
- vpp: T8505: Switch PPPoE bindings retrieval from CLI parsing to API call
   - PR: vyos/vyos-1x#5132
- serial: T8375: call update_serial_console() only once for default tty
   - PR: vyos/vyos-1x#5133


## vyos-build
- Testsuite: T8375: verify proper serial console settings
   - PR: vyos/vyos-build#1155
- T8472: Revert KEA-DHCP patch
   - PR: vyos/vyos-build#1158
- T8460: Add CPU isolation option to QEMU install checks for VPP-related tests
   - PR: vyos/vyos-build#1160


