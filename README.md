# Mapping RDP Attempts using a SIEM
This lab project demonstrates one of the many uses of a security information and event management (SIEM) platform. 

Using Microsoft Azure, a VM is created to accept packets from all sources by turning off its firewall and other security measures put in place by default. This makes the VM act as a honeypot for remote attackers from around the world. 

Using a log analytics workspace, set up in Azure, log files with information about these remote desktop protocol (RDP) attempts are analyzed and sent to Microsoft Sentinel where the information is used to map the source destination of these incoming RDP requests on a world map. 

This lab was inspired and based off a video by [Josh Madakor](https://www.youtube.com/c/JoshMadakor) (YouTube).

Read the attached file for the full lab write-up.

![image](https://user-images.githubusercontent.com/91490989/157337685-243d1342-25c5-439a-93ef-5384ffddbfb7.png)
