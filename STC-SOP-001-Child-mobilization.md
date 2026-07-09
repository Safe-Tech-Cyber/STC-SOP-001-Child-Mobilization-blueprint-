# Safe Tech Cyber (STC) — Standard Operating Procedure
**Document ID:** STC-SOP-001  
**Classification:** Public Operational Blueprint  
**Title:** 24-Hour Critical Child Mobilization & Passive Threat Intelligence Pipeline  

---

## 1. Objective & Operational Mandate
When a child goes missing or an active abduction is suspected, the clock is ticking against a critical 24-hour window. The mandate of Safe Tech Cyber (STC) Floor 6 (Threat Intelligence) is to deploy immediate, high-speed, passive digital footprint extraction to map threat actors and last known locations.

### The Golden Rule of Passive OSINT
STC analysts work completely invisibly. We harvest publicly available data on the clear and dark web. Personnel must NEVER interact with a suspect, message a target, or deploy active infrastructure that alerts a predator. If a threat actor detects an active trace, they will delete evidence, destroy hardware, or flee—putting the victim in immediate physical danger.

---

## 2. Phase 1: Operational Security (OpSec) & Legal Initialization (Hour 0 - Hour 1)
No analyst may input a name, alias, or keyword into a search engine until the digital workspace is completely isolated and legally validated. 

### A. Technical Isolation (The Digital Armor)
Analysts assigned to the mobilization unit must configure their environment using the following strict protocols:
1. **Operating System:** Analysts must boot up a dedicated, clean Virtual Machine (VM) running Kali Linux. All investigative tools, scripts, and temporary data must live exclusively inside this isolated environment to prevent cross-contamination with the host machine.
2. **Network Masking:** All internet traffic out of the Kali Linux environment must be routed through a premium, multi-hop Virtual Private Network (VPN) or the Tor Network. The native corporate or residential IP address of STC personnel must never touch a target site.
3. **Sanitized Browsing:** Utilize a hardened privacy browser (e.g., Brave or Tor Browser) in strict incognito mode. Clear all historical caches, cookies, and localized data before initiating a query.
4. **Sock Puppet Protocols:** Analysts must interact with social media platforms or public forums exclusively through pre-configured, thoroughly sanitized sock-puppet accounts (investigative personas). Personal or official STC corporate accounts are strictly forbidden from conducting target searches.

### B. Legal Continuity & Chain of Custody 
Because STC packages intelligence directly for international law enforcement, all evidence must remain legally pristine for future court actions.
1. **The Investigation Ledger:** Automated logging scripts must be active from minute zero, recording an unalterable, timestamped audit trail of every URL visited, search query executed, and file downloaded.
2. **Cryptographic Sealing:** The exact moment a critical image, post, or server log is extracted, the analyst must compute its unique digital fingerprint using SHA-256 cryptographic hashing. This permanently proves to law enforcement and judges that STC did not alter or manipulate the evidence post-collection.

---

## 3. Phase 2: Tactical Open Source Footprint Extraction (Hour 1 - Hour 6)
To maximize efficiency, analysts must strictly segment their workflows based on the target data type. Do not waste operational time using the wrong engine for the wrong task.

### A. Visual Intelligence & Facial Recognition (The Image Pipeline)
When extracting data from photos of the subject, known associates, or suspected predators:
1. **Primary Tool: Yandex Images**
   * *Mandate:* Utilize Yandex exclusively for facial recognition, reverse image matching, and background landmark triangulation (identifying architecture, street designs, or clothing trends). Its visual engine is globally dominant for locating matching faces across forums and unindexed web spaces.
   * *Constraint:* Do not waste critical minutes using Yandex for English text-based searches, corporate lookups, or standard name queries.
2. **Secondary Tool: PimEyes / FaceCheck.ID**
   * *Mandate:* Run isolated facial crops to locate hidden public profiles, obscure blog appearances, or historical forum interactions across the clear web.
3. **Tertiary Tool: Google Lens**
   * *Mandate:* Use Google Lens strictly to identify commercial background objects, mass-produced vehicles, clothing brands, or consumer goods to establish the subject’s environment.

### B. Text-Based Intelligence & OSINT Dorking (The Information Pipeline)
When tracking usernames, explicit names, aliases, leaked databases, or communication registries:
1. **Primary Tool: Google (Advanced Search Operators)**
   * *Mandate:* Utilize Google’s text indexing through advanced search strings (Google Dorking) to filter out internet noise.
   * *Mandatory Search Parameters:*
     * File extraction: `site:targetdomain.com filetype:pdf OR filetype:xlsx`
     * Domain filtering: `"target_alias" site:instagram.com OR site:linkedin.com`
     * Noise exclusion: `"Target Name" -site:wikipedia.org`
2. **Secondary Tool: DuckDuckGo / Mojeek**
   * *Mandate:* Deploy these alternative engines when tracking controversial keywords, underground forums, or alternative networks that Google actively filters, sanitizes, or censors out of its top indices.

### C. Network & Infrastructure Mapping (The Machine Pipeline)
If an IP address, domain registry, or active server configuration is tied to a suspect or a victim's last online signature:
1. **Primary Tool: Shodan / Censys**
   * *Mandate:* Query the network indicators to reveal open ports, vulnerabilities, connected routers, or localized security cameras, allowing the team to map the digital infrastructure where the subject was last active.

---

## 4. Regulatory & Constitutional Framework ( Legal Authority)
Safe Tech Cyber operates in absolute compliance with the laws of the United Kingdom. STC invokes specific statutory exemptions to process personal and criminal data without consent during active operations:

### A. UK GDPR Article 6(1)(d) & Article 9(2)(c) — Vital Interests
STC processes data without the consent of the individual because it is strictly necessary to protect interests **"essential for the life of the data subject or of another natural person."** This grants full legal authority to extract sensitive biometric, geographical, and descriptive data during a kidnapping or missing person emergency where the subject is physically or legally incapable of giving consent.

### B. Data Protection Act 2018, Schedule 1, Part 2, Paragraph 10
STC is legally permitted to process and track data relating to criminal offenses, suspects, and illicit networks without their knowledge because the action is carried out for reasons of **substantial public interest**, and seeking consent would severely **prejudice (ruin) the purpose** of detecting or preventing the crime.

### C. Data Protection Act 2018, Schedule 2, Part 1, Paragraph 2 — The Crime Exemption
This statute completely shields STC’s data compilation when handing files to law enforcement. It waives standard GDPR restrictions (such as a suspect’s right to see or delete data held about them) because enforcing those privacy rights would obstruct the **prevention or detection of crime** and the **apprehension or prosecution of offenders.**

### D. Human Rights Act 1998 & Article 2 of the ECHR (The Right to Life)
Under British constitutional principles, there is a positive obligation to take active steps to safeguard human life. By compiling cryptographically sealed, legally untainted intelligence files and transferring them securely to public authorities (such as the Metropolitan Police or National Crime Agency), STC actively assists the state in executing its constitutional duty to protect vulnerable citizens under Article 2.
