---
title: "Two DNS configuration challenges"
date: 2019-11-02T09:57:05-07:00
draft: false
---

I think two challenging parts of DNS configuration for non-technical users are:
1. Setting up custom domains
2. Understanding subdomains

If users don't want their automatically generated Netlify domain name to be the public address of their website, they need to know how to register another domain name and associate it with the IP address where their site lives. For this, it's helpful to have a mental model of what domain names and IP addresses even are. I still find `A` and `CNAME` records confusing. I can imagine customers asking themselves: 
- What information do I need in order to make this change? 
- Where do I find it? 
- How does this affect my SSL certificates?
