---
title: "Why do you think SSL/HTTPS is important?"
date: 2019-11-02T09:56:05-07:00
draft: false
---

If nothing else, Wireshark has taught me that HTTP traffic is highly sniffable! Beyond your house, office, or coffee shop network, unencrypted traffic is visible to ISPs, network operators, VPN operators... basically, a ton of people who you may not want to see your packet payloads. So HTTPS is important for privacy reasons, but it's also critical on any site where users are supplying sensitive information like passwords or credit card numbers.

Several other reasons why SSL/HTTPS is important are listed in the Netlify [docs](https://docs.netlify.com/domains-https/https-ssl/):

- Content integrity: Without HTTPS, free Wi-Fi services can inject ads into your pages.
- SEO: Google search results prioritize sites with HTTPS enabled.
- Referral analytics: HTTPS-enabled sites will not send referral data to sites without HTTPS enabled.
- HTTP/2: Boost your sites' performance — HTTP/2 requires HTTPS.

Luckily, HTTPS is now relatively easy to implement thanks to Let's Encrypt.
