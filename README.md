# Nivesh Kavach

A scam and claim checker for everyday Indian investors. Built for the SANGYAN Investor Resilience Hackathon (SEBI, NSDL, IIT BHU Science and Technology Council). Tracks: A (Digital Fraud and Scam Resilience) and E (Misinformation), with a touch of D (Financial Habits).

## What it does
- Paste a WhatsApp, Telegram or SMS message and get a 0 to 100 risk meter with plain-language reasons.
- Understands English, Hinglish and Hindi scam patterns (guaranteed returns, fake SEBI claims, remote-access apps, OTP and KYC threats, withdrawal-fee traps, secrecy, urgency, short links).
- Hindi and English interface with read-aloud voice.
- Pause check before sending money, and recovery steps if money is already sent.

## Guardrails
No stock tips, no monetisation, no login, no data collection. All checking runs in the browser, so no message ever leaves the device. The result is a pattern check, not a verdict.

## Run it
Open `index.html` in any browser. No install and no internet needed.

## Tech
A single HTML, CSS and JavaScript file with an explainable rule engine and the browser Web Speech API.

## Limitations and roadmap
Rule-based today. Future work: Bhashini languages, on-device OCR for screenshots, a trained ML classifier, official SEBI registry lookup, and an IVR or missed-call version.

## Credits
Built by Rishav Kumar Pandey (B.Tech 1st year, Asansol Engineering College) with AI assistance (Claude by Anthropic).
