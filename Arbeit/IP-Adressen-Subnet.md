|Problem 1
|:---------------------------------|-------------|---------|
|Host IP Address                   |172.30.1.30  |B-Klasse |
|Subnet Mask                       |255.255.255.0|         |
|Network Mask                      |255.255.0.0  |B-Klasse |
|Number of Subnet Bits             |8            |         |
|Number of Subnets                 |2^8 = 256    |         |
|Number of Hostbits per Subnet     |8            |         |
|Number of Usable Hosts per Subnet |2^8 - 2 = 254|         |
|Subnet Address for this IP Address|172.30.1.0   |         |
|IP Address of First Host Subnet   |172.30.1.1   |         |
|IP Address of Last Host Subnet    |172.30.1.254 |         |
|Broadcast Address of this Subnet  |172.30.1.255 |         |

---

|Problem 2
|:---------------------------------|---------------|--------|
|Host IP Address                   |172.30.1.33    |B-Klasse|
|Subnet Mask                       |255.255.255.252|        |
|Network Mask                      |255.255.0.0    |B-Klasse|
|Number of Subnet Bits             |14             |        |
|Number of Subnets                 |2^14 = 16384   |        |
|Number of Hostbits per Subnet     |2              |        |
|Number of Usable Hosts per Subnet |2 (2^2-2)      |        |
|Subnet Address for this IP Address|172.30.1.32    |        |
|IP Address of First Host Subnet   |172.30.1.33    |        |
|IP Address of Last Host Subnet    |172.30.1.34    |        |
|Broadcast Address of this Subnet  |172.30.1.35    |        |


---

| Problem 3
|:---------------------------------|--------------|---------------------------------------|
|Host IP Address                   |192.192.10.234|C-Klasse                               |
|Subnet Mask                       |255.255.255.0 |Da es das Gleiche wie Network ist oder?|
|Network Mask                      |255.255.255.0 |                                       |
|Number of Subnet Bits             |0             |                                       |
|Number of Subnets                 |0             |                                       |
|Number of Hostbits per Subnet     |8             |                                       |
|Number of Usable Hosts per Subnet |2^8 - 2 = 254 |                                       |
|Subnet Address for this IP Address|192.192.10.0  |                                       |
|IP Address of First Host Subnet   |192.192.10.1  |                                       |
|IP Address of Last Host Subnet    |192.192.10.254|                                       |
|Broadcast Address of this Subnet  |192.192.10.255|                                       |

---

| Problem 4
|:---------------------------------|---------------|---------------------------------------|
|Host IP Address                   |172.17.99.71   |B-Klasse                               |
|Subnet Mask                       |255.255.255.0  |Ist das Gleiche wie Network            |
|Network Mask                      |255.255.255.0  |B-Klasse                               |
|Number of Subnet Bits             |0              |Da es das Gleiche wie Network ist oder?|
|Number of Subnets                 |0              |                                       |
|Number of Hostbits per Subnet     |16             |                                       |
|Number of Usable Hosts per Subnet |2^16-2         |                                       |
|Subnet Address for this IP Address|172.17.0.0     |                                       |
|IP Address of First Host Subnet   |172.17.0.1     |                                       |
|IP Address of Last Host Subnet    |172.17.255.254 |                                       |
|Broadcast Address of this Subnet  |172.17.255.255 |                                       |

---

| Problem 5
|:---------------------------------|-------------|---------------------------------------|
|Host IP Address                   |192.168.3.219|C-Klasse                               |
|Subnet Mask                       |255.255.255.0|Ist das Gleiche wie Network            |
|Network Mask                      |255.255.255.0|C-Klasse                               |
|Number of Subnet Bits             |0            |Da es das Gleiche wie Network ist oder?|
|Number of Subnets                 |0            |                                       |
|Number of Hostbits per Subnet     |8            |                                       |
|Number of Usable Hosts per Subnet |2^8-2 = 254  |                                       |
|Subnet Address for this IP Address|192.168.3.0  |                                       |
|IP Address of First Host Subnet   |192.168.3.1  |                                       |
|IP Address of Last Host Subnet    |192.168.3.254|                                       |
|Broadcast Address of this Subnet  |192.168.3.255|                                       |

---

|Problem 6
|:---------------------------------|---------------|--------|
|Host IP Address                   |192.168.3.219  |C-Klasse|
|Subnet Mask                       |255.255.255.252|        |
|Network Mask                      |255.255.255.0  |C-Klasse|
|Number of Subnet Bits             |14             |        |
|Number of Subnets                 |2^14           |        |
|Number of Hostbits per Subnet     |2              |        |
|Number of Usable Hosts per Subnet |2 (2^2 - 2)    |        |
|Subnet Address for this IP Address|192.168.3.216  |        |
|IP Address of First Host Subnet   |192.168.3.217  |        |
|IP Address of Last Host Subnet    |192.168.3.218  |        |
|Broadcast Address of this Subnet  |192.168.3.219  |        |
