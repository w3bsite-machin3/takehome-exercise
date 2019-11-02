---
title: "Two DNS configuration challenges"
date: 2019-11-02T09:57:05-07:00
draft: false
---

Based on my own experience and [this Netlify blog post from 2017](https://www.netlify.com/blog/2017/12/19/an-easier-way-to-manage-domains-and-dns-on-netlify/#getting-to-know-dns), I think two challenging parts of DNS configuration for non-technical users are:

1. Setting up custom domains
2. Understanding subdomains

If users don't want their automatically generated Netlify domain name to be the public address of their website, they need to know how to register another domain name and associate it with the IP address where their site lives. For this, it's helpful to have a mental model of what domain names and IP addresses even are. 

The user experience of the domain registrar can also impact this setup process. If the registrar is great and/or integrated into the deployment tool, that can make things easier—but piecing together information from an external registrar can make the process more challenging. 

I still find `A` and `CNAME` records confusing, as well as the fact that `www` is actually a subdomain (?!). Lots to get tripped up on, so I have a lot of empathy for other people's DNS woes.
