# Weekly Automotive News Report

This repo fetches automotive news every Monday, categorizes headlines, creates a short insight per headline, and emails the HTML report.

## Setup
1. Add files to a GitHub repo (these files).
2. In GitHub: Settings → Secrets and variables → Actions → New repository secret:
   - SMTP_HOST (e.g. smtp.gmail.com)
   - SMTP_PORT (e.g. 587)
   - SMTP_USER (your email address used to send)
   - SMTP_PASS (SMTP password or Gmail App Password)
   - TO_EMAIL = amit.ak.069@gmail.com
   - EMAIL_SUBJECT = weekly automotive lineup
3. Commit & push. Actions will run automatically on the next Monday (09:00 IST).

## Run locally (test)
```bash
pip install feedparser pandas python-dateutil requests
python weekly_automotive_news_report.py --output test-report
