Starting is hard, for me sticking with something is even harder. There is so much information out there about bug bounty hunting. It can be overwhelming. I am following Bugcrowd's Bug Bounty 101 run by InsiderPhD. And committing to putting in time everyday

My goal is to be able to identify web vulnerabilities and get on the bugcrowd leaderboard

**May 2023**

Day 1 homework - learning about computational thinking (decomposition, pattern recognition, loops, pattern generalization, algorithmn design)

Day 2 homework - what is the internet? bit sending, internet working protocol, IP addresses (IPv4, IPv6), DNS (look up domain names and get the associated IP)

Day 3 homework - packets, routing & reliability (packets of information, too many to send at once), TCP does an inventory that all packets rec'd), TCP. source: code.org https://youtu.be/mTGSiB4kB18

Day 4 bugcrowd, how does the internet work?
TCP/IP (3-way handshake), Request, Response, DNS, DNS queries, DNS records, HTTP servers, proxies, HTTP Request/Response
status codes, HTTP headers, GET + POST requests, cookies and sessions, code

Day 5 learning about DNS settings in practice by changing the domain name for the Pilar website, looking at dnschecker.org, HTTP servers, HTTP request/response. Have realised that the HTML I know from building landing pages is helping understand HTTP Requests. From the little code I know I recognise the structure of the HTML doc, the top with all the charset=UTF-8

Homework install foxyproxy extension. Got Burp already

Day 6 set up tools to start 
Burp (Community edition is fine for learning)
Use one browser for hacking (Firefox)
Getting extensions insiderphd recommends (password manager, foxyproxy, firefox containers, cookie quick manager) 

Day 7 set up tools (extensions)

Day 8, 9, 10 get familiar with Burp - scope settings, how to add subdomains, make a change see what happens

The aim of using Burp is to make a change on the Request side and see if it makes a difference on the Response side - insiderphd deletes the cookie and that leads to a 302 error, not necessarily a vulnerability but shows the required approach

Day 11 where are the IDs? UUID = No bug?

Day 12 How do we do this? Accessing something that without being logged on

Day 13 Accessing another user's resource, important tip from InsiderPhd - if the action happens to Account B it is NOT AN IDOR. Logged into the Indeed program on Bugcrowd to follow InsiderPhd's demo

Day 14 Read blog post by Codingo suggesting where to start - Essential Badge PentestLab and then Authentication / Authorization Badge. Will do that in parallel with getting familiar with Burp and Access Control

Day 15 Watched 'How to Crush Bug Bounties in the first 12 Months' Bugcrowd YouTube video; and tried to fix DNS issue on other website; set up a wiki (thank you @codingo for the tip)

Day 16 Checked the DNS records for website, not sure what the problem is. Partway through SafeStack SQL Injection tutorial

Day 17 Can I use an iphone 4s as a server - no, need newer version of iOS. 

Day 18 learning about SQL injection. New BC video dropped.

Back from a road trip! 

Day 19 Been listening to critical thinking - a bug bounty podcast

Day 20 The aim for this week is to start on pentesterlab and look at Atlassian on bugcrowd

**June 2023**

Took a few days break from clicking away at the keyboard and did some reading on CTI.
Ready to make a start. pew pew.

Thu 22 June 2023
Refresh of Burp (InsiderPhD Bugcrowd YT)
Starting with Indeed (InsiderPhD Bugcrowd YT) - read through the instructions on Bugcrowd for the Indeed program. Importance of using BC researcher email address.

**Burp Target scope**
In Burp added '^.+indeed\.com$' in Target scope so all the Indeed domains are included. Filter settings: select 'Show only in-scope items' - this filters out the garbage.

InsiderPhd's method
set up two accounts in Indeed, or any domain that is going to be tested. 

Fri 23 June 2023
PentesterLab 

Sun 25 June 2023
PentesterLab
Started wiki 

Mon 26 June 2023
PentesterLab. Not much progress but got the badges appearing on Bugcrowd

Tues 27 June 2023
PentesterLab. Learning UNIX - similar to Terminal mac commands so at least not completely new material. Reinforces that I do know some stuff

Sat 1 Jul + Sun 2 Jul
Taking GitLab for a spin - learning about Git, CI/CD, runners, pipelines

Tues 11 Jul
Getting familiar with AWS cloud, spinning up an instance
PentesterLab - Unix

Wed 12 Jul
PentesterLab - Unix

Thurs 13 Jul
PentesterLab - Unix
Submitted a bug to apple - found something that didn't do what it is supposed to do. saw it a couple of weeks ago but yesterday it happened again. might as well submit and get apple to look at it

Fri 14 Jul 
Reading a blog post shared by syngularity0 written by Graham Helton - https://grahamhelton.com/blog/jobs/
Really well written and great to see someones journey

Sat 15 Jul
Reading Bugcrowd's Inside the mind of a hacker 2023. Use of AI. Need to companies to increase scope
Refresh of SQL injection

Sun 16 Jul
Finished reading Bugcrowd's Inside the mind of a hacker 2023. Important insights for companies to better understand researchers - motivations, backgrounds etc
Watch YT video Bugcrowd interview with Casey Ellis

Tues 18 Jul
Time to get the hang of python scriptin. Downloaded PyCharm

Wed 19 Jul
Read PEP8 - style guide for python
Read article, watched YT video on Requests package

Thurs 20 Jul
What is a good resource to learn python. There are so many out there. I just want to learn the basics and start on a small project
Goal - next couple of days learn basic syntax

Fri 21 Jul
Learn basic syntax do some practical exerices/mini project
Moving learnings to python repository
Goal: by Tues night to have spun up a AWS instance and put some mini projects on a landing page

Mon 24 Jul
All about learning python atm

Thurs 27 Jul
Back to PentesterLab - Unix/Linux. Got stuck on one but I think I did too many and was zonked

Fri 28 Jul
PentesterLab - Unix/Linux. The one I was stuck on was me being tired. Got it straight away
Took ages to get Unix 15 done. I have used Vim before but not for ages. Had to find how to insert and save. Also took a while to install John-the-ripper. Still not sure if I have the jumbo version. Got there in the end which is really satisfying 😅 

Mon 31 Jul
Reread Codingo's blog post on starting bug bounties. Will make a start on the Bugcrowd platform and go through the Unix examples from PentesterLab. I want to finish the Unix badge and then move on to the Essentials Badge

Tues 1 Aug
Got John-the-ripper jumbo working

Wed 2 Aug
Stuck on Unix 20

Thurs 3 Aug
Finally got Unix 20. Tried another way which worked 😅 

Sun 6 Aug
Pentesterlab. unix 🐈‍⬛
