# gtm-automation-portfolio
GTM Engineer portfolio - Lead enrichment and sales automation projects
# GTM Automation Portfolio

Sales and marketing automation projects built with N8N, Python, and APIs.

## 🚀 Project 1: Lead Enrichment Automation

**Problem:** Sales teams waste 15+ minutes per lead doing manual research on LinkedIn, company websites, and databases.

**Solution:** Automated pipeline that enriches leads in 2 seconds with company data, job titles, employee counts, and social profiles.

### What It Does
- Receives lead email via webhook
- Enriches with company data from Abstract API
- Scores leads based on company size (100 for enterprise, 50 for SMB)
- Sends Slack alert for high-value leads
- Pushes enriched data to CRM

### Tech Stack
- **Automation:** N8N
- **APIs:** Abstract API (company enrichment)
- **Integration:** Slack, Webhook/CRM
- **Processing Time:** <1 second per lead

### Results
- **Time Saved:** 15 minutes → 2 seconds (99.7% reduction)
- **Data Quality:** 15+ fields enriched automatically
- **Lead Response Time:** Instant alerts for high-value prospects

### Screenshots

![Full Workflow](lead-enrichment-workflow.png)
*Complete automation workflow in N8N*

![Enriched Data](enriched-data-output.png)
*Sample enriched lead profile*

![Slack Notification](slack-notification.png)
*Automatic alert to sales team*

### Try It Yourself
1. Import `Lead_Enrichment_Pipeline.json` into N8N
2. Get free Abstract API key
3. Configure webhook and Slack
4. Send test lead data

---

## 📫 Contact
- **LinkedIn:** [https://www.linkedin.com/in/gideon-akanni]
- **Email:** gakanni91@gmail.com

## 🔜 Coming Soon
- Project 2: Meeting Scheduler
- Project 3: Follow-up Sequences
- Python versions of all workflows
