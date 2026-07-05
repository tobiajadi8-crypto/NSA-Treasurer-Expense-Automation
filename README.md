# NSA Reimbursement & Funding Automation

A single n8n workflow automating two club financial processes for the Nigerian Students Association (University of Windsor), built with the Claude API.

## What it does
1. **Reimbursement Checker** — triggered by new Google Form submissions, uses Claude to validate expense category and policy compliance, auto-appends approved requests to a ledger sheet, and emails a flag for anything that needs manual review.
2. **Funding Request Assistant** — triggered by a separate event-details form, uses Claude to draft a formatted UWSA funding request write-up from rough event notes, emailed back for easy copy-paste into the official application.

## Stack
n8n (self-hosted via Docker) · Claude API · Google Sheets API · Gmail API
