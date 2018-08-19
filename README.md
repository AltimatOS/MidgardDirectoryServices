# MidgardDirectoryServices

The Midgard Directory Services project is a FOSS implementation of directory services utilizing various open source tools that is compatible with Apple's Open Direcotory. Features will include:

- Strong security using Kerberos authentication
- LDAP for identity management
- NTP services
- DNS zone definitions in LDAP and served by ISC BIND
- DHCP configuration stored in LDAP and served by ISC DHCPD
- Sudoers configuration stored in LDAP, used on Linux by NSS and `sudo`
- Automount configuration stored in LDAP, usable on most UNIX operating systems
- SSH key management in LDAP
- Chef Configuration management role and runlist storage in LDAP
- Chef Cookbook local repository and distribution via rsync or HTTP using either RsyncD or Lighttpd
- Certificate Management and storage in LDAP
- SASL authentication for Web services
