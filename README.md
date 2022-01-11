# ransomware-poc

The key used for encryption is hard coded. In order to generate your own key use "openssl rand -base64 32" in your command line.
The ransomware is configured to only encrypt the Downloads Folder.
This script only works against Linux systems.
This script is easily detected by any antivirus (including Windows Defender). 

This project was created to show the vulnerability the os.system function has. Calling os.system does not require any credentials or privileges. 
Websites and Applications that import the os library are vulnerability to command injection via the method demonstrated in this script.
