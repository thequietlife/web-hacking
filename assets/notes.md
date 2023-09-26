
# Bug Bounty Daily Log

Starting is hard, for me sticking with something is even harder. There is so much information out there about bug bounty hunting. It can be overwhelming. I am following Bugcrowd's Bug Bounty 101 run by InsiderPhD. And committing to putting in time everyday.

My goal is to be able to identify web vulnerabilities and get on the bugcrowd leaderboard.

## May 2023

|     | Daily Log |
| ----------- | ----------- |
| Day 1      | Learning about computational thinking (decomposition, pattern recognition, loops, pattern generalization, algorithmn design)     |
| Day 2    | What is the internet? bit sending, internet working protocol, IP addresses (IPv4, IPv6), DNS (look up domain names and get the associated IP)       |
| Day 3    | Packets, routing & reliability (packets of information, too many to send at once), TCP does an inventory that all packets rec'd), TCP. source: code.org https://youtu.be/mTGSiB4kB18|
| Day 4    | How does the internet work? TCP/IP (3-way handshake), Request, Response, DNS, DNS queries, DNS records, HTTP servers, proxies, HTTP Request/Response status codes, HTTP headers, GET + POST requests, cookies and sessions, code|
| Day 5    | Learning about DNS settings in practice by changing the domain name for the Pilar website, looking at dnschecker.org, HTTP servers, HTTP request/response. Have realised that the HTML I know from building landing pages is helping understand HTTP Requests. From the little code I know I recognise the structure of the HTML doc|
| Day 6    | Set up browser extensions to start, Burp (Community edition is fine for learning), use one browser for hacking (Firefox), getting extensions InsiderPhD recommends (password manager, foxyproxy, firefox containers, cookie quick manager)|
| Day 7    | Set up browser extensions     |
| Day 8    | Get familiar with Burp - scope settings, how to add subdomains, make a change see what happens        |
| Day 9    | More getting familiar with Burp        |
| Day 10    | More Burp, The aim of using Burp is to make a change on the Request side and see if it makes a difference on the Response side - insiderphd deletes the cookie and that leads to a 302 error, not necessarily a vulnerability but shows the required approach        |
| Day 11    | Where are the IDs? UUID = No bug?       |
| Day 12    | How do we do this? Accessing something that without being logged on        |
| Day 13    | Accessing another user's resource, important tip from InsiderPhd - if the action happens to Account B it is NOT AN IDOR. Logged into the Indeed program on Bugcrowd to follow InsiderPhd's demo        |
| Day 14    | Read blog post by Codingo suggesting where to start - Essential Badge PentestLab and then Authentication / Authorization Badge. Will do that in parallel with getting familiar with Burp and Access Control        |
| Day 15    | Watched 'How to Crush Bug Bounties in the first 12 Months' Bugcrowd YouTube video; and tried to fix DNS issue on other website; set up a wiki (thank you @codingo for the tip)       |
| Day 16    | Checked the DNS records for website, not sure what the problem is. Partway through SafeStack SQL Injection tutorial        |
| Day 17    | Can I use an iphone 4s as a server - no, need newer version of iOS        |
| Day 18    | learning about SQL injection. New BC video dropped       |
|     | Back from a road trip!          |
| Day 19    |   Been listening to Critical Thinking - Bug Bounty Podcast https://www.criticalthinkingpodcast.io/ |

## June 2023

|     |  |
| ----------- | ----------- |
|   | Took a few days break from clicking away at the keyboard and did some reading on CTI. Ready to make a start. pew pew  |
| Day 20    | Starting with Indeed (InsiderPhD Bugcrowd YT) - read through the instructions on Bugcrowd for the Indeed program. Importance of using BC researcher email address       |
|  Day 21 | Burp Target scope. In Burp added '^.+indeed\.com$' in Target scope so all the Indeed domains are included. Filter settings: select 'Show only in-scope items' - this filters out the garbage       |
| Day 22    | InsiderPhd's method set up two accounts in Indeed, or any domain that is going to be tested      |
| Day 23    | PentesterLab       |
| Day 24    | PentesterLab. Started wiki       |
| Day 25    | PentesterLab. Not much progress but got the badges appearing on Bugcrowd        |
| Day 26    | PentesterLab. Learning UNIX - similar to Terminal mac commands so at least not completely new material. Reinforces that I do know some stuff      |

## July 2023

