---
layout: page
title: Meetings
description: Listing of course modules and topics.
---

# **Meeting Schedule**

**SIG-ICPC welcomes everyone!** You do not need to be a certain skill level to attend any meeting!

Thursday meetings are more beginner-friendly practice sessions that cover general topics that are common in technical interviews. 

Saturday meetings are more rigourous and cover more complicated algorithms seen in ICPC and other related competitions. Anyone interested in ICPC is highly encouraged to attend Saturday meetings!

Unless specified, Thursday meetings are 4-6PM at Sidney Lu 2200 and Saturday meetings are 1-6PM at DCL 0440. 

Please join our [Discord](https://discord.gg/eWcbBd7Vcf) for location and times!

{% for module in site.modules %}
{{ module }}
{% endfor %}
