Sonix SN9C2904S Exhibit A
===================================
File description
-----------------------------------  
###Firmware Update Application Guide_v2_0_0_03_01.pdf
1.Sonix Firmware Update Manual.

###Security.txt
1. Security description.

###fw_update.tar.gz
1. Firmware binary encryption file, use OpenSSL command to decryption.
2. command: openssl enc -d -aes256 -k sonix -in fw_update.tar.gz |tar xzf -

###SN9C2904S_Firmware.aes
1. BurnAP encryption file, use OpenSSL command to decryption.
2. command: openssl enc -d -aes-256-cbc -k sonix -in SN9C2904S_Firmware.aes  -out SN9C2904S_Firmware.bin

###Device_Config.ini
1. Reference file: Firmware Update Application Guide_v2_0_0_03_01.pdf

###COPYING
1. License description

###SerialNumber.txt
1. Serial number format and mask.