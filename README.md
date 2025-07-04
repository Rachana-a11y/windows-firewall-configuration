
# Firewall Configuration and Traffic Filtering (Task 4)

**Cybersecurity Internship – Firewall Setup and Management**


## Objective

To demonstrate the ability to configure and manage basic firewall rules on Windows, enabling or blocking traffic on specific ports to enhance network security.

## Tools & Environment

- **Operating System**: Windows 7 (via VirtualBox)
- **Firewall Utility**: Windows Firewall with Advanced Security
- **Browser**: Google Chrome (installed manually)
- **Testing Tool**: Telnet / Command Prompt
- **Virtualization**: Oracle VirtualBox


## ⚙️ Implementation Steps

### 1. Open Windows Firewall

- Navigated to:
Control Panel → System and Security → Windows Firewall

- Accessed the **Advanced Settings** to configure inbound/outbound rules.

### 2. Review Existing Rules

- Inspected current inbound and outbound rules to identify default behavior.

### 3. Block Inbound Traffic on Port 23 (Telnet)

- Created a new **Inbound Rule** with the following parameters:
- **Rule Type**: Port
- **Protocol**: TCP
- **Port**: 23
- **Action**: Block the connection
- **Profile**: Domain, Private, Public
- **Name**: Block Telnet (Port 23)

### 4. Test the Rule

- Verified the rule by attempting a Telnet connection.
- Confirmed the traffic was successfully blocked.

### 5. Restore Original State

- Removed the custom rule to return the firewall to its default configuration.


## Key Concepts Demonstrated

- Understanding of firewall interfaces and rule creation.
- Blocking unsecured ports to reduce attack surface.
- Importance of inbound traffic management.
- Basic Windows firewall rule lifecycle (create, test, delete).


Visual evidence of firewall configuration and testing attached in screenshots folder[Results](screenshots).
