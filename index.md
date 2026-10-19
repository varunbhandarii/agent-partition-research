---
title: The Agent Partition
---

# The Agent Partition

We study how websites respond to declared automated identities, and whether
machine-readable versions of pages are accurate and current.

This is a course research project for AMS 691.01, Ideas in AI/ML, at Stony Brook
University. The researchers are Varun Bhandari, Dennis Huang and Vraj Patel.

## Our requests

Our research bot identifies itself as `AgentPartitionResearch/0.1` and links to
this page. Other requests use declared browser and crawler user agents for
comparison. These requests originate from our collectors, not the organisations
whose crawler names are being compared. We record robots.txt preferences and
compare them with observed access on a fixed set of public URLs.

Requests to each site are separated by at least two seconds, with one active
request per site. We record access challenges and never solve them. Collection
uses public pages, without logging in or making purchases. Fetched page bodies
are retained for research and are not republished.

## Contact and opt out

To have your site excluded, open an issue at
<https://github.com/varunbhandarii/agent-partition-research/issues> titled
"Agent Partition opt out", listing the domains or subdomains you operate. We add
them to our exclusion list before further collection. You can use the same page
for questions or concerns about the study.

Agent profile: <https://varunbhandarii.github.io/agent-partition-research/agent-profile.json>
