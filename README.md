# Project 01 — Website Lead Capture Automation

## Overview

An automated lead management workflow built with **n8n Cloud**, Google Sheets, and Gmail.

The system captures customer inquiries through a web form, stores submitted information in Google Sheets, and sends an email notification to the business owner.

## Business Problem

Small businesses often receive customer inquiries manually through different channels. This can lead to missed leads, delayed responses, and disorganized customer information.

## Solution

This workflow automates the initial lead capture process.

### Workflow Architecture

```text
Customer Inquiry Form
        |
        v
    n8n Form Trigger
        |
        v
Google Sheets - Append Row
        |
        v
Gmail - Send a Message
```

## Technologies Used

- n8n Cloud — Workflow automation
- Google Sheets — Lead database
- Gmail — Email notifications
- JSON — Workflow data and configuration

## Features

- Customer inquiry form
- Automatic lead collection
- Google Sheets row insertion
- Email notifications
- Automated execution workflow

## Testing Results

The initial end-to-end test was completed successfully.

- Form submission: Verified
- Google Sheets row insertion: Verified
- Gmail notification: Verified

## Project Structure

```text
01-lead-management/
├── workflow.json
├── README.md
└── screenshots/
```

## Setup Instructions

1. Create an n8n Cloud account.
2. Import `workflow.json` into n8n.
3. Connect your own Google Sheets credentials.
4. Connect your own Gmail credentials.
5. Select your spreadsheet and worksheet.
6. Configure the form and test the workflow.

**Important:** Credentials are not included. Configure your own connections before running the workflow.

## Future Improvements

- AI-powered lead classification
- Hot, Warm, and Cold lead scoring
- Automated personalized follow-ups
- CRM integration
- Error handling and execution monitoring

## Project Status

**Completed — Initial working version**

Built as part of my AI Automation & Business Systems Developer portfolio.
