# customer-experience/ — Service, Onboarding & Retention

**Owner:** `customer-experience-manager`

## What belongs here
Customer service reply templates · the FAQ · onboarding sequences · renewal reminders · the cancellation save flow · surveys · review requests · win-back campaigns · the anonymized feedback log · retention analysis.

## Structure
```
customer-experience/
├── service-templates/   ← one per situation (damaged kit, cancel, etc.)
├── surveys/
└── (top-level: faq, onboarding-sequence, renewal-reminders,
     cancellation-flow, review-requests, win-back-campaign,
     feedback-log, retention-analysis)
```

## The rules for this folder
1. **Nothing here has been sent to anyone.** Every template is a draft.
2. **Refunds, credits, and replacements are left blank** — `[MAYA: your call]`. The agent never decides what to offer.
3. **No customer names, emails, addresses, or child details** in any file. The feedback log holds categories and counts only.
4. **No dark patterns** in the cancellation flow. Leaving must be easy.
