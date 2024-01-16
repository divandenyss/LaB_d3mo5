# attAck_d3mo5
This repo contains video illustrations of what happens in my labs behind the scenes, these are all for educational purposes only and should be used ethically. 

# Illustrating ZeroLogon, Domain Hash Dumping, and Remote Code Execution 
In this video, I will be using ZeroLogon to exploit the Domain Controller which would essentially give me no password access to dump hashes remotely on the Domain Controller. After obtaining hashes. I will be using a privileged users hash to remotely execute commands with psexec from adversary machine to Domain Controller. 

Top Left Corner: 
Zerologon is a vulnerability in the cryptography of Microsoft's Netlogon process that allows an attack against Microsoft Active Directory domain controllers. Zerologon makes it possible for a hacker to impersonate any computer, including the root domain controller. 

Top Right Corner: 
Secretsdump.py to dump all the hashes of the Target Domain Controller, this is where threat actors will obtain privileged credentials in their mission for Domain Dominance and Complete Destruction. 

Bottom Right Corner: 
Psexec.py to execute commands remotely from "Beachead" to Target Server. Psexec spawns a file on remote server as well as creates a service.


https://github.com/divandenyss/attAck_d3mo5/assets/156643542/8dfb9288-0691-429c-821e-98b38dc0ce90




# Capturing NTLMv2 Hashes with Responder.


https://github.com/divandenyss/att-ck_d3mo5/assets/156643542/751177c1-d9b9-46b3-bb2a-7098120a5a4d


# Utilising "crackmapexec" recently dubbed "netexec" 



https://github.com/divandenyss/att-ck_d3mo5/assets/156643542/386af929-2156-40b4-a8ed-7854d881dd53



