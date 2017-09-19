# Network Management, Antivirus, Firewall, Wifi, Monitoring and Logs


### Introduction
This module is designed to be an introduction to some of the major tools and features that are available for a champion to begin implementing basic control of networks and security software within their organisations. It is a huge and complex topic, that would probably take weeks to address effectively. The idea is to highlight major tools and concepts, so that they can consider further exploration of them at some point in future. Also, the aim is to equip them with the basic knowledge that will allow champions to be able to understand and ask questions to effectively manage others will more expert skills in this area - outside consultants etc.

### Learning Goals  
* Understand a basic network architecture

### Assessment Goals    
* Have a map of their network architecture

### Recommend Preparations  
N/A

### Suggested Time 
75 minutes with 10 minute break 

### Notes   
N/A

## Activity 
Ask participants to split into groups and draw network maps of all the tools, software and devices that they operate in their organisation.

    
***Scenarios***  
(Trainer Note: this might be best used at the ed of the module):
    
    
## Discussion  
* What type of network is used by each organisation that the participants are from?
 
## Inputs   

![Zenmap](img/network/zenmap.png)

***Networking Mapping with Nmap/Zenmap GUI/Maltego***


Highlight the management features of tools such as :    

![Cloudron](img/network/cloudron.png)

![Sandstorm](img/network/sandstorm.png)  

## Deepening    
***Antivirus, Firewalls and Intrusion Detection Systems***
![Tech Soup](img/network/techsoup.png)

![Norton Small Business](img/network/norton.jpeg)

One method for penetration an organisation is through attacks on WiFI. These mainly take two forms, attacks on weak WiFi security and the use of rogue access points. 

Some methods to reduce WiFi risk include:

* Attacks on weak wifi security usually involve routers usinig a weak protocol such as WEP. It is best to set your routers to WPA2 if possible.  
* Change the WiFi name (SSID) to something that is not easily recognisable as connecting to your organisation.
* If possiible, have a second wifi connection for public or visitors with a different SSID and password.
* WiFI passwords should be strong and of an appropriate length (e.g more than 12 characters with a mix of numbers, letters, uppercase/lower case etc)
* Ensure the SSID and passwords are changed on a regular basis
* Monitor the number of devices on your WiFi
* Use a MAC address filter which devices can connect (though this can be spoofed)
* Using a wired ethernet connection
* Utilise a VPN

![WiFi Pineapple](img/network/pineapple.png)    
*Example of a WiFI Pineapple - a popular rogue access point*

Another potential risk is from rogue access points. These are routers, phones or laptops that have been placed near to your home and residence in order to try to gain access to your network or man-in-the-middle your communication. The utilise a number of methods to try to do this, such as creating a fake WiFi network with the same or similar name to your real network. 

Some of the easiest ways to reduce the risks from rougue access points are:

* Check for any SSIDs that are similar to ones used in your office.
* Ensure your router strength only broadcasts over the areas that you need it (for example, the office) and not further than necessary (e.g other parts of the building where someone could try to connect easily without being discovered). Test this by mapping out the location of WiFi devices in your building using a tool such as [Netspot](https://www.netspotapp.com), [NetStumbler](http://www.stumbler.net) or [Airmon-ng](https://www.aircrack-ng.org/)
* Monitor your physical space for equipment that should not be present (for example, rogue access points hidden in a roof or cupboard).
* If using network authentication, use certicates to limit the ability of any rouge access point.
* Use tools such as [Nessus](https://www.tenable.com) to scan the network to look for known rogue access point tools.


## Synthesis 
Participants should turn to their assessment documentation and consider how their organisation deals with the subject matter covered in this module. Where necessary they should ask questions and work with other participants to identify any:
 
* Issues they have found that effect their organisations
* Possible solutions they have learned
* Possible difficulties they may face in implementation (ideally using the time ad experience of trainers and other participants)
* Things would need to overcome these difficulties
* Connections to other organisations or individuals that would help them
* Timeline, resources and costs for implementation

This should be noted in their assessment, for future use.

## Resources    
* [SAFETAG, "Network Scanning," Page 60](https://www.safetag.org)
* [Guide for System Administrators in At‐Risk Organizations: "Network Security"](https://github.com/OpenInternet/System_Administrator_Guide_Text/blob/master/en/best_practices/network_security/index.md)
* [NIST: "Guide to General Server Security"](http://csrc.nist.gov/publications/nistpubs/800-123/SP800-123.pdf)
* [NIST: "An Introduction to Computer Security"](http://csrc.nist.gov/publications/nistpubs/800-12/handbook.pdf)
* [NIST: "Guide to Intrusion Detection and Prevention Systems (IDPS)""](http://csrc.nist.gov/publications/nistpubs/800-94/SP800-94.pdf)
* [SANS "Critical Security Controls"](https://www.sans.org/critical-security-controls/controls)
* [SANS "Detecting and Preventing Rogue Devices on the
Network"](https://www.sans.org/reading-room/whitepapers/detection/detecting-preventing-rogue-devices-network-1866) 
* [Information Ecology: Public Wireless](https://0xacab.org/iecology/security-checklists/blob/master/6_public_wireless_checklist.md)

        