# Systems-Hardening

## Steps


 ![image](https://github.com/user-attachments/assets/2631ad18-e992-437c-a004-8fb82b93dab6)

I updated the system, and checked the status of the firewall, which I later enabled.
 ![image](https://github.com/user-attachments/assets/97b71897-66d6-4747-a587-be18e71f7f1d)

I updated the rules of the firewall, changing the defaults and allowing certain incoming and outgoing ports. The results for the verbose output is shown above.
 ![image](https://github.com/user-attachments/assets/b81ad53a-22b8-4f31-9af8-0dd4ec404138)

I checked the programs that were running on the machine, purged a program called samba, and also disabled a program named nginx. 
![image](https://github.com/user-attachments/assets/b290a812-d783-4c48-ac2f-0a930b2ccad8)

 
Dunnxter and Orlando were missing passwords, and so I created new passwords for them. 








CIS CAT Report
Looking at the assessment results on the report, I noticed that the system failed quite a lot of benchmarks. In particular the system seems to have done pretty badly when it comes to the “File system Integrity Checking” section, where it failed both of the benchmarks. 
 ![image](https://github.com/user-attachments/assets/edd69664-3022-45f0-ac5c-7cd6080bd761)

This might be something that we could improve on to further harden the system, since the integrity of a file is pretty important. 
Another section that the system did pretty badly on is the secure boot settings. 
 ![image](https://github.com/user-attachments/assets/eb206444-0383-4257-8682-32062e8c510c)

Secure boot can be pretty important for the security of a machine, since it ensures that the computer doesn’t boot up with untrusted software. Ensuring some of these things are in place could help to further harden the system. 
There were also some problems when it comes to the Network Parameters sections. 
 ![image](https://github.com/user-attachments/assets/d35c49de-3ece-4365-b8df-18cfa23a2567)

As we can see, the system failed at quite a lot of these tests, one of the most concerning being that the system failed the test for ensuring that suspicious packets were logged. Without this safety precaution in place, it would be very hard for a cybersecurity professional to figure out what happened during an incident. 




