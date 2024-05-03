# Prisma SD-WAN Zone Name Update (Preview)
"The aim of this script is to retrieve all security zones, apply any requested name changes, and then re-upload them. If no new name is provided, they will be disregarded.

#### License
MIT

#### Requirements
* Active CloudGenix Account - Please generate your API token and add it to cloudgenix_settings.py
* Python >=3.7

#### Installation:
 Scripts directory. 
 - **Github:** Download files to a local directory, manually run the scripts. 
 - pip install -r requirements.txt

### Examples of usage:
 Please generate your API token and add it to cloudgenix_settings.py
 
 1. ./get_zones.py
      - Will export a csv called Zones.csv
	  
 2. ./update_zones.py
      - Will import a csv called Zones.csv and apply any modifications you have done to the new zone name
	  
### Caveats and known issues:
 - This is a PREVIEW release, hiccups to be expected. Please file issues on Github for any problems.

#### Version
| Version | Build | Changes |
| ------- | ----- | ------- |
| **1.0.0** | **b1** | Initial Release. |


#### For more info
 * Get help and additional Prisma SD-WAN Documentation at <https://docs.paloaltonetworks.com/prisma/cloudgenix-sd-wan.html>
