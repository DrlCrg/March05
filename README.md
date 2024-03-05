# March05
This is what I did in Pentest Class

Today I finised up the OWASP room on TryHackMe. 
![Screenshot 2024-03-04 181908](https://github.com/DrlCrg/March05/assets/160629376/a72f24f1-1f08-4a5e-9582-cbbbba692a06)

##Some notable events: 
Task 8 had me use a web based hash cracker. Alternatively I could use hashcat on Kali Linux. The web based hash cracker is pretty straightforward so I decided I would mess around with hashcat.

![Screenshot 2024-03-05 100824](https://github.com/DrlCrg/March05/assets/160629376/a58e752a-68d0-4e90-a66e-94b3dbb6c1f7)
This was eye opening.

Task 14 had me do a Remote Code Execution. I used searchsploit to find what I needed because I couldn't find it on the exploit database for some reason.

![Screenshot 2024-03-05 142352](https://github.com/DrlCrg/March05/assets/160629376/6e7bf29d-cf9d-4d91-9128-66b8901d8bb7)

During Task 17 I had to re-register an already existing account to get around their login page.

![Screenshot 2024-03-05 142258](https://github.com/DrlCrg/March05/assets/160629376/76d50ef3-5199-4a65-82b1-4b4a2921f09d)
thanks darren

Task 20 was fun, here I performed some cookie manipulation.

![Screenshot 2024-03-05 150311](https://github.com/DrlCrg/March05/assets/160629376/fe889e5e-8caf-4ba6-a473-2f5eec701169)
I used the web development tools so I could edit the JSON Web Token (JWT) values so I could trick the server into thinking I was the Admin.

![Screenshot 2024-03-05 150318](https://github.com/DrlCrg/March05/assets/160629376/f5e3c5b7-787e-4b99-9222-3711735d2b7c)
This required some work encoding/decoding Base64. Also I left out a "." and that mistake cost me so much time.

Finally the last task (22) had me use netcat to find the flag. This took way too long because I had trouble connecting to the vpn.

Afterwards I worked on some interview prep for my interview with Sentrillion. 
