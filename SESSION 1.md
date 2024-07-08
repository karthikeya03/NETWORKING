# Learning Networking :

## 1. Fiber Optic Cables :

Fiber optic cables are high-speed data transmission mediums. They contain strands of glass fibers inside an insulated casing. These cables are designed for long-distance and high-performance data networking and telecommunications.

**Example:** Fiber optic cables are used by ISPs (Internet Service Providers) to provide high-speed internet connections to homes and businesses.

## 2. Internet: Connection of Regions :

The internet connects different regions worldwide through a network of physical cables, including fiber optics, copper cables, and satellite connections.

**Illustration:** Regions are interconnected through a global network of cables and satellite links, allowing data to travel across countries and continents.

## 3. Submarine Cable Map :

The Submarine Cable Map is a free and regularly updated resource from TeleGeography that shows the locations and connections of undersea cables worldwide. These submarine cables are crucial for international data transmission.

**Connected Undersea:** Submarine cables lie on the ocean floor, connecting different continents and enabling global communication.

## 4. Network Models :

### Workgroup Model

A workgroup model is a peer-to-peer network where each computer has equivalent capabilities and responsibilities. It is typically used in small networks.

**Example:** A small office network where all computers can share files and printers directly with each other.

### Server-Client Model :

In a server-client model, one central server provides resources and services to multiple client computers. This model is common in larger networks.

**Example:** A corporate network where a central server hosts applications, files, and data, which client computers access.

## 5. Commands :

1. `ipconfig` (cmd command): Displays the network configuration details of your computer, such as IP address, subnet mask, and default gateway.

   **Example:** Running `ipconfig` can help you find your computer's IP address.

2. `ncpa.cpl`: Opens the Network Connections window on a Windows computer, allowing you to view and manage network adapters.

   **Example:** Use `ncpa.cpl` to troubleshoot network connectivity issues.

3. `ping`: Checks the connectivity between two computers or IP addresses by sending packets and measuring response times.

   **Example:** `ping google.com` tests if your computer can reach Google's servers.

## 6. Sharing a File Through IP Addresses :

1. Right-click the file or folder you want to share.
2. Select "Share with".
3. Add "Everyone" to the list of people you want to share with.
4. Change permissions to "Read only" if you want others to only view the file without making changes.

## 7. Manage Advanced Sharing Service :

- **Advanced network settings:** Turn on public and private network discovery and file sharing.
- **Turn on network discovery:** Allows your computer to see other computers and devices on the network and makes your computer visible to others.

**Example:** To access a shared folder on another computer, you can type `\\(IP Address)` in the Run dialog or File Explorer address bar.

## 8. RDP: Remote Desktop Protocol
- Can take control of another remote desktop.
- You have to know how to give access and take access.

### 1. To give access:
- Go to Settings: Go to Remote Desktop settings: Turn it on: Remove the check mark: Require computers to authenticate to connect.
- Go to Remote Desktop users.
- Add - type "Everyone".
- Go to Run.
- Type `mstsc`.
- Enter the IP and connect.

### 2. To take access:
- Open the Run dialog by pressing `Win + R`.
- Type `mstsc` and press Enter. This will open the Remote Desktop Connection client.
- In the Remote Desktop Connection window, enter the IP address or hostname of the remote machine you want to connect to.
- Click "Connect".
- You will be prompted to enter the username and password for the remote machine.
- After entering the credentials, click "OK".
- You should now be connected to the remote desktop.
