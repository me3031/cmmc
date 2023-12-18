To satisfy the CMMC Maturity Level 1 requirements of the System and Information Integrity (SI) control family; the following products of the Microsoft 365 E3 license will be used (each hyperlink will direct you to an overview of the product):

| Control | M35 Product | 
| -------- | ----------- | 
| SI. L1-3.14.1 - Flaw Remediation | Microsoft Intune |
| SI. L1-3.14.2 - Malicious Code Protection | Microsoft Defender for Endpoint - Plan 1, Microsoft Defender Antivirus, Microsoft Intune, Exchange Online Protection |
| SI. L1 - 3.14.4 - Update Malicious Code Protection | Microsoft Defender for Endpoint - Plan 1, Microsoft Defender Antivirus, Microsoft Intune | 
| SI. L1 - 3.14.5 - System & File Scanning | Microsoft Defender for Endpoint - Plan 1, Microsoft Defender Antivirus, Microsoft Intune | 

SI. L1-3.14.1 - Flaw Remediation 

Control language: Identify, report, and correct information and information system flaws in a timely manner. 

Determination statements: [a] the time within which to identify system flaws is specified [b] system flaws are identified within the specified time frame [c] the time within which to report system flaws is specified [d] system flaws are reported within the specified time frame [e] the time within which to correct system flaws is specified [f] system flaws are corrected within the specified time frame Control summary: A developed process to identify and resolve flaws within the information system must be created. The organization will be responsible for setting a standard that will allow the organization to identify the flaw, analyze its severity, and apply items such as patches or compensating solutions to resolve it. The organization is also responsible for assuring that the process put in place is executed as specified. Meaning that flaws are resolved in the time frame which they determined was the standard. Microsoft 365 licensing needed: Microsoft 365 E3 licensing offers the following features to be leveraged to satisfy the requirements of this control: ▫ Microsoft Intune ▫ Defender for Endpoint (Plan 1) ▫ Exchange Online Protection ▫ Microsoft Defender Antivirus How to implement using Microsoft 365: The organization will need to develop policy and procedure documentation that requires and facilitates the organization checking vendor resources such as websites or direct notifications for available patches on a recurring basis. [a]. Additionally, the documentation should develop a process to evaluate the updates for severity and determine a mandatory time frame for the updates to be applied to remove flaws based on their severity [c,e]. In accordance with the time periods specified, devices enrolled and controlled using Microsoft Intune, should be configured to check for and automatically apply updates to systems [b,e]. Finally, the organization will need to implement a review process for system flaw remediation activities. During this process, remediated flaws will be evaluated to determine if they were resolved within the time period specified in the documented procedures created by the organization. Using Microsoft Intune, the organization can produce on-demand device compliance reports that will provide visibility for items such as patch status of enrolled devices [f]. Microsoft technical reference documentation: Managing Windows updates with Intune Device Compliance Reports using Intune


SI. L1-3.14.2 - Malicious Code Protection Control language: Provide protection from malicious code at appropriate locations within organizational information systems. Determination statements: [a] designated locations for malicious code protection are identified [b] protection from malicious code at designated locations is provided Control summary: The organization must maintain an up-to-date inventory of all endpoints that access the information system, and the organization must have malicious code protection mechanisms such as anti-virus/anti-malware solutions deployed to those identified locations. Microsoft 365 licensing needed: Microsoft 365 E3 licensing offers the following features to be leveraged to satisfy the requirements of this control: ▫ Microsoft Defender for Endpoint- Microsoft Defender for Endpoint Plan 1, Microsoft Defender Antivirus Microsoft Intune ▫ Exchange Online Protection How to implement: To identify the locations for malicious code protection, the organization will need to develop and maintain an inventory of assets which access their resources. Additionally, through a network diagram, the organization will need to identify areas on entry into the information system, which are the avenues that can be used to introduce malicious code. Malicious code protection locations should include (but not be limited to) items such as: workstations, mobile devices, and network appliances (I.e., firewalls and switches) [a]. Once the locations that require protection are identified, the organization will need to ensure that Microsoft Defender Antivirus is configured to conduct system scans on all devices enrolled using Microsoft Intune. The organization will also need to configure Microsoft Defender Antivirus to enable always-on protection which allows the solution to conduct real-time scans of the environment. This includes when USB devices and other external components are introduced to any asset, files are downloaded, or emails containing attachments are received [b]. Exchange Online Protection acts as an additional layer of defense, conducting real- time scans of communications to prevent spam, malware, and other email threats. Microsoft technical reference documentation: Enabling Microsoft Defender Antivirus “Always-on” protection Scheduling a scan with Microsoft Defender Antivirus Enabling antivirus policies on devices managed with Intune Overview of Exchange online protection

