# Academic Medic SAT Dashboard

## Overview
This project is a student-facing SAT practice dashboard that displays assignments, due dates, and progress.

It pulls data from a Google Sheet and renders a clean, visual dashboard for students to track their work.

---

## How It Works

### Data Source
- Google Sheets acts as the database
- Key fields:
  - student_id
  - assignment_id
  - title
  - due_date

### Front End
- Hosted via GitHub Pages
- index.html = live version
- index_temp.html = development version

### Logic
- The dashboard is **read-only**
- No data is written back to the sheet
- Progress, overdue status, and highlights are calculated in the browser

---

## Key Features
- Assignment list by student
- Due date tracking
- Overdue highlighting
- “Due Today” highlighting
- Progress tracking

---

## Workflow

### Updating Assignments
1. Add or edit rows in Google Sheets
2. Dashboard updates automatically on reload

### Adding a New Student
1. Copy TEMPLATE rows
2. Replace student_id
3. Adjust due dates

---

## Version Notes

### Version 1.1
- Static due dates
- Overdue highlighting added
- “Due Today” highlighting added

---

## Future Plans
- Student registration system
- Score tracking integration
- Self-hosted SAT test system
- Dashboard → test page communication

---
