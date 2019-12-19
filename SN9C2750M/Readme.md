Sonix SN9C2750M Exhibit A
===================================
File description
-----------------------------------  
###Firmware Update Application Guide_v1.0.6.1.pdf
1.Sonix Firmware Update Manual.

###Security.txt
1. Security description.

###SN9C2750M_Firmware.aes
1. Firmware binary encryption file, use OpenSSL command to decryption.
2. command: openssl enc -aes-256-cbc -in SN9C2750M_Firmware.aes  -out SN9C2750M_Firmware.bin -d -k sonix

###Device_Config.ini
1. Reference file: Firmware Update Application Guide_v1.0.6.1.pdf

###BurnAP_std_V1.0.6.1.tar.gz
1. Firmware update tool source code, use OpenSSL command to decryption.
2. command: openssl enc -aes-256-cbc  -d -k sonix -in BurnAP_std_V1.0.6.1.tar.gz | tar xzf -

###COPYING
1. License description

###SerialNumber.txt
1. Serial number format and mask.
