# AutomatedPcapXray
The main source of this repository is from https://github.com/Srinivas11789/PcapXray
I have tried to automate the analysis of this tool and removed GUI.\
After cloning this repository there are few chages that are need to be done, in user_interface.py change self.pcap_file and self.destination_report as per your choice
and in plot_lan_network.py and change pcapfile as done in user_interface.py

Before cloning this repository install few requirements using

sudo apt install python3-pip
sudo apt install python3-tk
sudo apt install graphviz
sudo apt install python3-pil python3-pil.imagetk


Clone this repository using

git clone https://github.com/ramz-021002/AutomatedPcapXray.git 


After cloning the repository install the requirements using pip

sudo pip3 install -r requirements.txt


You can use zeek to capture packets and load them directly using the above modifications and run this tool using python
Change the directory to AutomatedPcapXray

cd AutomatedPcapXray/

Run main.py

sudo python3 main.py
