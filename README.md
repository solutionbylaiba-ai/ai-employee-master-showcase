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

<img width="2600" height="559" alt="workflow-diagram" src="https://github.com/user-attachments/assets/c01e6d14-0032-429b-aea3-f012bc1ef878" />


## Screenshots
<img width="1920" height="1080" alt="Screenshot (185)" src="https://github.com/user-attachments/assets/0252e76c-68ac-47c2-8d5e-e43fe01de63a" />
<img width="1920" height="1080" alt="Screenshot (186)" src="https://github.com/user-attachments/assets/43a5366f-7765-409d-ab85-c4eabc233243" />
<img width="1920" height="1080" alt="Screenshot (187)" src="https://github.com/user-attachments/assets/22762fc7-9ac9-40c7-a17e-d3c136d800e2" />
<img width="1920" height="1080" alt="Screenshot (188)" src="https://github.com/user-attachments/assets/40d9704f-cee7-453c-bb46-a1ba85b6357d" />
<img width="1920" height="1080" alt="Screenshot (189)" src="https://github.com/user-attachments/assets/b4b5216a-8cbd-4478-a11d-5ac1e596430b" />
<img width="1920" height="1080" alt="Screenshot (180)" src="https://github.com/user-attachments/assets/e0751905-a29f-42d9-8365-21f0193da556" />
<img width="1920" height="1080" alt="Screenshot (181)" src="https://github.com/user-attachments/assets/ad90b0a9-4f0c-44d5-9960-de38a3ec8bde" />
<img width="1920" height="1080" alt="Screenshot (182)" src="https://github.com/user-attachments/assets/3c10d394-3df2-4db8-9ddb-ae759cd0c63c" />
<img width="1920" height="1080" alt="Screenshot (183)" src="https://github.com/user-attachments/assets/c72f55b1-f91a-4d5c-b951-8e35671ce6bf" />
<img width="1920" height="1080" alt="Screenshot (184)" src="https://github.com/user-attachments/assets/4604ca70-e4fc-4450-a98c-17b2327ec6e3" />


## Tech stack

Next.js (TypeScript) · FastAPI (Python) · PostgreSQL · MinIO (S3-compatible storage) · Ollama (local LLM) · Docker Compose

AI extraction runs entirely on infrastructure the client controls — documents are never sent to a third-party cloud AI API.

## Interested in this for your team?

This is an actively developed product, not a one-off script. Get in touch for a live demo or to discuss fit for your workflow.

**Laiba** — [solutionbylaiba@gmail.com](mailto:solutionbylaiba@gmail.com)
