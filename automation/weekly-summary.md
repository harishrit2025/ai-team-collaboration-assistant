# Weekly Summary Automation

This repository includes a GitHub Actions workflow at `.github/workflows/weekly-summary.yml`.

It runs every Monday and creates a GitHub issue containing a reminder to review the task board and post the weekly summary. It does not send email/Slack messages; this is a simple free GitHub-based automation. You can manually run it from the Actions tab too.

## Manual test
1. Open repository → Actions.
2. Select “Weekly Project Summary”.
3. Click “Run workflow”.
4. Confirm a summary issue appears under Issues.
