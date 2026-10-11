# Student Setup Guide (tonight)

## What you get
- **First Bot (free):** a setup guide bot. It teaches you email and calendar basics, asks a few setup questions, then helps you set up Map Lead Hunter.
- **Map Lead Hunter (paid):** finds local, single-location businesses with no website or a weak one, scores them out of 20, and drafts outreach for a brochure or landing page offer. You review and send every message yourself.
- Everything between you and BK's system happens by **email**. No app, no logins to BK's systems.

## Your license ID
BK emails you a license ID that looks like **MLH-XXXX** (letters and numbers, never 0, O, 1 or I). Tell BK the email address you will send from. Only emails from that address with your ID in the subject get a reply.

## Step 1: Install the First Bot
1. Create a new Grok Bot. Name it "My First Bot – Setup Guide".
2. Paste in everything from `FIRST_BOT_INSTRUCTIONS.md` as its instructions.
3. Say "hi". It will take you through email and calendar basics (connecting your email and calendar, drafting a test email, adding a "Lead hunt" event).

## Step 2: Let it deploy Map Lead Hunter
The First Bot asks one question at a time: your name, license ID, sending email, niche, area, channels and hours per week. Then it walks you through creating a second bot called **Map Lead Hunter** using the profile BK gives you, and gives you its first message to send.

## Step 3: Emails you send (to INBOX_ADDRESS)
**SETUP** (once, when setup is done):
```
Subject: SETUP | MLH-AB2C | Tan Wei Ming

License: MLH-AB2C
Name: Tan Wei Ming
Niche: bakeries
Area: Tampines, Singapore
Channels: email, phone
```
**LEADS** (each time Map Lead Hunter has results, max 25 leads):
```
Subject: LEADS | MLH-AB2C | bakeries Tampines | 2

License: MLH-AB2C

business_name,category,area,phone,website,source,score,notes
Ah Seng Bakery,Bakery,Tampines,+65 6123 4567,,Google Maps,16,no website
Roti House,Bakery,Tampines,+65 6345 6789,none,Directory,14,Facebook page only
```
(MLH-AB2C is an example. Use your own ID.) Full details: `EMAIL_FORMATS.md`.

## Step 4: What comes back
- After SETUP: a welcome email confirming your license and your first lead hunt.
- After LEADS: how many leads arrived, how many have no website, and next steps (pick your top 3, draft outreach, you send).
- Replies normally arrive within minutes once BK's system processes your email. No reply? Check your license ID, the subject format (`SETUP |` or `LEADS |`), and that you sent from your registered address.

## Rules
- Your bots draft. **You** read, edit and send.
- Public business info only. No personal data.
- Singapore: follow PDPA, check the Do Not Call registry before calling or texting, include an opt-out, stop when anyone says no.
- Scope: brochure or landing pages for single-location businesses. No online shops, no multi-location sites.
- No income is guaranteed. Results come from your outreach.

## Pricing
- First Bot: free
- Map Lead Hunter: $10 one-time setup + $5–10/month API fee
- 20% success fee on your first closed deal (you'll report it later; nothing to do tonight)
