============================================================
Usage:
1. Install python 3 on windows.
2. Run cmd with elevated privilages and execute below commands:
	pip install netmiko
	pip install colorama
3. Make text file with name "device_ip.txt" and put on configs directory.
4. Add IP of cisco devices(Each ip in one line) to device_ip.txt file.
5. Put script to side of configs directory.
6. Add username and password of cisco device (privilage 15 required) into script.
	Switch ={ 
            'device_type': 'cisco_ios',
            "ip": ip_address,
            "username": "username",
            "password": "password"
            }
7. Run this command: python.exe script.py.
============================================================
Tested on:
	windows 11,23H2 (OS Build 22631.3447)
	AlmaLinux release 8.9 (Midnight Oncilla)
	Python 3.12.0
============================================================
Hamidreza Kohzadpour, 2024, kohzadpour@gmail.com
============================================================