## Koja Web App prototype

This is the prototype for the Koja Web Appp

## Functionality included (as of 17/01/2025):
- Login
- Registration
- Add children & link TFC account (via HMRC Sandbox API)
- Add invoices
- Check TFC account balances (via HMRC Sandbox API)
-  HMRC Sandbox API payment integration

## Next features to be added

- Yapily integration (single payment)


# Koja – Your Parenting Finance Co-Pilot 🍼💸

Koja is the first **parent-first finance platform** that helps UK families reclaim childcare benefits, automate nursery payments, and survive the cost-of-living crisis with real-time, AI-powered insights.

This repo is the **MVP frontend for Koja**, used by working parents to:

- Track and pay childcare invoices
- Automate Tax-Free Childcare (TFC) top-ups
- Get personalised savings + benefits guidance

> “Parenting is hard. Paying for it shouldn't be.”

---

## 💻 Tech Stack

| Layer        | Tech               |
|--------------|--------------------|
| Frontend     | Next.js + Tailwind |
| Backend API  | Supabase           |
| Auth         | Supabase Auth      |
| Payments     | Yapily (Open Banking), Stripe |
| AI Engine    | OpenAI GPT-4 Turbo |
| Analytics    | Mixpanel / PostHog |

---

## 🛠️ Getting Started

```bash
git clone https://github.com/KojaApp/koja-web-mvp-v2
cd koja-web-mvp-v2
npm install
npm run dev
