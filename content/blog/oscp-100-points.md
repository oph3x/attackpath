---
title: "From 60 to 100: My Journey to Passing the OSCP"
date: 2026-11-11
draft: false
tags: ["OSCP", "OffSec", "Pentesting", "Active Directory", "Windows", "Linux","Certifications"]
summary: "My journey to passing the OSCP with a perfect score of 100 points on my second attempt, including my preparation strategy, lessons learned, and exam experience."
categories: "Certifications"
---

# From 60 to 100: My Journey to Passing the OSCP

Attackers don't just run a scanner and call it a day. They dig, enumerate, identify small misconfigurations, chain vulnerabilities together, and keep pushing until something gives.

That's exactly what the OSCP teaches you to do.

After approximately three months of preparation, two exam attempts, and plenty of lessons learned along the way, I finally achieved my goal: **100/100 points on the OSCP exam.**

However, getting there wasn't as straightforward as I initially expected. My first attempt ended with 60 out of the 70 points required to pass. Four weeks later, I went back, addressed my weaknesses, and managed to complete the entire exam in approximately five hours.

In this post, I'll share my experience, how I prepared, the resources I used, what I learned from failing my first attempt, and what I would recommend to anyone preparing for the OSCP.

## 1. Background: Where I Started

Before pursuing the OSCP, I had approximately three years of experience working in cybersecurity. My professional background included vulnerability management and incident response, rather than penetration testing.

I also held several cybersecurity certifications, including:

- CompTIA Security+
- CompTIA PenTest+
- INE eJPT

Although I had some theoretical knowledge of penetration testing, I had never worked professionally as a pentester.

My experience with Active Directory was also practically nonexistent. I had never performed an Active Directory assessment before starting my OSCP preparation.

I had solved approximately 30 machines on Hack The Box, which gave me some hands-on experience with different vulnerabilities and exploitation techniques, but I still had a lot to learn.

### Why OSCP?

My main motivation was professional development and expanding my career opportunities.

While looking at penetration testing job openings, I noticed that the OSCP appeared frequently as a required or preferred certification. It had become an important industry benchmark, and I wanted to validate my practical skills with a certification recognized by the offensive security community.

That was the main reason I decided to invest in the PEN-200 course and pursue the OSCP.

## 2. Preparation: Three Months of PEN-200

I spent approximately three months preparing for the exam, which was the same period included in the PEN-200 bundle I purchased for $1,749.

During those three months, I studied approximately 7–8 hours every day.

My preparation was primarily based on three resources:

- **PEN-200:** The official OffSec course and its included labs.
- **Proving Grounds (PG):** Additional machines to practice enumeration, exploitation, and privilege escalation.
- **HackSmarter:** A platform I used specifically to improve my Active Directory skills.

### PEN-200

In my opinion, PEN-200 is indispensable when preparing for the OSCP.

The course is well structured, and one of its biggest advantages is how it combines theoretical explanations with practical exercises. You can read about a technique and immediately put it into practice in the included labs.

Although much of the information covered in the course can be found online for free, having everything organized into a structured learning path makes a significant difference.

The challenge labs are also extremely important. They provide additional opportunities to practice and include three retired OSCP exam sets, which help you understand the general structure and difficulty of the assessment.

### Proving Grounds

Proving Grounds was another important part of my preparation.

The platform offers a wide variety of machines that help you develop your enumeration and exploitation skills. More importantly, solving different machines exposes you to techniques and attack vectors that you might not encounter otherwise.

One resource I highly recommend is the Proving Grounds machine list created by LainKusanagi. It is a useful reference when deciding which machines to prioritize during your preparation.

### HackSmarter: My Active Directory Training

Active Directory was probably the area where I needed the most improvement.

Since I had practically no previous experience with AD, I needed a dedicated environment where I could practice enumeration, identify misconfigurations, and understand how different attacks could be chained together.

That's where HackSmarter came in.

I found its Active Directory labs extremely useful for developing the skills required for the AD portion of the OSCP.

If you're preparing for the exam and don't have much experience with Active Directory, I strongly recommend giving this platform a try.

I personally focused on the easy and medium difficulty labs. In my opinion, the hard labs go beyond what is necessary for the OSCP, so I would prioritize mastering the fundamentals before attempting more advanced scenarios.

