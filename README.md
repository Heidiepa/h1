# h1

## x) Read and summarize. Some bullets is enough for a summary.

### Hutchins et al 2011: Intelligence-Driven Computer Network Defense Informed by Analysis of Adversary Campaigns and Intrusion Kill Chains

* No IT system will be secure enough to fully prevent cyber attacks so it is better to be prepared always and in various fronts. This work is continuous and ever-changing and it is important to keep up with the world.
* Models to prepare, mitigate and resolve cyber security threats have been created, examples are Attack-Based Sequential Analysis of Countermeasures (ABSAC) and IED delivery chain model
* Good way to manage cyber security is a startgey called intelligence-driven computer network defense. This strategy is based on indicators that describe the intrusion. There are three typed of indicators: Atomic (e.g. IP addresses), computed (data based values) and behavioural indicators (combination of first two).
* Kill Chain aims to target the threat and resolve it. Kill Chain Model is a process to do Kill Chain actions in a controlled manner. With computer intelligence-driven approach, Kill Chain actions can be made more precise and even enable threat resolution even before it comes a threat. Base line is properly done indicator analysis.


## Darknet Diaries. Pick one episode. 

EP 122: Lisa
* Selected this because lady in Cyber Security is not that common occurence and may provide different insight on the topic
* Podcast? is about Lisa's experience in internal threats. Staring point is Lisa's career in maritime activity, mainly her previous career in preventing piracy in the Horn of Africa and using music in high frequency to prevent pirates from landing on ships.
* After the introduction, discussion turns into her Lisa's current career in internal threat prevention and about a case she had participated. Case was about huban relations and them starting to affect company's cyber security.
* * Lisa thinks that you can be prepared but you are never really prepared. This applies to piracy and cyber threats.

## MITRE ATT&CK FAQ explains the ATT&CK Enterprise Matrix. Explain "tactic", "technique" and "procedure" in context of ATT&CK, and give an example of each. The enterprise matrix is big, you can just glimpse/browse it to see what's available instead of reading hundreds of pages.

* Tactic: The goal attacker has. There are 11 tactics in the model. Goal would be for example to get company secrets to be ransomed or to get personal information from individuals who 

* Technique: Methods the attacker is using to achive tactic or goal. There are over 250 techniques reported. One example would be that attackers try to get listing of local system accounts. This technique is T1087.001 and it's siblings are cases where attacker steals email addresses, cloud accounts or domain accounts.

* Procedures are ways to implement techniques that attackers want to achieve.  Attacker can use e.g. Powershell script to inject  data in a location where the crime is done.


## How would you compare Cyber Kill Chain and ATT&CK Enterprise matrix? Who do you think could benefit from these models?


The Cyber Kill Chain and ATT&CK framework are approaching the same things from a bit different perspectives, use cases, depth and trhough different approach of community involvement. Cyber Kil Chain is more high level and ATT&CK framework more detailed. The focus is also different: CKC is about stages of attack, from attacker POV and ATT&CK is more tactic and procedure related. The Cyber Kill Chain and ATT&CK framework complement each other and should be used together to achieve best results. CKC can be used in intial stage of threat detection and prevention and ATT&CK framework after that. Finally, update-wise ATT&CK framework is superior  and is community supported model which makes it more applocable to real-life situations.

I feel that all organisations could benefit from these models, if not fully, at least by adapting parts of them to match with company environment.

## Pick a security incident and learn about it. Write briefly about it. Point out the concepts of threat actor, exploit, vulnerability and (business) impact. (You can find writeups about security incidents from Darknet Diaries and Krebs)
Melissa Virus, one of the firt major cyber security incidents in year 1999. The virus was created by threat actor David Lee Smith .
The virus exploited Microsoft Word macro functionality and tricked email users to open corrupted document. Contents of the virus were of degraring kind and adult content.

Melissa spread rapidly and disturbed operations in major companies like Microsoft. According to estimates, around million email accounts were affected and that was huge number in 1999.
Melissa Virus did not steal any financial information or and it did not cause permanent damage to affected systems. It still took aroun 80 million dollars to clean up the mess caused by Melissa dn restore email and server functionality. 

## Install Debian on Virtualbox. Report your work, including the environment (including host OS, the real physical computer used), the steps you took and their results.

First time ever installing virtual machine. Running Linux on Windows 11 Home 23H2, Lenovo Ideapad, AMD Ryzen 5 4600H with Radeon Graphics. 3.00 GHz

Installation was somewhat complex for the first-timer. I always feel a lot of anxiety when I'm expected to do more technical tasks so this felt frutrating but after short struggle, but I was able to get the machine running. 

Comments:
Was not that clear what name to use for virtual machine, now it is named after me, not after Tero. Hope this is OK.
Guide was good but somewhat complex to follow, possibly personal issue. I would have liked more concise guide of details as there was some side-stepping but managed with this.
Also following intructions and booting up the system on only laptop (without external screen) was bit difficult but got it working finally.

## Voluntary bonus: Use either (Hutchins et al 2011) cyber kill chain or MITRE ATT&CK framework for analyzing a security incident. You can pick any incident you want (even the one you used earlier in this homework), but try to pick a source that gives you enough technical and business detail to do some analysis. (If you're in a hurry, cyber kill chain is much simpler. If you're technically skillful, you might find ATT&CK interesting)

Passing this one.

## Voluntary bonus: What do you consider the fundamentals of security? What are the theoretical foundations you would teach on the first day?

Preparing, analyzing risk and understanding used technlogies and risks they pose
Communication and involving users to be active participants in preventing and acting when security is breached.
Support and preparedness of different support functions: action plans, communication plans etc.
(Cyber Security) Incident Management
Reasons for why cyber security incident happen, benefits and what is achieved. In various levels.

## Voluntary bonus: Do you think anything is missing from these models, Cyber Kill Chain or MITRE ATT&CK?

While I cannot say if anything is missing from these models, I feel that they are named in very  AGGRESSIVE and MANLY manner and that might not give the most professional image of them. Of course both ar models created for USA but still. TBH, Cyber Kill Chain could be a name of figting game attack but what do I know about this.

I also think that these models should be even more user centric. Cyber security is not just something that certain highly technical specialist do, it is a group effort and without correct language used between professionals and users, the point of cyber security is lost and users are not even willing to be prepared.
