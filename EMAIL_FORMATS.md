# Email formats

Send every email to **aihustle-leads@mail.grokbot.com** from the email address you used on the class signup page (your first email registers your ID to it). The subject must carry your license ID. Anything else is ignored.

## 1. SETUP (sent once, after the First Bot finishes)
```
Subject: SETUP | MLH-XXXX | Your Name

License: MLH-XXXX
Name: Your Name
Niche: [bakeries]
Area: [Tampines, Singapore]
Channels: [email, phone]
```

## 2. LEADS (sent by Map Lead Hunter, up to 25 leads per email)
```
Subject: LEADS | MLH-XXXX | [bakeries Tampines] | 3

License: MLH-XXXX

business_name,category,area,phone,website,source,score,notes
Ah Seng Bakery,Bakery,Tampines,+65 6123 4567,,Google Maps,16,no website
Kopi Corner,Cafe,Tampines,+65 6234 5678,kopicorner.sg,Google Maps,12,site last updated 2019
Roti House,Bakery,Tampines,+65 6345 6789,none,Directory,14,Facebook page only
```
Leave `website` blank (or write `none`) when the business has no website. `score` is out of 20.

You can also use blocks instead of CSV, one lead per block, separated by a blank line:
```
Business name: Ah Seng Bakery
Category: Bakery
Area: Tampines
Phone: +65 6123 4567
Website: none
Source: Google Maps
Score: 16
Notes: no website
```

## What comes back
- SETUP: a welcome email confirming your license, including the full Map Lead Hunter instructions to paste into a new bot.
- LEADS: how many leads were received, how many have no website, and your next steps.
- No reply? Check the license ID, the subject format, and that you sent from your signup email.
