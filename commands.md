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

| Command                       | Description                                                                              |
|-------------------------------|------------------------------------------------------------------------------------------|
| `switch`                      | Enters the user EXECUTION mode on a switch. This is the initial mode where basic commands can be executed. |
| `enable`                      | Enters privileged EXEC mode from user EXEC mode. This mode allows access to more advanced commands.  |
| `configure terminal`          | Enters global configuration mode from privileged EXEC mode. This mode allows configuration of the switch. |
| `interface fastEthernet 0/1`  | Enters interface configuration mode for FastEthernet interface 0/1. This mode allows configuration of the specific interface. |
| `int fa0/1`                   | Shortcut command to enter interface configuration mode for FastEthernet interface 0/1.   |
| `exit`                        | Exits the current configuration mode or privileged EXEC mode and returns to the previous mode.         |
| `show ip interface brief`     | Displays a brief summary of the IP status and configuration of the interfaces on the switch.           |