SI. L1-3.14.4 - Update Malicious Code Protection Control language: Update malicious code protection mechanisms when new releases are available Determination statement: [a] malicious code protection mechanisms are updated when new releases are available Control summary: The organization must ensure that the solution which provides protections to their environment from malicious content is updated when new threat signatures and virus definitions are available. Additionally, the organization will need to apply the updates to the antivirus solution on all devices which it is deployed. Microsoft 365 licensing needed: Microsoft 365 E3 licensing offers the following features to be leveraged to satisfy the requirements of this control: ▫ Microsoft Defender for Endpoint- Microsoft Defender for Endpoint Plan 1, Microsoft Defender Antivirus ▫ Microsoft Intune How to implement: Microsoft continually updates (every 2 hours) security intelligence in antimalware products to cover the latest threats and to constantly tweak detection logic, enhancing the ability of Microsoft Defender Antivirus and other Microsoft antimalware solutions to accurately identify threats. However, the organization must configure devices enrolled with Microsoft Intune to deploy automatic updates from Microsoft Defender Antivirus or implement a process to manually deploy the automatic updates to enrolled devices [a]. Microsoft technical reference documentation: Security intelligence updates for Microsoft Defender Antivirus Deploying updates with Intune

SI. L1-3.14.5 - System & File Scanning Control language: Perform periodic scans of the information system and real-time scans of files from external sources as files are downloaded, opened, or executed. Assessment objective: [a] the frequency for malicious code scans is defined [b] malicious code scans are performed with the defined frequency [c] real-time malicious code scans of files from external sources as files are downloaded, opened, or executed are performed Control summary: The organization should deploy an anti-virus / anti-malware solution to scan for and identify viruses on all devices. With this solution deployed the organization must configure the solution to scan for threats on a defined re-occurring frequency. The solution must also be configured to scan all external components (USB devices, portable storage) connected to any protected device; and scan any files or attachments prior to download. Microsoft 365 licensing needed: Microsoft 365 E3 licensing offers the following features to be leveraged to satisfy the requirements of this control: ▫ Microsoft Defender for Endpoint- Microsoft Defender for Endpoint Plan 1, Microsoft Defender Antivirus ▫ Microsoft Intune How to implement using Microsoft 365: The organization will need to determine the frequency at which its environment will be scanned for malicious code (computer viruses, worms, Trojan horses, logic bombs, spyware) and define that frequency in its documented policies and procedures [a]. Best practice recommendations are to have the antivirus solution conduct a full system scan at least once daily. Additionally, the antivirus solution should conduct real-time scans on all emails, files, attachments, and downloads. Microsoft Defender Antivirus will need to be configured to conduct systems scans on all devices enrolled using Microsoft Intune at the frequency defined by the organization [b]. Additionally, the organization will need to enable “always-on protection” Which enables Microsoft Defender Antivirus to conduct real-time scans of the environment; this includes when USB devices and other external components are introduced to endpoints, files are downloaded, or emails containing attachments are received [c]. Microsoft technical reference documentation: Enabling Microsoft Defender Antivirus “Always-on” protection Scheduling a scan with Microsoft Defender Antivirus Enabling antivirus policies on devices managed with Intune