## 3. What I Focused on During Preparation

Although I studied different topics throughout PEN-200, three areas received most of my attention.

### Enumeration

Enumeration is arguably one of the most important skills in penetration testing, and I believe it is also one of the most underestimated.

A common mistake is to rush through enumeration and jump straight into exploitation. However, if you cannot identify the right attack vector, you are unlikely to get a foothold in the first place.

Sometimes, the information needed to compromise a machine is already available through an overlooked open port, an exposed service, or information that can be obtained through protocols such as SNMP.

A thorough enumeration process can make the difference between finding an attack path and spending hours going down the wrong rabbit hole.

### Windows and Linux Privilege Escalation

I dedicated a significant amount of time to privilege escalation on both Windows and Linux.

However, I focused slightly more on Windows because of its importance in the Active Directory environment.

Understanding Windows privilege escalation is not only useful for standalone machines. It can also be critical when compromising individual domain-joined machines and identifying opportunities for further lateral movement.

I wanted to be comfortable identifying potential privilege escalation vectors manually rather than relying entirely on automated tools.

### Active Directory

Active Directory was another major focus.

At the time of my exam, the complete AD set was worth 40 points. That represented a substantial portion of the total score required to pass.

Considering that I had no previous AD experience, I knew I couldn't afford to neglect this area.

Looking back, dedicating additional time to AD was probably the most important adjustment I made after my first attempt.

## 4. My First Attempt: 60/70 Points

My first OSCP attempt took place on October 8, 2026.

Unfortunately, I scored 60 out of the 70 points required to pass.

I was close, but not close enough.

I managed to obtain only 10 out of the 40 available points from the Active Directory set. This highlighted one of my biggest weaknesses: I hadn't dedicated enough time to studying AD attacks and Windows privilege escalation.

I also made several mistakes during the exam.

**First, my time management was poor.** I didn't have a predefined time limit for each machine, which caused me to spend too much time on certain objectives. I fell into several rabbit holes instead of moving on when I should have.

**Second, I underestimated Active Directory.** I had focused more on standalone machines and didn't fully appreciate how important Windows privilege escalation would be throughout the AD environment.

**Finally, I didn't take enough breaks.** I spent more than 19 consecutive hours in front of my computer trying to obtain the remaining points. I barely took any time to disconnect, clear my head, or rest.

Looking back, I realized that technical knowledge wasn't my only problem. My approach to the exam itself needed improvement.

I had four weeks before my next attempt, and I knew exactly what I needed to work on.

## 5. Four Weeks to Fix My Weaknesses

After my first attempt, I dedicated almost all my remaining preparation time to two areas:

- Active Directory attacks.
- Windows and Linux privilege escalation.

Most of my time went into HackSmarter's Active Directory labs. I wanted to become comfortable with the enumeration process and understand how different misconfigurations could lead to lateral movement and privilege escalation.

I also changed the way I practiced standalone machines.

Instead of spending unlimited time trying to compromise a single machine, I started using a one-hour timer for each Proving Grounds machine.

If I couldn't make meaningful progress within that time, I would move on to the next one.

This helped me develop a better sense of time management and, more importantly, avoid getting stuck on a single objective for too long.

By the time I scheduled my second attempt, I felt considerably more confident about my weaknesses.

## 6. The Second Attempt: November 5, 2026

My second attempt took place on Thursday, November 5, at 10:00 AM Central Mexico Time.

This time, I approached the exam with a completely different mindset.

I had a predefined strategy for managing my time:

- **Active Directory:** Up to four hours dedicated exclusively to compromising the domain.
- **Standalone machines:** Approximately one hour per machine before moving on if I got stuck.

I decided to start with the standalone machines.

My reasoning was simple: I wanted to find an easy win early in the exam, build some momentum, and gain confidence before moving on to the more complex objectives.

To my surprise, it worked better than expected.

### The First Foothold

My first foothold took approximately 20 minutes.

That was a great start and immediately gave me confidence that my preparation had paid off.

I continued working through the standalone machines, applying the enumeration and exploitation techniques I had practiced throughout PEN-200 and Proving Grounds.

### Active Directory

The biggest difference compared to my first attempt was Active Directory.

I had spent the previous four weeks almost entirely focused on improving my AD skills, and it showed.

I managed to compromise the entire domain in approximately two hours.

