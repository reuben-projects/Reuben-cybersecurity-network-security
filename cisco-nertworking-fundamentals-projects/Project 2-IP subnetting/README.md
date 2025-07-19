# Project 2: IP Subnetting

This project demonstrates how to design and apply IP subnetting for a small network.  
Subnetting is essential for efficient IP address allocation and network segmentation.

---

## 🧠 Objective

- Understand how to divide a large network into smaller subnetworks.
- Learn how to calculate subnet ranges, subnet masks, and host capacities.
- Practice assigning subnets to different departments or segments in a network.

---

## 🛠️ Tools Used

- Cisco Packet Tracer  
- IP Subnetting Calculator  
- Manual Calculation (Optional)

---

## 📌 Scenario

I am given a Class C network: `192.168.10.0/24`  
I am are required to divide it into **4 subnets** for different departments.

---

## 📐 Subnetting Details

| Subnet | Network Address | Subnet Mask   | Host Range             | Broadcast Address   |
|--------|------------------|----------------|-------------------------|---------------------|
| 1      | 192.168.10.0     | 255.255.255.192 (/26) | 192.168.10.1 - 192.168.10.62  | 192.168.10.63       |
| 2      | 192.168.10.64    | 255.255.255.192 (/26) | 192.168.10.65 - 192.168.10.126 | 192.168.10.127      |
| 3      | 192.168.10.128   | 255.255.255.192 (/26) | 192.168.10.129 - 192.168.10.190 | 192.168.10.191    |
| 4      | 192.168.10.192   | 255.255.255.192 (/26) | 192.168.10.193 - 192.168.10.254 | 192.168.10.255    |

---

## 🖼️ Media (Screenshots or Diagram)



---# 📁 Media Files – Project 2: IP Subnetting

### 🔌 Network Topology
- [Project 2 IP Subnetting Network Topology](./media/project%202%20IP%20subnetting%20network%20topology.png)

### 💻 IP Configuration Screenshots
- [IP Configuration – PC 0 ADMIN](./media/ip%20configuration%20pc%200%20ADMIN.png)
- [IP Configuration – PC 1 HR](./media/ip%20configuration%20pc%201%20HR.png)
- [IP Configuration – PC 2 IT](./media/ip%20configuration%20pc%202%20IT.png)
- [IP Configuration – PC 3 SALES](./media/ip%20configuration%20pc%203%20SALES.png)

### 📶 Ping Test Results
- [Ping Result – PC 0 ADMIN](./media/ping%20results%20pc%200%20ADMIN.png)
- [Ping Result – PC 1 HR](./media/ping%20results%20pc%201%20HR.png)
- [Ping Result – PC 2 IT](./media/ping%20results%20pc%202%20IT.png)

## 🚀 Implementation Steps

1. Calculate the required number of subnets.
2. Determine the new subnet mask based on required subnets.
3. Divide the network into subnet ranges.
4. Assign each subnet to a department (e.g., HR, IT, Finance, Admin).
5. Use Cisco Packet Tracer to simulate:
   - PCs in each subnet
   - Proper IP configuration
   - Ping tests between devices in the same and different subnets.

---

## ✅ Outcome

- Each department has its own subnet.
- No IP conflicts.
- Devices in the same subnet can communicate.
- Devices in different subnets require a router for communication.

---

## 📚 Lessons Learned

- Mastered the method for calculating subnet ranges.
- Understood the importance of subnetting in real-world networks.
- Practiced designing and implementing subnet structures in Cisco Packet Tracer.
