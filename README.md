# Configure-DHCP-service-in-RHEL

### DHCP Server (Dynamic Host Configuration Protocol Server)

A DHCP server is a network service that automatically provides IP addresses and other network configuration details (like subnet mask, gateway, and DNS servers) to devices on a network. This eliminates the need for manually assigning IP addresses to each device..

### Key Benefits:
1.Automatic IP Assignment – Reduces manual work and prevents IP conflicts.

2.Lease Time Management – IP addresses are assigned temporarily (lease) and can be renewed.

3.Centralized Configuration – All network settings can be managed from one server.

### How It Works
1.Device Request (DHCP Discover): When a device (like a computer or phone) connects to the network, it sends a broadcast message asking for an IP address.

2.DHCP Offer: The DHCP server responds with an available IP address and configuration details.

3.DHCP Request: The device accepts the offer and requests to use that IP.

4.DHCP Acknowledgement: The DHCP server confirms and leases the IP to the device for a certain period.

### Step 1

#### i.Create Repo file
<img width="666" height="331" alt="1" src="https://github.com/user-attachments/assets/50dc559b-3c73-41b2-9577-5e50fb464dea" />
<img width="682" height="360" alt="2" src="https://github.com/user-attachments/assets/398c34a5-e514-4b92-b7fe-76e974eae522" />

### Step 2
#### i.Install DHCP service
<img width="686" height="482" alt="3" src="https://github.com/user-attachments/assets/94700c4c-2942-4220-a35e-f40066c77262" />

#### ii.Update DHCP configuration file
<img width="668" height="471" alt="4" src="https://github.com/user-attachments/assets/85876031-1253-4757-b6dd-d6cb918bc5e1" />
<img width="668" height="460" alt="5" src="https://github.com/user-attachments/assets/c225e0bb-02ac-4d49-b686-5a499b43bf9a" />
<img width="678" height="471" alt="6" src="https://github.com/user-attachments/assets/ac2f2ed0-74dd-486f-b4ac-f3b8ee1e6d22" />

### Step 3
#### i.Start and Enable DHCP service
<img width="676" height="471" alt="7" src="https://github.com/user-attachments/assets/73fbbf15-c8ab-40a7-8419-54e43a369181" />

#### Step 4
#### i.Add DHCP service into firewall
<img width="675" height="377" alt="8" src="https://github.com/user-attachments/assets/ca7abb10-56d4-4255-a30d-13850f37bd2c" />

### Step 5
#### i.Open the client machine
#### ii.Check the connection
<img width="683" height="273" alt="9" src="https://github.com/user-attachments/assets/b1c01047-c0ac-4c84-909a-c473324a92e2" />

#### iii.Activate the connection
<img width="678" height="314" alt="10" src="https://github.com/user-attachments/assets/cc631343-1cb5-46b6-8ca9-a694625ed2f3" />

#### iv.Check the IP address
<img width="671" height="467" alt="11" src="https://github.com/user-attachments/assets/6538c16d-c3fc-42f4-b7ce-4b62e82c03da" />

#### Here you can see the IP address is automatically assigned to the client machine 






