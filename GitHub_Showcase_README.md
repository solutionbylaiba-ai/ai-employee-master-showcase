# AI Employee Master

AI-assisted invoice & purchase order processing for manufacturing and import/export procurement teams — built to remove manual data entry from the review/approval loop while keeping a human in control of every decision.

> **Note:** This is a client-facing product built and maintained by [Laiba](mailto:solutionbylaiba@gmail.com). Source code is private — this repo is a project showcase. Reach out for a live walkthrough or trial access.

## The problem

Procurement and finance teams manually read every invoice and PO, retype the same fields into a spreadsheet or accounting system, and chase approvals over email or WhatsApp — with no single record of who approved what.

## What it does

- **Multi-format intake** — PDF, scanned images, Word, Excel, and CSV
- **Hybrid AI extraction** — fast rule-based pattern matching first, a locally-run AI model only for whatever it can't confidently find, with a per-field confidence score
- **Human review & correction** before anything is finalized
- **Role-based approval workflow** — Reviewer submits, Manager/Admin approves or rejects (rejection requires a written reason)
- **Full audit trail** of every action, org-wide
- **Duplicate detection** — blocks re-uploading the same file, and blocks submitting a second document with a matching invoice number
- **CSV export**, in-app notifications, self-service password reset via emailed one-time code

## How it works

![Workflow](./screenshots/workflow-diagram.png)

## Screenshots

<!-- Add 2-4 screenshots here: dashboard, field review panel, approval history, audit log -->
![Dashboard](./screenshots/dashboard.png)
![Field review](./screenshots/field-review.png)

## Tech stack

Next.js (TypeScript) · FastAPI (Python) · PostgreSQL · MinIO (S3-compatible storage) · Ollama (local LLM) · Docker Compose

AI extraction runs entirely on infrastructure the client controls — documents are never sent to a third-party cloud AI API.

## Interested in this for your team?

This is an actively developed product, not a one-off script. Get in touch for a live demo or to discuss fit for your workflow.

**Laiba** — [solutionbylaiba@gmail.com](mailto:solutionbylaiba@gmail.com)
