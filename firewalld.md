# firewalld
## outline
service -> zone -> interface
- service: port/tcp|udp
- zone: change easily
- interface: NIC

## commands
### basics
#### basic commands
`# systmectl status firewalld`

#### reload
`# firewall-cmd --reload`

### zones
#### get all zones
`# firewall-cmd --get-zones`

#### get current zone
`# firewall-cmd --get-active-zones`

#### get default zone
`# firewall-cmd --get-default-zone`

#### change default zone
`# firewall-cmd --set-default-zone=<zone>`

### services
#### get services on active zone
`# firewall-cmd --list-services`

#### get services on supecify zone
`# firewall-cmd --list-services --zone=<zone>`

#### get services on all zones
`# firewall-cmd --list-all-zones`

#### get all defined services
`# firewall-cmd --get-services`

#### change interface of specify zone
`# firewall-cmd --zone=<zone> --change-interface=<interface>`



