---
title: Challenges
description: Challenges
permalink: /security/challenge

layout: page

---

## Cloudflare's challenges stop bots and malicious clients in their tracks
Cloudflare's firewall can challenge suspicious visitors to ensure that a higher percentage of traffic hitting your server is legitimate.

### Challenge demos

| Managed Challenge |
|---|
| Managed challenge is the future of challenges - each request is analyzed and an appropriate challenge is presented. This challenge reduces the number of CAPTCHAs visitors have to complete. <button onclick="window.location.href='challenge/managed-challenge'" class="">Test managed challenge</button>
![Block Chrome firewall rule](https://sergiodemo.com/cdn-cgi/imagedelivery/dHAzaCotabzPiuBsjyNCtA/49eb3baf-0524-411b-62c4-37f82dac2f00/public)  |

| JS Challenge |
|---|
| JS Challenge is the classic "bouncing balls" challenge Cloudflare is famous for. It uses a Javascript analysis to slow down visitors and to validate their browser environment. <button onclick="window.location.href='challenge/js-challenge'" class="">Test JS challenge</button>
![Block Firefox firewall rule](https://sergiodemo.com/cdn-cgi/imagedelivery/dHAzaCotabzPiuBsjyNCtA/3b0668be-fa11-4c8c-c488-e26d72d4d200/public)  |

| Legacy Challenge (not recommend) |
|---|
| Legacy challenge is a old-school CAPTCHA challenge. It's not recommended for most use cases. <button onclick="window.location.href='challenge/legacy-challenge'" class="">Test legacy challenge</button>
![Block Safari firewall rule](https://sergiodemo.com/cdn-cgi/imagedelivery/dHAzaCotabzPiuBsjyNCtA/b222540f-5bba-4aed-144a-cc8fee8e8200/public)  |

