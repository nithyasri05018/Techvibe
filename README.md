# Medical Document Intelligence & Patient Timeline — Review 3

A browser-based hackathon prototype built with HTML, CSS and JavaScript.

## Run in VS Code

1. Open this folder in VS Code.
2. Install/use **Live Server** (recommended).
3. Right-click `index.html` → **Open with Live Server**.
4. Sign in with one of the demo accounts.

No Node.js or backend is required.

### Demo accounts

- Admin — admin@demo.com / Admin@123
- Doctor — doctor@demo.com / Doctor@123
- Viewer — viewer@demo.com / Viewer@123

## Working features

- Session-based login using `sessionStorage`
- Admin / Doctor / Viewer frontend role controls
- Multiple patients keyed by Patient ID
- Patient name / ID search
- Create and delete patients
- Multiple document upload per patient
- Patient-isolated document storage in `localStorage`
- PDF text extraction through PDF.js CDN
- Text/CSV extraction using browser APIs
- Rule-based extraction of dates, doctors, conditions, medicines and common lab mentions
- Disease/condition history
- Recent illness
- Doctor history
- Prescription history
- Prescription comparison
- Lab history
- Complete chronological timeline
- Demo data reset

## Important prototype note

This is a hackathon prototype, not a clinical decision-support or diagnostic system. The NLP is intentionally rule-based and should not be treated as medically authoritative.

## Storage

Data is stored locally in the browser. Clearing site data or using the Admin reset removes locally stored records.

## Suggested demo flow

Login as Admin → search Ananya → open patient → Documents → upload 2–3 text/PDF records → view Analysis → Prescriptions → Rx Comparison → Lab History → Timeline → switch to Rahul to demonstrate patient isolation → login as Viewer to demonstrate read-only access.
