# Home_Lab_IP_Schema

Cave001 [192.168.0.110-149]
Tattoo1 [192.168.0.150-200]

Domain Name
- horde.local
- ac.local

Utility Subnet [192.168.0.100-110]
dc1.horde.local - 192.168.0.100
- DNS / LDAP / Windows 2016

dc1.ac.local - 192.168.0.101
- DNS / LDAP / Windows 2016


Cave001 [192.168.0.110-149]
Tattoo1 [192.168.0.150-200]

Orchestration Subnet [192.168.0.100-110]
- ansible1.horde.local - 192.168.0.110
- Consul1.horde.local  - 192.168.0.111
- Consul2.horde.local  - 192.168.0.112
- Consul3.horde.local  - 192.168.0.113
- vault1.horde.local   - 192.168.0.114
- vault2.horde.local   - 192.168.0.115

