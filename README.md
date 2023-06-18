# Dataset Description
This project includes the CSV files of our new dataset for network attacks in an IoT network environment (with a focus on Botnet attacks).
In order to create this dataset, we have simulated a virtual network environment using GNS3. 
## 1. Normal traffic generation
For normal traffic generation, we used multiple virtual machine that were supposed to mimic the behavior of real network users. It consisted of 3 Ubuntu VMs that served as users and another Ubuntu VM that played the role of a local server providing services such as web site hosting and file sharing using FTP. We also used an Ubuntu VM to run IoT-Flock, an IoT devices simulation tool. We used it to simulate the following devices: Light intensity sensor, Temperature sensor, Smoke sensor, Door lock, Fan speed controller.
## 2. Attack scenarios
As for the attack scenarios, we used a botnet composed of multiple VMs controlled by a Kali virtual machine. This botnet was able to launch a variety of network attacks on the local server described above. These attacks included the following: HTTP GET flood, HTTP POST flood, ICMP flood, TCP SYN flood, UDP flood, Port scanning and Brute force.
## 3. Data capture
To capture the network trafic in our environment, we used a flow capture tool called CICFlowmeter.

