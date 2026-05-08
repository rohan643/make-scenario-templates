<div align="center">

# 📋 Make.com Scenario Templates

**30+ battle-tested Make.com blueprints covering the most critical business automations**

[![Make](https://img.shields.io/badge/Make.com-Blueprints-6D00CC?style=for-the-badge)](https://make.com)
[![Templates](https://img.shields.io/badge/Templates-32-gold?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</div>

---

## What's Included

Drop-in Make.com scenario blueprints (.json) you can import and activate in minutes. Every scenario has been deployed in a real client environment.

---

## Template Library

### 💰 Finance & Invoicing
| Template | Description | Trigger |
|---|---|---|
| `invoice-auto-send.json` | Generates and sends invoices from Airtable deal records | Airtable record created |
| `invoice-reminder-3touch.json` | 3-email invoice reminder with escalating urgency | Cron — checks overdue daily |
| `stripe-to-quickbooks.json` | Syncs Stripe payments to QuickBooks automatically | Stripe payment webhook |
| `subscription-churn-alert.json` | Slack alert when a subscription cancels, plus win-back email | Stripe webhook |
| `expense-report-automation.json` | Collects receipts from Gmail, logs to Airtable, sends weekly summary | Gmail + Cron |

### 🎯 Sales & CRM
| Template | Description | Trigger |
|---|---|---|
| `hubspot-deal-alerts.json` | Slack notification on every stage change with deal context | HubSpot webhook |
| `proposal-auto-send.json` | Generates Google Doc proposal and sends via Gmail | Airtable record |
| `lost-deal-reactivation.json` | Re-engages deals closed-lost after 90 days with new angle | Cron |
| `lead-routing-round-robin.json` | Routes inbound leads to sales reps evenly via HubSpot | HubSpot form webhook |
| `call-notes-to-crm.json` | Transcribes sales calls (Fireflies) and logs summary to HubSpot | Fireflies webhook |

### 📣 Marketing & Content
| Template | Description | Trigger |
|---|---|---|
| `blog-to-social.json` | Repurposes one blog post into 10 social posts via GPT-4o | RSS feed / manual |
| `social-scheduler.json` | Schedules approved content across LinkedIn, Twitter, Instagram | Airtable approval |
| `newsletter-automation.json` | Compiles weekly newsletter from Notion drafts and sends via Mailchimp | Cron — Fridays |
| `review-request-sequence.json` | Sends Google/Trustpilot review requests post-project completion | Airtable status change |
| `competitor-alerts.json` | Daily briefing on competitor news, pricing changes, job posts | Cron — daily 7 AM |

### 🛒 E-Commerce
| Template | Description | Trigger |
|---|---|---|
| `order-to-fulfillment.json` | Routes Shopify orders to correct fulfillment partner automatically | Shopify webhook |
| `abandoned-cart-3step.json` | 3-email abandoned cart with discount escalation (10% → 15% → 20%) | Klaviyo / Shopify |
| `post-purchase-nps.json` | Sends NPS survey 7 days post-delivery, logs responses to Airtable | Shopify + Cron |
| `inventory-reorder-alert.json` | Alerts team when SKU hits reorder point, drafts PO | Shopify polling |
| `return-handler.json` | Processes return requests, updates inventory, issues refund/credit | Shopify webhook |

### 📁 Operations & Internal
| Template | Description | Trigger |
|---|---|---|
| `employee-onboarding.json` | Creates accounts, sends credentials, schedules day-1 meetings | BambooHR webhook |
| `meeting-notes-distributor.json` | Sends AI-summarized meeting notes to Notion + Slack + email | Fireflies webhook |
| `weekly-kpi-report.json` | Pulls KPIs from 5 sources, generates report, emails leadership | Cron — Mondays |
| `project-status-updater.json` | Syncs project status from Asana → Notion → client Slack channel | Asana webhook |
| `sop-reminder-system.json` | Reminds team of recurring SOPs (weekly reviews, monthly audits) | Cron |

### 🤖 AI-Powered
| Template | Description | Trigger |
|---|---|---|
| `ai-support-responder.json` | Drafts support email replies using GPT-4o, routes to inbox | Gmail webhook |
| `contract-ai-reviewer.json` | Flags risky clauses in uploaded contracts using GPT-4o | Google Drive |
| `ai-job-description.json` | Generates JD from a bullet-point brief, posts to LinkedIn | Manual trigger |
| `sentiment-monitor.json` | Monitors brand mentions, classifies sentiment, alerts on negatives | Twitter/RSS |
| `ai-data-cleaner.json` | Cleans and normalizes a messy Airtable or CSV dataset with GPT-4o | Manual / webhook |

---

## How to Import a Scenario

1. Open **Make.com** → go to **Scenarios**
2. Click **Create a new scenario**
3. Click the **three dots menu** → **Import Blueprint**
4. Upload the `.json` file
5. Go through each module and connect your credentials
6. Run once with test data
7. Activate

---

## Customization Tips

Each blueprint uses placeholder values marked with `{{REPLACE_ME}}`:

```json
{
  "slackChannel": "{{REPLACE_ME: your-channel-name}}",
  "airtableBaseId": "{{REPLACE_ME: your-base-id}}",
  "fromEmail": "{{REPLACE_ME: your@email.com}}"
}
```

Search the JSON for `REPLACE_ME` before importing or you'll get errors.

---

## Difficulty Rating

| Level | Icon | Count |
|---|---|---|
| Beginner (< 5 modules) | 🟢 | 8 |
| Intermediate (5–15 modules) | 🟡 | 18 |
| Advanced (15+ modules, multi-scenario) | 🔴 | 6 |

---

<div align="center">

**Built by [Rohan Mukherjee](https://github.com/rohan643) @ Apex Automation Co.**

</div>
