# Lead Follow-up Automation

Automatically send personalized follow-up emails to leads within 60 seconds of form submission using AI.

## What It Does

1. Lead submits a Google Form with their info
2. Form data triggers a webhook to Make.com
3. Google Gemini AI generates a personalized email based on lead's business type and main challenge
4. Email is automatically sent via Gmail within 60 seconds

**Result:** No more lost leads due to slow response times.

## Tech Stack

- **Make.com** — Workflow automation (1000 ops/month free)
- **Google Gemini AI** — Personalized email generation (free tier)
- **Google Forms** — Lead capture
- **Gmail API** — Email delivery
- **Google Apps Script** — Form-to-webhook bridge

## How It Works

### Architecture
### Setup Steps

1. Create Google Form with fields: Full Name, Email, Business Type, Main Challenge
2. Create Google Sheet connected to form responses
3. Deploy Apps Script that sends form data to Make webhook
4. Build Make.com workflow: Webhook → Gemini → Gmail
5. Deploy and activate

## Performance

- **Response time:** < 60 seconds
- **Personalization:** AI-generated per lead
- **Cost:** $0 (free tier usage)
- **Success rate:** 100% (tested with multiple submissions)

## Demo

[Watch the demo video](link-to-loom-gif-here)

## Use Cases

- Restaurant chains following up with new customers
- Real estate agents contacting interested leads
- Service businesses auto-responding to inquiries
- E-commerce stores engaging potential buyers

## Pricing for Clients

- **Setup:** $200–500 (one-time)
- **Maintenance:** $50–100/month

## Files

- `README.md` — This file
- `demo.gif` — Demo video showing the workflow
- `apps-script.js` — Google Apps Script code (reference)

## Advantages

✅ Zero manual effort after setup  
✅ AI-personalized responses  
✅ Instant follow-up (no delays)  
✅ Works with any business type  
✅ Bilingual support possible (Arabic + English)  
✅ Scalable to unlimited leads  

## Next Features

- Delay scheduling (send at optimal times)
- SMS fallback if email bounces
- CRM integration (Pipedrive, HubSpot)
- A/B testing for email templates
- Multilingual support

## Author

Patrick Amin — AI Automation Developer  
Cairo, Egypt  
📧 patrick.ebeid@gmail.com  
🔗 [GitHub](https://github.com/patrickamin) | [Upwork](https://upwork.com)

---

*Built for Egyptian businesses. Arabic + English support available.*
