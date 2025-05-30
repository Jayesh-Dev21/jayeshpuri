---
author: MarshmalloQi
pubDatetime: 2025-04-08T20:58:52.737Z
modDatetime: 2025-05-30T19:25:46.734Z
title: Who am I ??
description: A OSINT CTF chall regarding geo osint 
slug: en/kashictf/osint
featured: false
draft: false
tags:
  - kashictf
  - OSINT
  - OPEN-SOURCE INTELLIGENCE
  - maps
  - Hungary-Budapest
---

# Who am I ??

**Final Points:** 100

## Description
You've stumbled upon a bustling street with political posters. Find out after which politician this road is named. 

Flag Format: `KashiCTF{Full_Name}`

**Flag format clarification:** The full name is in `Title_Case`, without any diacritics, with each "special character (anything other than a-zA-Z)" replaced by an underscore.

## Attachments 

<img src="/kashictf/who_am_i/images/Road_Not_Taken.png" alt="Road">

---
## Writeup
### Step 1: Searching for the Street

As the language wasn't familiar to me so I decided to search for the country first and thus, searched for the politicians whose posters were there (*Dr. TATAR* and *DONATH ANNA*) and found the country to be *HUNGARY*.

 
After some research I found the street named *Bajcsy-Zsilinszky út* and to confirm I used [Google Earth](https://earth.google.com/web/search/Duna+House+near+Budapest,+Bajcsy-Zsilinszky+%c3%bat,+Hungary/@47.50327098,19.05506542,105.85079889a,0d,60y,66.20180559h,85t,0r/data=CqcBGnkScwolMHg0NzQxZGM3Yjk5MmUwZmFkOjB4N2I3NGU5NDJlZWQ1OTEzYRle2QWDa8BHQCH4_ZsXJw4zQCo4RHVuYSBIb3VzZSBuZWFyIEJ1ZGFwZXN0LCBCYWpjc3ktWnNpbGluc3preSDDunQsIEh1bmdhcnkYASABIiYKJAmnJf8Q6MBHQBF0EHmWbsBHQBk86yG-YQ8zQCEUUgvcxwwzQEICCAEiGgoWTFo5NGd3LXhEdVdIeXZ4QlF2amM3ZxACOgMKATBCAggASg0I____________ARAA) and found the exact location and was thus  confirmed.

### Step 2: Retrievel of Flag

I searched for the politician and found *Endre Bajcsy-Zsilinszky* and converting it to the required format gives.
> **Endre_Bajcsy_Zsilinszky**

---
## Flag
```
KashiCTF{Endre_Bajcsy_Zsilinszky}
```
