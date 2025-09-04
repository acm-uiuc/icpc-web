---
layout: page
title: Meetings
description: Listing of course modules and topics.
---

[Help I'm currently at an icpc meeting and I don't know how to get started](start.md)

# **Meeting Schedule**

**SIG-ICPC welcomes everyone!** You do not need to be a certain skill level to attend any meeting!

Thursday meetings are more beginner-friendly practice sessions that cover general topics that are common in technical interviews. 

Saturday meetings are more rigourous and cover more complicated algorithms seen in ICPC and other related competitions. Anyone interested in ICPC is highly encouraged to attend Saturday meetings!

Unless specified, Thursday meetings are 5-7PM at Siebel CS 1302 and Saturday meetings are 11-4PM at Siebel CS 1304 (lunch provided!). 

Please join our [Discord](https://discord.gg/eWcbBd7Vcf) for location and times!

{% assign sorted_modules = site.modules | sort | reverse %}
{% for module in sorted_modules %}
{{ module }}
{% endfor %}