The additional practice on HackSmarter made a significant difference. I was much more comfortable with the enumeration process, identifying potential attack paths, and understanding how to move through the environment.

### The Final Score

After completing all the objectives, I achieved the maximum possible score:

**100/100 points.**

The breakdown was:

| Objectives | Points |
|---|---:|
| Standalone machine 1: Foothold + Privilege Escalation | 20 |
| Standalone machine 2: Foothold + Privilege Escalation | 20 |
| Standalone machine 3: Foothold + Privilege Escalation | 20 |
| Complete Active Directory set | 40 |
| **Total** | **100/100** |

What surprised me the most was how quickly everything came together.

I completed the entire exam in approximately five hours.

For comparison, my first attempt had taken more than 19 hours and still wasn't enough to pass.

Going from 60 points to a perfect score in just four weeks was a completely different experience.

## 7. My Technical Approach and Tools

I don't believe there is a single tool or methodology that guarantees success in the OSCP. However, there are a few tools and practices that I consider essential.

Here are some of the tools I relied on the most.

### Nmap: Start With Enumeration

Nmap was probably the most important tool throughout the exam.

My approach always starts with port scanning.

Without knowing which ports are open and which services are running, identifying potential attack vectors becomes significantly harder.

One thing I strongly recommend is scanning **all TCP ports**, rather than limiting your scan to the most common ones.

For example:

```bash
nmap -Pn -T4 -p- <TARGET>
```

Services don't always run on their default ports. SSH, web servers, and other services can be configured to listen on unexpected ports.

After identifying open ports, I perform additional scans to identify service versions and gather more information.

```bash
nmap -Pn -sC -sV -p <PORTS> <TARGET>
```

Once I know which services are running and their respective versions, I can start researching potential vulnerabilities and identifying possible attack vectors.

The important thing is not to rush this process.

Good enumeration is often what separates a successful engagement from hours of unproductive exploitation attempts.

### NetExec: A Must-Have for Active Directory

NetExec (nxc) was another essential tool during the exam.

It is extremely versatile and useful for both standalone Windows machines and Active Directory environments.

I particularly recommend spending time understanding everything NetExec can do instead of only learning a few commonly used commands.

It can significantly simplify different enumeration tasks and help you gather information throughout an assessment.

### WinPEAS and LinPEAS

For privilege escalation enumeration, I relied heavily on WinPEAS and LinPEAS.

Both tools are excellent for identifying potential privilege escalation vectors on Windows and Linux systems.

However, there is something important to remember:

**Automated enumeration tools should complement manual enumeration, not replace it.**

You need to understand what the tools are looking for and, more importantly, how to manually investigate the findings.

Blindly executing an enumeration script and hoping it identifies an exploitable vulnerability is not a reliable approach.

### Ligolo-ng

I also used Ligolo-ng for tunneling when needed.

It is one of my favorite tools for this purpose because it is relatively straightforward to configure and very stable.

If you need to perform pivoting during an assessment, I strongly recommend becoming familiar with it.

### Obsidian: Taking Notes

Throughout both my preparation and the exam, I used Obsidian to organize my notes.

One of the things I like most about Obsidian is that it uses Markdown, making it easy to structure information, customize notes, and keep everything organized.

Having a well-maintained knowledge base is extremely valuable when preparing for a practical certification like the OSCP.

## 8. Active Directory: Lessons From My Experience

Since Active Directory was one of my biggest weaknesses during the first attempt, I want to highlight a few things that I consider particularly important.

### BloodHound Enumeration

One of the first things I usually do when assessing an Active Directory environment is collect domain information using NetExec's BloodHound integration.

The goal is to gather as much information as possible about users, groups, computers, permissions, and relationships within the domain.

Visualizing this information can help identify potential attack paths that might otherwise be difficult to notice.

### Password Reuse

Another thing I strongly recommend is testing every password you discover against other domain accounts.

Password reuse is something you should never overlook.

A password discovered on one machine might also work for a service account, another domain user, or even an account with administrative privileges.

Never assume that a credential is only valid for the account where you originally found it.

### Treat Domain-Joined Machines as Individual Targets

One approach I found useful was treating each domain-joined machine as an individual target.

Rather than immediately focusing on domain-level attacks, I would enumerate each machine and look for opportunities to obtain local administrative privileges.

