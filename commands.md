# Networking Commands and Their Uses

| Command        | Use                                                                                 |
|----------------|--------------------------------------------------------------------------------------|
| `ipconfig`     | Displays IP address, subnet mask, and default gateway for all adapters.             |
| `ping`         | Tests the reachability of a host on an IP network and measures round-trip time.      |
| `netstat`      | Displays network connections (incoming and outgoing), routing tables, and statistics.|
| `tracert`      | Traces the path that packets take to reach a network host.                          |
| `ncpa.cpl`     | Opens the Network Connections control panel applet.                                 |
| `devmgmt.msc`  | Opens the Device Manager, which allows you to manage hardware devices and drivers.  |
| `getmac`       | Displays the MAC address for all network adapters.                                  |
| `ipconfig/all` | Provides detailed network configuration information for all adapters.               |
| `services.msc` | Opens the Services management console, which allows you to manage system services.  |

# Cisco IOS Command Explanations

| Command                               | Description                                                                              |
|---------------------------------------|------------------------------------------------------------------------------------------|
| `switch`                              | Enters the user EXEC mode on a switch. This is the initial mode where basic commands can be executed. |
| `enable`                              | Enters privileged EXEC mode from user EXEC mode. This mode allows access to more advanced commands.  |
| `configure terminal`                  | Enters global configuration mode from privileged EXEC mode. This mode allows configuration of the switch. |
| `interface fastEthernet 0/1`          | Enters interface configuration mode for FastEthernet interface 0/1. This mode allows configuration of the specific interface. |
| `int fa0/1`                           | Shortcut command to enter interface configuration mode for FastEthernet interface 0/1.   |
| `shutdown`                            | Puts the specified interface into a shutdown state, disabling it from forwarding traffic.   |
| `no shutdown`                         | Re-enables a shutdown interface, allowing it to forward traffic.                           |
| `interface range fastEthernet 0/1-10` | Enters interface configuration mode for a range of FastEthernet interfaces from 0/1 to 0/10. Allows configuration of multiple interfaces at once. |
| `exit`                                | Exits the current configuration mode or privileged EXEC mode and returns to the previous mode.         |
| `show ip interface brief`             | Displays a brief summary of the IP status and configuration of the interfaces on the switch.           |
| `show running-config`                 | Displays the current configuration in the switch's running memory.                         |
| `copy running-config startup-config`  | Saves the current configuration to the startup configuration, which is used when the switch boots.    |
| `show version`                        | Displays the system hardware and software status, including the current software version.  |
| `show interfaces`                     | Displays detailed information about all interfaces, including status, errors, and statistics.          |
| `hostname <name>`                     | Sets the hostname for the switch.                                                         |
| `enable secret <password>`            | Sets a password for privileged EXEC mode with encrypted storage.                           |
| `line console 0`                      | Enters line configuration mode for the console line.                                      |
| `password <password>`                 | Sets a password for the console line (used in line configuration mode).                   |
| `login`                               | Enables password checking at login.                                                      |
| `line vty 0 4`                        | Enters line configuration mode for the virtual terminal lines (used for remote access).   |
| `service password-encryption`         | Encrypts passwords in the configuration file.                                             |
| `banner motd #<message>#`             | Sets a Message of the Day (MOTD) banner that displays when users connect to the switch.   |
| `ip address <ip-address> <subnet-mask>` | Assigns an IP address and subnet mask to an interface (used in interface configuration mode). |
| `ip default-gateway <ip-address>`     | Sets the default gateway for the switch.                                                  |
| `switchport mode access`              | Sets the interface to access mode, used for end devices.                                  |
| `switchport mode trunk`               | Sets the interface to trunk mode, used for connecting to other switches.                  |
| `switchport access vlan <vlan-id>`    | Assigns the interface to a specific VLAN (used in interface configuration mode).          |
| `vlan <vlan-id>`                      | Enters VLAN configuration mode for the specified VLAN ID.                                 |
| `name <vlan-name>`                    | Assigns a name to the VLAN (used in VLAN configuration mode).                             |
| `spanning-tree mode <mode>`           | Configures the spanning-tree protocol mode (e.g., PVST, RSTP).                            |
| `show vlan brief`                     | Displays a brief summary of VLAN information, including IDs and names.                    |
| `show mac address-table`              | Displays the MAC address table, showing learned MAC addresses and their associated ports. |
