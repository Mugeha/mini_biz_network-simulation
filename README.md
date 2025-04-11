🧾Mini BizNet
⚡ Mini BizNet – Small Office Network Simulation

Mini BizNet is a simple but powerful network simulation built using Cisco Packet Tracer. 
It mimics the real-world setup of a small business network with VLANs, DHCP, and secure router access — ideal for anyone learning basic networking skills.

🧠 What This Project Covers

- 📡 DHCP configuration for dynamic IP allocation  
- 🌐 VLANs for department segmentation (Sales, HR, Admin)  
- 🔒 Router security: SSH access + local user login  
- 🖧 Basic device connectivity via Switch & Router  
- 🧪 Network testing using `ping`  
- 💻 CLI commands for routing/switching setup

> All PCs receive IPs dynamically via DHCP.  
> Router handles VLAN subinterfaces for inter-VLAN routing and SSH login.

---

🗂️ VLAN & IP Schema

| VLAN | Dept  | Subnet           | Router IP       | DHCP Range             |
|------|-------|------------------|------------------|-------------------------|
| 10   | Sales | 192.168.10.0/24  | 192.168.10.1     | 192.168.10.100–199     |
| 20   | HR    | 192.168.20.0/24  | 192.168.20.1     | 192.168.20.100–199     |

---

🔧 Tools Used

- Cisco Packet Tracer
- CLI (Command Line Interface)
  
🚀 How to Run It

1. Clone this repo or download the `.pkt` file
2. Open `minibiz.pkt` using Cisco Packet Tracer
3. Hit **Power On All Devices**
4. Open PC terminal and ping across VLANs
5. Try SSH into the router:
   ```bash
   ssh -l admin 192.168.10.1
🔐 SSH Login Details
Username: admin

Password: Pa$$w0rd123 (or whatever you set)

Router Hostname: MiniBizRouter

Domain: minibiz.local

🙌 Credits
Built by Mugeha — learning one packet at a time.                                                                                                              