Having administrator access to individual machines can potentially expose sensitive information, including credentials stored in memory or local account information in the SAM database.

This information can sometimes provide additional opportunities for lateral movement within the domain.

## 9. Windows Privilege Escalation: Don't Rely Only on Automated Tools

Windows privilege escalation deserves special attention because of its importance throughout the exam.

Being able to manually identify potential privilege escalation vectors is essential.

Some techniques I recommend becoming comfortable with include:

- DLL hijacking.
- Unquoted service paths.
- Weak service permissions.
- Insecure file and directory permissions.
- Credential discovery and reuse.

Another important aspect that I don't see discussed enough is knowing how to operate tools when you don't have a fully interactive shell.

For example, some tools and commands behave differently when executed through a reverse shell.

Mimikatz, for instance, may require a different execution approach depending on the shell environment. The same applies to commands that expect interactive input, such as `runas`, or applications that prompt for database credentials.

Understanding how to adapt commands and tools to restricted shell environments can save you a significant amount of time.

## 10. Lessons Learned and Recommendations

After two exam attempts and approximately three months of preparation, there are several things I would recommend to anyone pursuing the OSCP.

### 1. Take Active Directory Seriously

Don't underestimate the importance of Active Directory.

Even if you're comfortable with standalone Windows and Linux machines, AD requires a different set of skills.

Practice domain enumeration, understand common misconfigurations, learn how to identify attack paths, and become comfortable with lateral movement.

If you have limited AD experience, dedicate additional time to it.

### 2. Never Rush Enumeration

This is probably the most important lesson I learned throughout my preparation.

A poor enumeration process can make an otherwise straightforward machine extremely difficult.

Scan all ports, identify services and versions, investigate exposed information, and don't overlook protocols that might reveal useful information.

Sometimes the answer is already there; you just haven't looked in the right place.

### 3. Be Careful With Walkthroughs

I don't think walkthroughs are inherently bad.

They can be excellent learning resources, especially when you're completely stuck or trying to understand a technique you haven't encountered before.

However, I recommend using them carefully.

It's easy to become comfortable knowing that the solution to your current challenge is always one click away.

The problem is that during the actual exam, there is no walkthrough waiting to save you.

Try to solve machines independently before looking for hints or complete solutions. Understanding why something works is much more valuable than simply reproducing the commands.

### 4. Manage Your Time

Don't spend hours chasing a single potential vulnerability.

If you're making no meaningful progress, take a step back, review your enumeration, and consider moving to another target.

Having a predefined time limit for each machine helped me tremendously during my second attempt.

It also reduced the pressure of feeling like I had to solve every machine immediately.

### 5. Understand What You're Doing

Finally, don't just copy and paste commands.

Take the time to understand what each command does, why you're using a particular tool, and what is happening behind the scenes.

When you understand the underlying concepts, you become much less dependent on specific tools.

That's when you start developing the problem-solving skills that actually matter during a penetration test.

## 11. Final Thoughts

Getting 100 points on my second OSCP attempt was something I was genuinely proud of.

After coming so close during my first attempt, being able to return four weeks later and achieve a perfect score in approximately five hours was an incredible feeling.

More importantly, this experience made me realize how much I enjoy penetration testing.

Coming from a background in vulnerability management and incident response, PEN-200 gave me the opportunity to develop an entirely different set of technical skills.

I genuinely enjoyed the course, both reading the material and putting everything into practice. The knowledge and hands-on experience I gained throughout the process were invaluable.

Would I recommend the OSCP?

Absolutely.

It's a significant financial investment, but I believe the certification is worth pursuing if you're serious about building a career in penetration testing. While there are other excellent and more affordable alternatives, such as the HTB CPTS, the OSCP remains one of the most recognized certifications in offensive security.

As for what's next, I'm already working toward the CRTO certification, with the goal of expanding my knowledge of red teaming and Active Directory attacks.

Another major goal is to transition into a professional penetration testing role.

This is just the beginning.

---

**Thanks for reading!**

If you're currently preparing for the OSCP, I hope my experience helps you approach your preparation differently.

And remember: enumerate thoroughly, understand your tools, manage your time, and don't give up after a failed attempt.

Sometimes, the difference between 60 and 100 points is simply knowing what you need to improve.
