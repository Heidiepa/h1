# h1

x) Read and summarize. Some bullets is enough for a summary.

Hutchins et al 2011: Intelligence-Driven Computer Network Defense Informed by Analysis of Adversary Campaigns and Intrusion Kill Chains
Darknet Diaries. Pick one episode. (RSS feed)

## MITRE ATT&CK FAQ explains the ATT&CK Enterprise Matrix. Explain "tactic", "technique" and "procedure" in context of ATT&CK, and give an example of each. The enterprise matrix is big, you can just glimpse/browse it to see what's available instead of reading hundreds of pages.

Tactic: The goal attacker has. There are 11 tactics in the model.

Technique: Methods the attacker is using to achive tactic or goal. There are over 250 techniques reported. One example would be that attackers try to get listing of local system accounts. This technique is T1087.001 and it's siblings are cases where attacker steals email addresses, cloud accounts or domain accounts.

Procedures are the specific implementations the adversaries use for techniques or subtechniques. For example, a procedure could be an adversary using PowerShell to inject into lsass.exe to dump credentials by scraping LSASS memory on a victim. Procedures are categorized in ATT&CK as the observed in the wild use of techniques in the "Procedure Examples" section of technique pages.



## How would you compare Cyber Kill Chain and ATT&CK Enterprise matrix? Who do you think could benefit from these models?



## Pick a security incident and learn about it. Write briefly about it. Point out the concepts of threat actor, exploit, vulnerability and (business) impact. (You can find writeups about security incidents from Darknet Diaries and Krebs)
Melissa Virus, one of the firt major cyber security incidents in year 1999. The virus was created by threat actor David Lee Smith .
The virus exploited Microsoft Word macro functionality and tricked email users to open corrupted document. Contents of the virus were of degraring kind and adult content.

Melissa spread rapidly and disturbed operations in major companies like Microsoft. According to estimates, around million email accounts were affected and that was huge number in 1999.
Melissa Virus did not steal any financial information or and it did not cause permanent damage to affected systesm. It still took aroun 80 million dollars to clean up the mess caused by Melissa dn restore email and server functionality. 

## Install Debian on Virtualbox. Report your work, including the environment (including host OS, the real physical computer used), the steps you took and their results.

First time ever installing virtual machine. Running Linux on Windows 11 Home 23H2, Lenovo Ideapad, AMD Ryzen 5 4600H with Radeon Graphics. 3.00 GHz

Installation was somewhat complex for the first-timer. I always feel a lot of anxiety when I'm expected to do more technical tasks so this felt frutrating but after short struggle, I was able to get the machine running. 

Comments:
Was not that clear what name to use for virtual machine, now it is named after me, not after Tero
Guide was good but somewhat complex to follow, possibly personal issue. I would have liked more concise guide but managed with this.
Also following intructions and booting up the system on only laptop (without external screen) was bit difficult but got it working finally.

## Voluntary bonus: Use either (Hutchins et al 2011) cyber kill chain or MITRE ATT&CK framework for analyzing a security incident. You can pick any incident you want (even the one you used earlier in this homework), but try to pick a source that gives you enough technical and business detail to do some analysis. (If you're in a hurry, cyber kill chain is much simpler. If you're technically skillful, you might find ATT&CK interesting)

## Voluntary bonus: What do you consider the fundamentals of security? What are the theoretical foundations you would teach on the first day?

Preparing, analyzing risk and understanding used technlogies and risks they pose
Communication and involving users to be active participants in preventing and acting when security is breached.
Support and preparedness of different support functions: action plans, communication plans etc.
(Cyber Security) Incident Management
Reasons for why cyber security incident happen, benefits and what is achieved. In various levels.


## Voluntary bonus: Do you think anything is missing from these models, Cyber Kill Chain or MITRE ATT&CK?

While I cannot say if anything is missing from these models, I feel that they are named in very  AGGRESSIVE and MANLY manner nd that might not give the most professional image of them. TBH, Cyber Kill Chain could be a name of figting game attack but what do I know about this.

I also think that these models should be even more user centric. Cyber security is not just something that certain highly technical specialist do, it is a group effort and without correct language used between professionals and users, the point of cyber security is lost and users are not prepared.
