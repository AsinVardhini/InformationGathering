# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## output
![Screenshot from 2023-08-31 08-47-55](https://github.com/AsinVardhini/InformationGathering/assets/119417735/4edc4631-6c89-46bf-bf6b-735229badfd7)

## Finding IP address:

ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
![image](https://github.com/AsinVardhini/InformationGathering/assets/119417735/68d7d69e-41bc-43f0-8bd0-1a3a10fa94d5)

## FINDING THE HOSTING COMPANY :
```
https://www.ip2location.com/demo/13.33.146.98
```
![image](https://github.com/AsinVardhini/InformationGathering/assets/119417735/1e2d2720-cb2d-40dd-b033-be5424e75c0f)

## WEB ARCHIVE (HISTORY OF THE WEBSITE) :
```
https://web.archive.org/details/freshworks.com
```
![image](https://github.com/AsinVardhini/InformationGathering/assets/119417735/cae7ad50-0db0-4ff6-a4e9-d876a16f3310)

## NMAP :
```
nmap -p 21 -sV --script=banner 13.33.146.98
```
![image](https://github.com/AsinVardhini/InformationGathering/assets/119417735/47765673-7930-46f7-9933-dbfd6ae94c33)

## WHATWEB :
```
whatweb freshworks.com
```
![image](https://github.com/AsinVardhini/InformationGathering/assets/119417735/1ff75b90-6bf3-40cf-902d-f7527d2ae275)
```
whatweb -v freshworks.com
```
![image](https://github.com/AsinVardhini/InformationGathering/assets/119417735/97ed7f82-705d-4ab7-85e9-44eafc697a29)
## HTTPRINT :
```
httprint -h 13.33.146.98 -s /usr/share/httprint/signatures.txt -P0 |more
```
![image](https://github.com/AsinVardhini/InformationGathering/assets/119417735/a0999212-12b5-4eac-9ed0-fa454a4465fd)
### TRACEOUT :
## TCP TRACEOUT :
```
 sudo traceroute -T www.freshworks.com
```
![image](https://github.com/AsinVardhini/InformationGathering/assets/119417735/da148908-aac3-44fa-9180-e4545e7e63c6)

## UDP TRACEOUT :
```
sudo traceroute -U www.freshworks.com
```
![image](https://github.com/AsinVardhini/InformationGathering/assets/119417735/f0c8d421-8cac-45ff-9ec3-a2a23465b88d)
## ICMP TRACEOUT :
```
 sudo traceroute  www.freshworks.com
```
![image](https://github.com/AsinVardhini/InformationGathering/assets/119417735/28665b8c-4679-497a-9a55-3167c3fada32)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
