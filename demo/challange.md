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
| Managed challenge is the future of challenges - each request is analyzed and an appropriate challenge is presented. This challenge reduces the number of CAPTCHAs visitors have to complete.
|<button onclick="window.location.href='challenge/managed-challenge'" class="">Test managed challenge</button>|
![Managed challenge firewall rule](/cdn-cgi/imagedelivery/dHAzaCotabzPiuBsjyNCtA/92a3fdd4-1742-4d79-0bb8-584214e99c00/public)  |

| JS Challenge |
|---|
| JS Challenge is the classic "3 dots" challenge Cloudflare is famous for. It uses a Javascript analysis to slow down visitors and to validate their browser environment. 
|<button onclick="window.location.href='challenge/js-challenge'" class="">Test JS challenge</button>|
![JS challenge firewall rule](/cdn-cgi/imagedelivery/dHAzaCotabzPiuBsjyNCtA/52419993-4994-4aea-1e77-561fbcb9cf00/public)  |

| Legacy Challenge (not recommend) |
|---|
| Legacy challenge is a old-school CAPTCHA challenge. It's not recommended for most use cases.
|<button onclick="window.location.href='challenge/legacy-challenge'" class="">Test legacy challenge</button>|
![Legacy challenge firewall rule](/cdn-cgi/imagedelivery/dHAzaCotabzPiuBsjyNCtA/29bf02c4-82ab-4b54-6d26-8a91c6f40d00/public)  |