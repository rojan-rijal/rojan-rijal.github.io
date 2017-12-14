# Projects Description 

**S3 Search Engine**

This is a form of automated search engine that grabs the list of s3 bucket for domains, companies that you search. This is part of a bigger recon project that is expected to launch on end of December or by early January. Currently for security reasons, the domains that are scanner can only be added by me. If you want a domain to be monitored/scanned, open an issue and give me list of them. Once they are added, I will let you know. After that, the list should be updated every 24 hrs (unless the server goes down, in which case, an alert will be added to the search engine). 

*What to expect?*

In future, this will be available to use for all researchers/hackers. Once the CMS that I am working on is opensoured, you can integrate the same search engine to your own. That way you can have your own private search. Meanwhile, this will always be public for all users. 

*What does this do?*

As of December 13, 2017 9:45 PM PST, this scans domains every 24 hrs and brutefroces s3 buckets. The list is then updated on Algolia DB. In about 1 week, a new update will also list the ACL policy for the buckets for example, it will anwser if the bucket is readable, writable etc. 

This will allow for hackers/researchers/bug bounty hunters to find vulnerable s3 bucket. 

*Domains*

It currently has limited domanis, but soon this will also be automated so that we can add the domains that are not on the list dynamically. 

| Domains       |
| ------------- |
| uber      | 
| twitter      | 
| spotify | 
| yahoo | 
| snapchat      | 
| hackerone | 
| bugcrowd | 
| linkedin | 

*Want to help?*

Sure. Feel free to give ideas regarding how this can be upgraded. I am open to discussion. :) 
