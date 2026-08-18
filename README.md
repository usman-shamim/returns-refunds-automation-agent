# Returns & Refunds Automation Agent

**Handles return requests automatically, checks eligibility, generates labels, prevents fraud.**

- **Target:** Stores with 50+ orders/month
- **Price:** PKR 30,000 setup + PKR 3,000/month

## What It Does

Listens for return requests via WhatsApp or email, pulls order details from Shopify, evaluates eligibility (within 30 days, returnable product type, fraud checks), then approves/rejects with shipping labels or store credit offers — all automated.

## Build Plan

| Day | Task |
|-----|------|
| 1 | Set up WhatsApp/Email input |
| 2 | Add return policy logic |
| 3 | Generate return label + notifications |
| 4 | Demo + GitHub |

## Structure

```
returns-refunds-automation-agent/
├── workflow.json          # n8n workflow export
├── README.md
└── .gitignore
```