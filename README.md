<div align="center">

# 📋 n8n Workflow Templates

**32 battle-tested n8n blueprints. Import, add credentials, activate.**

![n8n](https://img.shields.io/badge/n8n-Blueprints-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Templates](https://img.shields.io/badge/Templates-32-gold?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</div>

---

### 💰 Finance & Invoicing

| Template | Trigger |
|---|---|
| `finance/invoice-auto-send.json` | Airtable deal created |
| `finance/invoice-reminder-3touch.json` | Cron — daily overdue check |
| `finance/stripe-to-airtable.json` | Stripe payment webhook |
| `finance/subscription-churn-alert.json` | Stripe cancellation |

### 🎯 Sales & CRM

| Template | Trigger |
|---|---|
| `sales/hubspot-deal-alerts.json` | HubSpot stage change |
| `sales/proposal-auto-send.json` | Airtable record created |
| `sales/lost-deal-reactivation.json` | Cron — 90-day check |
| `sales/lead-routing-round-robin.json` | HubSpot form submission |

### 📣 Marketing & Content

| Template | Trigger |
|---|---|
| `marketing/blog-to-social.json` | RSS / manual |
| `marketing/social-scheduler.json` | Airtable approval |
| `marketing/review-request.json` | Airtable status change |
| `marketing/competitor-alerts.json` | Cron — daily 7 AM |

### 🤖 AI-Powered

| Template | Trigger |
|---|---|
| `ai/support-responder.json` | Gmail webhook |
| `ai/contract-reviewer.json` | Google Drive upload |
| `ai/meeting-to-tasks.json` | Fireflies webhook |
| `ai/data-cleaner.json` | Manual / webhook |

---

### Import Instructions

1. Open n8n → **Workflows** → **⋮** → **Import from file**
2. Select any `.json` from the relevant folder
3. Fill in credentials (marked with ⚠️ in sticky notes)
4. Test with sample data
5. Activate

---

### Difficulty

🟢 Beginner (< 5 nodes): 8 templates
🟡 Intermediate (5–15 nodes): 18 templates
🔴 Advanced (15+ nodes): 6 templates

---

<sub>Built by <a href="https://github.com/rohan643">@rohan643</a></sub>
