Starting is hard, sticking with something is hard. There is so much information out there about bug bounty hunting. It can be overwhelming. I am following Bugcrowd's Bug Bounty 101 run by InsiderPhD. And committing to putting in time everyday.

Week 1 Intro Bug Bounty 101

- learn some coding, cloud and deployment (CI/CD pipelines, AWS)
- more important is learning computational thinking (steps needed to carry out a task like making coffee)
- InsiderPhd used Burp community edition for 12 months

Homework
- how does the internet work?
- what is a request, response? 
- what is happening when your browser loads a website, how does it know what your display, how do the website know you have logged in and not someone else
_______

How does the internet work?
'Everything on the internet email, cat videos, dog videos all come down to those ones and zeros being delivered by electronic pulses, light beams, radio waves.'

**I**nternet **P**rotocol
IP = a computer's address
organized in a hierarchy

174.129.14.120 
10101110 10000001 00001110 01111000 (32 bits)

IPv4 174.129.14.120 

IPv6 3FFE: F200: 0234: AB00: 0123: 4567: 8901: ABCD (128 bits)
     
3FFE = 0011 1111 1111 1110
F200 = 1111 0010 0000 0000

**D**omain
**N**ame
**S**ystem

DNS associates names like www.example.com with the corresponding IP

____

Packets, Routing + Reliability

How is a photo sent to you?
How is data delivered to you reliably?
- Broken down into packets. Each packet might take a different direction and some may arrive before others. 
- Routers act like traffic managers to keep the packets moving through the networks smoothly
- Internet protocol
- Fault tolerant
- Reliability

**T**ransmission
**C**ontrol
**P**rotocol

TCP does a full inventory and sends back acknowledgements of each packet received
Once TCP verifies delivery the song you selected from Spotify will play

- TCP + Router Systems are scalable
- 8
- 8,000,000,000 devices

Principles of Fault Tolerance, Redundancy

- the more routers we add the more reliable the internet becomes
- it is easy to scale the internet



Sources: 
Code.org https://youtu.be/ZhEf7e4kopM
