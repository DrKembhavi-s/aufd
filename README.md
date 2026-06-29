# Ayurveda Unfiltered Faculty Development

A faculty orientation and training platform for BAMS and MD/MS Ayurveda faculty. Built and maintained by **Dr. Aakash Kembhavi**, Hubli, Karnataka.

---

## About This Platform

The Ayurveda Unfiltered Faculty Development platform provides structured, live, online training sessions for Ayurveda faculty across India. Sessions are conducted via Google Meet or Microsoft Teams and cover three tracks:

- **Track 1 — Pedagogical Skills** : Teaching methods, assessment design, structured viva, question paper construction
- **Track 2 — Subject-Specific Depth** : Department-wise sessions on what faculty commonly get wrong or remain shallow on, led by practising subject experts
- **Track 3 — Research & Scholarly Skills** : Protocol writing, critical appraisal, biostatistics, dissertation supervision, publication ethics

This platform exists because existing faculty development programmes — including NCISM-mandated FDPs — function largely as curriculum read-alongs rather than genuine skill-building exercises. These sessions are designed to be different: honest, rigorous, and practically useful.

---

## What the Platform Does

### For Faculty
- Register with institutional details
- Await moderated approval by the administrator
- Receive approval confirmation by email automatically
- Browse and enrol for open sessions
- Receive session link (Google Meet / Microsoft Teams) by email before the session
- Track enrolled sessions and attendance from a personal dashboard

### For the Administrator
- Review and approve or reject faculty registrations
- Approval and rejection emails sent automatically on action
- Create and manage sessions with title, track, date, time, platform, link, and description
- Control session status (Upcoming / Open for Enrolment / Closed)
- Send session links to all enrolled faculty in one action
- Track enrolments by session
- Mark attendance after each session

---

## Technology Stack

| Layer | Technology |
|---|---|
| Hosting | GitHub Pages |
| Frontend | HTML, CSS, Vanilla JavaScript (single file) |
| Database | Firebase Firestore |
| Authentication | Firebase Authentication (Email/Password) |
| Email | EmailJS (connected to ayurvedaunfiltered@outlook.com) |

No backend server. No frameworks. One file deployment.

---

## Repository Structure

```
aufd/
│
├── index.html        # Complete platform — all pages, logic, and styles
└── README.md         # This file
```

---

## Platform Access

| Role | Access |
|---|---|
| Public | Home page, session listings, registration form |
| Faculty (pending) | Dashboard showing registration status |
| Faculty (approved) | Full dashboard, session enrolment |
| Administrator | Full admin panel — registrations, sessions, enrolments |

Administrator access is controlled by Firebase UID. Only accounts whose UID is listed in the `ADMIN_UIDS` array in `index.html` are granted admin access.

---

## Facilitator

**Dr. Aakash Kembhavi**  
MD (Ayu-Shalya), PGDMLS, MS (Counseling & Psychotherapy)  
Academician, Clinician & Researcher | Chief Editor, International Journal of Ayurveda  
Hubli, Karnataka, India

Three decades of clinical practice, teaching, examination, and institutional leadership in Ayurvedic medicine. Founder of the Ayurveda Unfiltered platform — a space for reform-oriented, evidence-conscious scholarship within the tradition.

---

## Contact

**Email** : ayurvedaunfiltered@outlook.com  
**Platform** : [Ayurveda Unfiltered](https://drkembhavi-s.github.io)  
**Journal** : [International Journal of Ayurveda](https://internationaljournalofayurveda.org)

---

## Part of the Ayurveda Unfiltered Ecosystem

This platform is one of several tools and initiatives under the Ayurveda Unfiltered brand:

- Ayurveda Unfiltered Blog — critical scholarship and reform commentary
- Ayurveda Unfiltered News — curated news platform
- Ayurveda Unfiltered Scholar Hub — unified research forum
- Ayurveda Unfiltered Voice — reform feedback platform
- **Ayurveda Unfiltered Faculty Development** — this platform
- International Journal of Ayurveda — peer-reviewed open-access journal

---

*All sessions are free. Participation certificates are issued for live attendance.*
