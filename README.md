# Elite Tutoring Perth — Learning Portal Wireframe

This is a **front-end-only interactive prototype** for presenting the proposed student learning portal to Elite Tutoring Perth.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in Chrome, Edge, or Firefox.
3. No build step or package installation is required.

You can also deploy the folder directly to Netlify, Vercel static hosting, or GitHub Pages.

## Demo credentials
**Student**
- Email: `student@etp.demo`
- Password: `Student123!`

**Admin**
- Email: `admin@etp.demo`
- Password: `Admin123!`

The login page lets you switch between Student and Admin roles. The credentials are demo-only.

## Included screens
### Student
- Overview dashboard with multi-subject progress chart
- My subjects
- Notes & resources
- Worksheets and submission entry points
- Tests & quizzes
- My progress
- Class schedule
- Announcements
- Account information
- Settings

### Admin
- Overview dashboard
- Student directory with search
- Classes & batches
- Resource library with search/filter
- Assign work form
- Submission review table
- Answer-sheet/marking-guide download examples
- Tests & quizzes
- Student progress
- Announcements
- Portal settings and launch checklist

## Important prototype limitations
- This is **not a production portal**. It has no backend, real authentication, database, persistent storage, or real file uploads.
- Student names, scores, tasks, charts, batches, and resources are fictional sample data for the presentation.
- Download buttons generate sample `.txt` placeholder files to demonstrate the interaction; replace these with real uploaded PDFs in the production build.
- Forms show demo confirmations and do not save data.
- The chart values are illustrative, not real ETP student results.
- The logo mark is a text-based `ETP.` placeholder because the logo image was not available as a separate file when the prototype was generated. Replace the `.brand-mark` block in `index.html` with the official logo asset when available.
- Google Fonts are loaded online; the page falls back to system fonts if offline.

## Brand palette
- Blue: `#1769E0`
- Bright pink: `#FF3F96`
- Black: `#111318`
- White: `#FFFFFF`

## Suggested next step
Use this prototype to agree the screens and workflows with Daksh. Once the scope is approved, connect the production app to managed authentication, a database, and protected cloud file storage; implement role-based access on the server/database, not just in the UI.