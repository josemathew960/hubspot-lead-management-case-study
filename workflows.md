# Workflows

## 1. Lead capture and assignment

| Source | How it creates a lead |
|---|---|
| Website forms | HubSpot forms feed one lead record |
| Management inboxes | A shared inbox or forwarding address creates the lead |
| Round-robin | A workflow assigns inside sales owners in turn and sets a task due in 1 day |

**Result:** every lead has an owner within minutes, and response time can be measured.

## 2. Inside sales workflow

| Lead status | What the rep does | What the system does |
|---|---|---|
| New | Calls the lead | Task due in 1 day |
| Attempting contact | No answer | Next follow-up task created |
| Callback scheduled | Prospect gives a date and time | Task set for that time |
| Qualified | Need and fit are clear | Lifecycle becomes SQL, owner moves to sales |
| Unqualified | Not a fit | Closed with a reason |

Qualified is the handover moment from inside sales to the sales team.

## 3. Sales pipeline

Requirements, Sample requested, Sample sent, Quote, Negotiation, Won or Lost (reason saved).

**Stuck-deal alert:** a workflow checks time in stage. A deal stuck in a stage for over 2 weeks sends an email alert to the Sales Manager.

## 4. Sample request workflow

1. **Sales raises it.** One form: product, quantity, address, due date.
2. **Team is notified.** The request lands in a sample queue. No manual emails.
3. **Two-day timer.** The due date is 2 business days. Late requests are flagged.
4. **Dispatch.** Status is set to Sent and the tracking number is saved.

Open points: approvals for restricted chemicals, and cover when the one sample person is away.

## 5. Handover pattern (MQL to SQL)

When a lead becomes qualified, the workflow:
- creates a task with the contact and company details,
- assigns it to the right owner,
- sends a Microsoft Teams alert.
