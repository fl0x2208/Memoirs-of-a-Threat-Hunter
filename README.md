# Memoirs-of-a-Threat-Hunter
My personal experience in Threat Hunting and knowledge gained so far.

I am an independent security researcher, with professional experience in Security Consultation, Social Engineering, Digital Forensics and Incident Response (DFIR) and Threat Intelligence. 9 years of experience in working with Incident Response and Security Operations Centre (SOC) of multi-national companies. 

I remember back in 1996, during my school days, came across a flaw in PPPoE implementation of our internet service provider where you can use credentials of anybody and access their internet connection. Having internet connection at that time was a luxury in India and I was one of the unfortunate ones. Let me make it clear that I never used the internet connection illegally. I advised about the flaw to a friend who happened to own a cyber café and make sure he communicates this to the service provider. This is when my curiosity turned into passion and I started to learn about network and security.

During this research, I came across and article in news about a bank in UK and issues they faced due to a simple error made by their Firewall engineer. The bank was supposed to introduce ATM and the engineer was responsible to make sure there are no network issues. That time, Firewall engineers used to have a printed form with checklists of the changes that are to be made on Firewall. The form had 2 options – Allow all traffic or deny all traffic. Likely, in hurry, option 2 was selected and all the traffic was denied by firewall. When the customers actually tried using ATM, there were not able to withdraw or perform any transaction. Bank realised after couple of hours, however, the issue affected bank’s reputation. This is when I realised how important one option is.

My research and learning continued and came across a buzz word or a technique that most organisations now are fighting – HACKING. Hackers, people with extensive knowledge of systems. In old days, hacking was more considered as hobby or only performed by few individuals who just want to test their skills and/or system. But, now these days the knowledge of hacking has become driver for financial gain, damaging one’s reputation/brand, corporate espionage and sometimes just for fun and/or fame. From, hobbyist to hackers to threats. 

Organisations are now aware of these threats and constantly deploying security mechanisms to defend themselves. Forensics and Incident Response and Penetration Testing – Red team, Blue Team, Tiger Team etc. were created to identify and investigate what happen via forensics and Incident Response and testing their network security via Penetration testing.

These techniques expanded and created a new buzz word THREAT HUNTING where by experienced analysts in Incident Response, Forensics, Malware research etc. used their knowledge to detect threats within their organisation that cannot be detected by implemented security controls.

I have worked as Incident Responder and as SOC Analysts and when I started reading more about Threat Hunting I realised this is something I am already doing. However, I had limitations. When you are an Incident Responder you are investigating a specific scenario or incident after it has been detected/identified. Similar goes to SOC analysts, however they are remote. What I call this was more reactive approach. 

I always faced issues in understanding complete picture especially as a SOC analyst. You heavily rely on logs and how good your SIEM rules are. There are many instances where correct logs are not even being logged to detect a threat. Yes there are SOC who performs threat hunting for their organisation or customer, however, in my experience I have seen all concentrating on identifying known indicators of compromise and normally follow these steps:

    1. Collect Indicators of Compromise – Basic/Advanced Threat intelligence platform – Yes I have collected Indicators of               compromise from all over world than what ?
    2. Compare the IOCs with internal logs – SIEM – to understand the extent of infection – lateral movements as we say. One can also use specific tools for this – carbon black, palantir, dark trace etc.
    3. Detect and mitigation – most of the time by running anti-virus and/or restoring the system from backup or re-installing a fresh copy or tuning security controls.

Threat hunting gave meaning to another approach - pro-active approach – where team of experience Incident Responders/ Analysts/Hunt Team will dive into logs and organisation network to identify anomalies and/or unwanted entities within a network. The days of external organisations notifying you of an infection or data exfil or their own data showing up on pastebin are increasing and organisation must have Threat Hunting capabilities well invested and implemented. Proper Process and procedure are important as well in understanding how to perform these duties. 

Threat hunting goes beyond just deploying a product within the network and responding based on what it alerts. It goes beyond normal rule and/or signature based mechanisms to detect threats that one cannot detect with just plug-n-play devices. Both requires human factor to perform these actions. Deep diving into the networks and looking for adversaries (active defense and/or pro-active investigations) is a must have within the organisation.

Threat Hunting phases as per Sqrrl:

    1. Create and/or define Hypotheses
    2. Investigate via tools and techniques
    3. Identify new patterns and TTP (Tools, techniques and procedure)
    4. Inform and update analytics platform and/or database
    5. Start 1

In this repo, I will be touching following points :

    1. Process and procedure for Threat Hunting.
    2. Approaches for Threat Hunting
    3. Ways to detect threats lurking on your network.
    
One can commend or request for something that they are specially looking for.

Happy Hunting !!!!