|     |  |
| ----------- | ----------- |
| Day 27    | Taking GitLab for a spin        |
| Day 28    | GitLab - learning about Git, CI/CD, runners, pipelines        |
| Day 29    | Getting familiar with AWS cloud. PentesterLab - Unix      |
| Day 30    | PentesterLab - Unix       |
| Day 31   | PentesterLab - Unix. Submitted a bug to apple - found something that didn't do what it is supposed to do. saw it a couple of weeks ago but yesterday it happened again. might as well submit and get apple to look at it       |
| Day 32    | Reading a blog post shared by syngularity0 written by Graham Helton - https://grahamhelton.com/blog/jobs/ Really well written and great to see someones journey       |
| Day 33    | Reading Bugcrowd's Inside the mind of a hacker 2023. Use of AI. Need to companies to increase scope. Refresh of SQL injection       |
| Day 34    | Finished reading Bugcrowd's Inside the mind of a hacker 2023. Important insights for companies to better understand researchers - motivations, backgrounds etc      |
| Day 35    | Downloaded PyCharm       |
| Day 36    | Read PEP8 - style guide for python. Read article, watched YT video on Requests package       |
| Day 37    | Basic Python syntax      |
| Day 38    | Python syntax        |
| Day 39    | All about learning Python atm       |
| Day 40    | Back to PentesterLab - Unix/Linux. Got stuck on one but I think I did too many and was zonked        |
| Day 41    | PentesterLab - Unix/Linux. The one I was stuck on was me being tired. Got it straight away. Took ages to get Unix 15 done. I have used Vim before but not for ages. Had to find how to insert and save. Also took a while to install, password cracking tool John-the-ripper. Still not sure if I have the jumbo version. Got there in the end which is really satisfying 😅       |
| Day 42    | Reread Codingo's blog post on starting bug bounties. I want to finish the Unix badge and then move on to the Essentials Badge       |


## August 2023

### Three months in!

|     |  |
| ----------- | ----------- |
| Day 43    | Got John-the-ripper jumbo working      |
| Day 44    | Stuck on Unix 20      |
| Day 45    | Finally got Unix 20. Tried another way which worked 😅       |
| Day 46    | Pentesterlab. Unix       |
| Day 47    | 🏅 Finished the Pentesterlab Unix badge. Next Essentials Badge. Spending a lot of time in the car. Started listening to critical thinking - a bug bounty podcast again (episode 1)       |
| Day 48    | Essentials Badge - Cross-Site Scripting. critical thinking - a bug bounty podcast - episode 2 hardware hacking       |
| Day 49    | Essentials Badge - Cross-Site Scripting. critical thinking - a bug bounty podcast - episode 3 H1 live hacking. Imposter syndrome doesn't go away. The amount of junk triagers get submitted. There is a need for researchers to have a good amount of foundational knowledge so prevent this      |
| Day 50    | Watched YT Hacksplaining SQL Injection and a bit of Rana Khalil SQL too. Huge day feeling smashed       |
| Day 51    | Back to Pentesterlab. pew pew       |
| Day 52    | Pentesterlab - working on Authentication         |
| Day 53    | Huge few days. SecTalks Perth, QuokkaCon, and BSides Perth. I also have TCM's Practical Ethical Hacking. Will look at that as well       |
| Day 54    | Back to Pentesterlab. Working on Authentication (MD5 hash)      |
| Day 55    | TCM Security - Practical Ethical Hacking (need to always study, note taking). Pentesterlab. Authentication       |
| Day 56    | Read through Google Hacking for Penetration Testers https://www.amazon.com/Google-Hacking-Penetration-Testers-Johnny/dp/0128029641|
| Day 57    | PentesterLab - Authorization. Started reading 'The Art of Deception' by Kevin Mitnick (social engineering)        |
| Day 58    | Got stuck trying to use Burp for a PentesterLab exercise      |
| Day 59    | This morning I realised how I could approach the Burp exercise. Head down and worked it out in 20 mins. Felt good to get it        |
| Day 60    | Reviewing notes. PentesterLab        |
| Day 61    | Finally got the PentesterLab exercise. 😅 I tried it a few times but had to leave it for a bit. I think I wasn't getting the POST request I needed in Burp ( /update URL)        |
| Day 62    | Going to focus just on bug bounty. Pausing CTI      |
|    | Took a break to work on a coding project, Back next week      |
| Day 64    | Formatting daily log        |
| Day xx    | ...        |
| Day xx    | ...        |
