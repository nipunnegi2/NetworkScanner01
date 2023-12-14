Network Scanner
Overview
The Network Scanner is a Python script that leverages the Scapy library to perform network scanning, discovering live hosts and retrieving their corresponding MAC addresses and vendors. The results are presented in a clear tabular format using PrettyTable, and MAC addresses are resolved to vendor names using MacLookup.

Features
Host Discovery: Utilizes ARP requests to discover live hosts on the network.
MAC Address and Vendor Lookup: Resolves MAC addresses to their corresponding vendors using MacLookup.
User-Friendly Output: Displays scan results in a formatted table for easy interpretation.
Prerequisites
Python 3.x
Scapy library: pip install scapy
MacLookup library: pip install mac_vendor_lookup
PrettyTable library: pip install prettytable
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/nipunnegi2/NetworkScanner01.git
cd network-scanner
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the script:

bash
Copy code
python netscan.py --h <target_ip(s)>
Example
bash
Copy code
python netscan.py --h 192.168.1.1 192.168.1.2
Contributing
Contributions are welcome! If you have suggestions, bug reports, or would like to add new features, please open an issue or create a pull request.

License
This project is licensed under the MIT License.
