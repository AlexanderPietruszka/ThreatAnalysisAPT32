<h1>Threat Analysis</h1>

<h2>Description</h2>
Project consists of researching APT32 through security vendor reports and other sites. The found information is then organized into models for more effective dissemination of information. This project summarizes the common attack vectors of the group, reconnaissance methods, payloads, and motivation.

<h2>Project Summary:</h2>


<h3>Aggregate data from sources that have come into contact with APT32</h3>
https://attack.mitre.org/groups/G0050 <br/>
http://www.mandiant.com/resources/blog/apt32-targeting-chinese-government-in-covid-19-related-espionage <br/>
http://www.mandiant.com/resources/blog/cyber-espionage-apt32 <br/>
https://www.cybereason.com/blog/operation-cobalt-kitty-apt <br/>
https://www.welivesecurity.com/2018/11/20/oceanlotus-new-watering-hole-attack-southeast-asia <br/>
https://s.tencent.com/research/report/471.html <br/>
https://www.recordedfuture.com/apt32-malware-campaign <br/>
https://unit42.paloaltonetworks.com/tracking-oceanlotus-new-downloader-kerrdown <br/>
https://www.trendmicro.com/en_us/research/20/k/new-macos-backdoor-connected-to-oceanlotus-surfaces.html <br/>

<br/><h3>Write up of general attacks</h3>

APT 32 is a suspected Vietnamese hacking group that is also commonly referred to by 
the alias OceanLotus. APT 32 has targeted many victims both internationally and domestically. 
APT 32 has targeted Vietnamese, European, US, Southeast Asian, and Chinese organizations.
While APT 32 is only suspected of being sponsored by the Vietnamese government, certain aspects of the group point towards this fact. The group is most active within the 
Asia-Pacific region, where it targets organizations with connections to Vietnam. Certain political objectives of the group are aligned with Vietnam’s interests, such as when 
the group targeted Cambodian government officials following their increased partnerships with 
China. The estimated working hours of the group are 9 AM to 6 PM Indochina Time, which matches with typical Vietnamese working hours. <br/>
APT 32 focuses on stealing confidential information from the organizations it targets. It 
does this by utilizing many malware packages: Windshield, Komprogo, Soundbite, and Phoreal. 
They also use altered publicly penetration testing software Beacon and use public cloud service 
providers. APT 32’s signature method of attack is a spearphishing attack to
gain initial access to a system. They also implement other methods of social engineering, such as watering hole attacks and social media phishing.
Once the victim has fallen for APT 32’s social engineering attack, the group inserts one 
of their malicious payloads into the device. APT 32’s malware allows them to insert backdoors 
into users’ devices and access elevated privileges on their devices. APT 32 has implemented certain techniques to obscure these packages from traditional 
security measures. They have masked their payloads
by spoofing legitimate Microsoft services, changed the names 
of their backdoors to mimic legitimate services by adding non-visible characters to the name, used fileless malware, and DNS tunneling to mask their fraudulent network traffic as 
legitimate traffic.
<br/>
<br/><h3>Establish a Diamond Model to establish an overview of APT32</h3>
<img src="https://github.com/AlexanderPietruszka/ThreatAnalysisAPT32/assets/100098304/7f130cdc-191b-4b6c-b3ba-7d31134e34e3" height="80%" width="80%" alt="Diamond Model"/>
<br/>

<h3>Create Kill Chain model</h3>
<img src="https://github.com/AlexanderPietruszka/ThreatAnalysisAPT32/assets/100098304/9dd34fe5-3f62-43fc-8f51-b892b2981d76" height="80%" width="80%" alt="Cyber Kill Chain"/>
<br/><h2>Payload Analysis:</h2>
<br/><h3>Open Malware Analysis Software</h3>
<img src="https://github.com/AlexanderPietruszka/ThreatAnalysisAPT32/assets/100098304/2cb542e0-ae85-4642-bfa8-25bca63ad988" height="80%" width="80%" alt="REMLinux"/>

<br/><h3>Retrieve Sample File</h3>
APT32 WINDSHIELD malware retrieved courtesy of https://github.com/ytisf/theZoo

<br/><h3>Check Malware Using Security Vendors</h3>
<img src="https://github.com/AlexanderPietruszka/ThreatAnalysisAPT32/assets/100098304/e46fa3e3-dffe-460e-8e5f-153f5e50419b" height="80%" width="80%" alt="Creating malware hash"/>
<img src="https://github.com/AlexanderPietruszka/ThreatAnalysisAPT32/assets/100098304/e30588f5-ae8e-4cf3-aa9c-9abecb97391e" height="80%" width="80%" alt="VirusTotal Results"/>

<br/><h3>Aalysis of Test File</h3>


<br/><h3>Sandbox</h3>


