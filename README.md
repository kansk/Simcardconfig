# Simcardconfig - Instruction to follow to program or view SIM SQN Infromation.

Please untar the uicc-v1.4.tar
Navigate to UICC-v1.4 folder

> $root@ubuntu:~/openairinterface5g/oai/uicc-v1.4# ./program_uicc --adm 22517657 --opc 504f20634f6320504f50206363500a4f --key 6874736969202073796d4b2079650a73 --spn openairinterface --authenticate

> Existing values in USIM
ICCID: 89860061100000000001
WARNING: iccid luhn encoding of last digit not done
USIM IMSI: 208920100001101
USIM MSISDN: 00000001
USIM Service Provider Name: openairinterface
Setting new values
Read new values in UICC
ICCID: 89860061100000000001
WARNING: iccid luhn encoding of last digit not done
USIM IMSI: 208920100001101
USIM MSISDN: 00000001
USIM Service Provider Name: openairinterface
Succeeded to authentify with SQN: 96
set HSS SQN value as: 128

## Note: 
Whenever SIM card pluged in to the 4G Handset. SQN number to be updated in the SIM Card and also in the DB OAI_DB. Please follow the above sequence after inserting the SIM card into the phone and before turning the Handset ON.


