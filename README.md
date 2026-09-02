# AI Employee Master

AI-assisted invoice and purchase order processing for manufacturing and import/export procurement teams — built to remove manual data entry from document review while keeping a person in control of every decision.

## The Problem

Procurement and finance teams spend hours every week manually reading invoices and purchase orders, retyping the same fields into a spreadsheet or accounting system, and chasing approvals over email or WhatsApp. Mistakes slip through, there's no single record of who approved what, and finding an old document later means digging through folders and inboxes.

## What This System Does

Upload an invoice or PO in almost any format — a PDF, a scanned image, a Word document, an Excel sheet, or a CSV — and the system reads it automatically, pulling out the fields that matter: invoice number, date, supplier, purchase order number, currency, tax, and total amount.

Nothing is approved automatically. A team member always reviews and can correct what the AI found before it moves forward, and only a Manager or Admin can give the final approval.

### How it works

1. **Upload** — drop in a PDF, scan, Word file, or spreadsheet
2. **AI Extraction** — the system reads invoice numbers, dates, totals & POs automatically
3. **Human Review** — your team checks and corrects the results in seconds
4. **Approval** — a Manager signs off, with the full history kept
5. **Export** — clean data ready for your accounting system

## Key Features

**Document intake**
- Accepts PDF, scanned images, Word, Excel, and CSV files
- Files are checked for type and size before they're accepted, so a bad upload fails fast with a clear message
- Duplicate protection — the same invoice can't be uploaded and processed twice, whether it's the exact same file or a rescanned copy with a matching invoice number

**AI-powered extraction**
- A fast first pass reads clearly labeled fields in under a second; a locally-run AI model only steps in for anything that pass couldn't confidently find
- Every extracted field shows a confidence score, so reviewers know at a glance what needs a closer look
- Extraction runs on infrastructure you control — documents are never sent to a third-party AI service

**Review and approval**
- Any team member can correct a field before it moves forward — the AI's original value is always kept for reference
- Only Managers and Admins can give the final approval or rejection; a rejection requires a written reason
- Every decision is permanently recorded with who made it and when

**Team management**
- Five roles — Admin, Manager, Reviewer, Employee, Auditor — each with different levels of access
- Admins add teammates directly with a chosen role, rather than everyone becoming their own independent account
- Self-service password reset via a one-time code emailed to the user — no admin needed

**Records and oversight**
- A complete audit trail of every upload, correction, submission, approval, and rejection
- In-app notifications when a document needs a decision or has been approved/rejected
- Export any document's data, or the entire organization's, as CSV for your accounting or ERP system
- Documents that are no longer active can be archived without deleting their history

## Built With

Next.js, FastAPI (Python), PostgreSQL, MinIO (secure file storage), and a locally-run AI model — all running in Docker, so it can be hosted anywhere without depending on a third-party cloud AI service.

## Project Status

The core workflow — upload, AI extraction, human review, approval, export, and a full audit trail — is complete and working end to end. This is an actively developed system; search/filtering, Excel export, and parallel document processing are the natural next additions as usage grows.

## Questions?

**Laiba** — [solutionbylaiba@gmail.com](mailto:solutionbylaiba@gmail.com)
