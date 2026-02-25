# 📁 PDF File Cabinet

A searchable index of PDF documents organized by email correspondence, with timestamps and direct source links.

---

## How to Use

| Column | Description |
|--------|-------------|
| **Date / Time** | Timestamp when the email was sent or received (UTC) |
| **Subject** | Email subject line |
| **From** | Sender address |
| **To** | Recipient address(es) |
| **PDF File** | Link to the attached or referenced PDF document |
| **Notes** | Additional context |

> **To add a new entry:** place the PDF file in this `pdf-cabinet/` folder, then append a row to the table below following the same format.

---

## Index

| Date / Time (UTC) | Subject | From | To | PDF File | Notes |
|-------------------|---------|------|----|----------|-------|
| 2026-01-15 09:32:14 | Q1 Budget Report | finance@example.com | ceo@example.com | [Q1-Budget-2026.pdf](./Q1-Budget-2026.pdf) | Approved |
| 2026-01-22 14:05:47 | Contract Amendment #3 | legal@example.com | partners@example.com | [Contract-Amendment-3.pdf](./Contract-Amendment-3.pdf) | Pending signatures |
| 2026-02-03 11:18:30 | Project Kickoff Agenda | pm@example.com | team@example.com | [Kickoff-Agenda-Feb2026.pdf](./Kickoff-Agenda-Feb2026.pdf) | Distributed to all |
| 2026-02-10 16:44:02 | Vendor Invoice #INV-0042 | vendor@supplier.com | accounts@example.com | [Invoice-INV-0042.pdf](./Invoice-INV-0042.pdf) | Paid 2026-02-14 |
| 2026-02-19 08:55:11 | Compliance Audit Results | auditor@regulator.gov | compliance@example.com | [Audit-Results-2026.pdf](./Audit-Results-2026.pdf) | Action items assigned |

---

## Adding a New Document

1. Copy the PDF into this `pdf-cabinet/` directory.
2. Open `pdf-cabinet/README.md` for editing.
3. Append a new row to the **Index** table:

   ```
   | YYYY-MM-DD HH:MM:SS | Subject line | sender@domain | recipient@domain | [Filename.pdf](./Filename.pdf) | Notes |
   ```

4. Commit the PDF and the updated `README.md` together with a descriptive commit message, e.g.  
   `Add Invoice-INV-0043.pdf — vendor payment Feb 2026`.

---

## Search Tips

- **Browser:** use `Ctrl + F` / `Cmd + F` on this page to search by subject, sender, date, or keyword.
- **Git log:** `git log --all --full-history -- "pdf-cabinet/*.pdf"` shows the full history for any file.
- **GitHub search:** use the repository search bar with `path:pdf-cabinet` to find entries by content.

---

&copy; 2025 GitHub &bull; [MIT License](../LICENSE)
