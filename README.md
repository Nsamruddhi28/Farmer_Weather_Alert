# Farmer Weather Alert System (Cisco Packet Tracer)

This project simulates a simple and effective weather alert system for farmers using Cisco Packet Tracer.  
It delivers **rain warnings** to smartphones and PCs in rural villages via email and also one can access weather portal.

---

## Project Purpose
The system helps farmers receive early weather alerts so they can protect crops and equipment.  
It uses:

- Weather Server (Email + Web)
- DNS Server
- 2911 Router
- Switch
- Wi-Fi routers for 3 villages
- Smartphones, Laptops, and PCs
- Weather_Admin_PC for sending alerts

---

## Network Topology
### Figure 1: Overall Network Topology
![Topology](topology.png)

---

## Connectivity Test
### Figure 2: Ping Results (Village ↔ Server)
![Ping Test 1](ping1.png)
![Ping Test 2](ping2.png)

---

## Web-Based Weather Access
### Figure 3: Accessing Weather Alerts via DNS
![DNS Web Access](dns_webaccess.png)

### Figure 4: Viewing Weather Alerts on Server
![Server Web Access](server_webaccess.png)

---

## Email Alert Delivery
### Figure 5: Weather Alert Sent
![Mail Sent](mail_sent.png)

### Figure 6: Farmer Receiving Alert
![Mail Received](mail_received.png)

---

## How to Run
1. Open `project_weather.pkt` in Cisco Packet Tracer  
2. Open any smartphone → Email → Receive  
3. Weather_Admin_PC → Email → Compose → Send alerts  
4. Open browser on a PC/smartphone → type:  
   `http://weather.com`  
5. Run ping tests to verify network connectivity  

---

## Author
SAMRUDDHI VINOD NIKAM
