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

`**June 2023**
`
Took a few days break from clicking away at the keyboard and did some reading on CTI.
Ready to make a start. pew pew.

Thu 22 June 2023
Refresh of Burp (InsiderPhD Bugcrowd YT)
Starting with Indeed (InsiderPhD Bugcrowd YT) - read through the instructions on Bugcrowd for the Indeed program. Importance of using BC researcher email address.

**Burp Target scope**
In Burp added '^.+indeed\.com$' in Target scope so all the Indeed domains are included. Filter settings: select 'Show only in-scope items' - this filters out the garbage.

InsiderPhd's method
set up two accounts in Indeed, or any domain that is going to be tested. 
