# Privacy Policy (RupeeSpent)

**Effective date:** 2025-12-26

RupeeSpent (“the App”) helps you track transactions (expenses/income) and view statistics. This Privacy Policy explains what data the App processes and how it is used.

## Summary

- **No account required** to use the App in local mode.
- Your transactions are stored **either locally on your device** (CSV) or **optionally** in **your own Google Sheet** (if you enable Google sync).
- The App does **not** sell your data and does **not** run third‑party advertising trackers.

## Information the App processes

### Transaction data you enter or import
The App processes information you provide, such as:
- Date, title/description, amount
- Category, tag, notes
- Timestamps used for sorting and history (created/modified)
- Optional ordering field (row order) to preserve manual ordering within a day

### Diagnostics (optional)
If you choose **Settings → Support → Copy Diagnostics**, the App copies a short diagnostic summary to your clipboard (e.g., app version, selected backend type, counts, and sync status). You choose whether to share it with support.

## Where data is stored

### Local storage (default option)
If you use Local storage, the App stores your ledger on-device in CSV files. Files are organized by Financial Year.

### Google Drive / Google Sheets (optional)
If you enable Google sync, the App uses Google OAuth to access Google APIs and will:
- Create (or reuse) a Google Spreadsheet in a folder you select
- Read/write only the rows needed to load and maintain your ledger

The spreadsheet belongs to you and remains in your Google Drive. You can view, edit, move, or delete it at any time.

## How the App uses Google scopes
If you enable Google sync, the App may request:
- `https://www.googleapis.com/auth/spreadsheets` to read/write the ledger spreadsheet
- `https://www.googleapis.com/auth/drive.file` to create/manage the spreadsheet file in your Drive folder

If you do not enable Google sync, these scopes are not used.

## Data sharing
The App does not share your transaction data with third parties for advertising. If you enable Google sync, your data is stored in your Google account as described above.

## Data retention and deletion
- **Local mode**: You can delete transactions within the App or delete the CSV files from your device.
- **Google mode**: You can delete transactions within the App or delete the spreadsheet from Google Drive.

## Security
Google API requests are made over HTTPS. You can revoke Google access at any time from your Google account permissions.

## Children’s privacy
RupeeSpent is not directed to children and does not knowingly collect personal information from children.

## Changes to this policy
We may update this Privacy Policy as the App evolves. We will update the effective date above when changes are made.

## Contact
For privacy questions, contact: **support@rupeespent.app**

