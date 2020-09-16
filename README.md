# mikrotik-office365-rsc
Mikrotik Address List for Microsoft Office 365

Collects list of IPs from *Office 365 IP Address and URL web service* and generates .rsc file to be imported to Mirktorik.


***Pre-requisites:***

Python 3.5 or above


***Usage:***

`git clone https://github.com/vzhilov/mikrotik-office365-rsc
cd mikrotik-office365-rsc
python o365.py`

Transfer newly generated o365.rsc to your Mikrotik device and run:
`/import o365.rsc`

---
Used links:
* https://docs.microsoft.com/en-US/microsoft-365/enterprise/microsoft-365-ip-web-service?view=o365-worldwide
* https://github.com/fillorkill/o365addrlist
