---
layout: post
author: guest2
---
Securely Wipe Your Drives With No Extra Software: Do you have an old PC or hard drive that you’d like to get rid of, without worrying about personal data that might be left behind? For your own privacy and security, it’s important to securely wipe your old hard drives before selling or disposing them. There are plenty of software choices for the job. Some are free, some paid, but none are as convenient and reliable as the wipe tool you already have: Windows.

At first glance, the below may seem overly complicated but it’s just a few steps (6 keyboard entries, to be exact). You’ll be done far quicker than googling “wipe windows drive”. Give it a go.

The short (geek-friendly) How-To-Wipe instructions:
(Command prompt with admin privileges)
e: {specified drive to be wiped}
E:\>vol {note volume name}
E:\>format e: /p:2 {2 wipe passes through the drive}
Enter current volume label for drive {volume name from above}
Proceed with Format (Y/N)? y
Formatting x.x TB
Would you like to force a dismount on this volume? (Y/N) y

...and that's it!