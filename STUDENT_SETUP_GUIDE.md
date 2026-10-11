# Student Setup Guide (tonight)

## What you get
- **First Bot (free):** a setup guide bot. It teaches you email and calendar basics, asks a few setup questions, then helps you set up Map Lead Hunter.
- **Map Lead Hunter (paid):** finds local, single-location businesses with no website or a weak one, scores them out of 20, and drafts outreach for a brochure or landing page offer. You review and send every message yourself.
- Everything between you and BK's system happens by **email**. No app, no logins to BK's systems.

## Your license ID
You get your license ID from the **class signup page**. It looks like **MLH-XXXX** (letters and numbers, never 0, O, 1 or I). Send every email from the **same email address you signed up with**. Your first email registers your ID to that address, so there's no need to tell BK beforehand. Emails about your ID from any other address are ignored.

## Step 1: Install the First Bot
1. Create a new Grok Bot. Name it "My First Bot – Setup Guide".
2. Paste in everything from `FIRST_BOT_INSTRUCTIONS.md` as its instructions.
3. Say "hi". It will take you through email and calendar basics (connecting your email and calendar, drafting a test email, adding a "Lead hunt" event).

## Step 2: Answer the setup questions and send SETUP
The First Bot asks one question at a time: your name, license ID, signup email, niche, area, channels and hours per week. Then it drafts your SETUP email (below) for you to send.

## Step 3: Deploy Map Lead Hunter from BK's reply
BK's reply to your SETUP email contains the full **Map Lead Hunter** instructions. The First Bot helps you create a second bot called Map Lead Hunter, paste them in, and send its first message.

## Step 4: Emails you send (to INBOX_ADDRESS)
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

## Step 5: What comes back
- After SETUP: a welcome email confirming your license, with the Map Lead Hunter instructions to paste in.
- After LEADS: how many leads arrived, how many have no website, and next steps (pick your top 3, draft outreach, you send).
- Replies normally arrive within minutes once BK's system processes your email. No reply? Check your license ID, the subject format (`SETUP |` or `LEADS |`), and that you sent from your signup email.

## Rules
- Your bots draft. **You** read, edit and send.
- Public business info only. No personal data.
- Singapore: follow PDPA, check the Do Not Call registry before calling or texting, include an opt-out, stop when anyone says no.
- Scope: brochure or landing pages for single-location businesses. No online shops, no multi-location sites.
- No income is guaranteed. Results come from your outreach.

## Coming later
- Realtor Bot Team tiers for property agents, and a Website Design bot.

## Pricing
- First Bot: free
- Map Lead Hunter: $10 one-time setup + $5–10/month API fee
- 20% success fee on your first closed deal (you'll report it later; nothing to do tonight)
