# wifi-scanner
Python script to scan any kind of wireless network based on 2.4ghz using scapy Network layers 

# HOW_TO
1. Monitor mode neede to make your job done
2. Make sure scapy is installed n your machine

3. sudo airmon-ng start <your_Network_card_interface>
4. git clone https://github.com/secdev/scapy.git
5. cd scapy
6. sudo python setup.py install

# RUN
1. Use sudo python3 wifi-scanner.py <monitor mode_interface> \n
e.g sudo python3 wifi-scanner.py wlan1mon

# Enjoy
