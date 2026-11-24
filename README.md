# Bhandari Tutorial - Uploaded Content Website Prototype

## Open locally
1. Extract the ZIP.
2. Open the `Bhandari-Tutorial` folder in VS Code.
3. Install the VS Code extension **Live Server**.
4. Right-click `index.html` -> **Open with Live Server**.
5. Keep the folder structure intact. The PDFs and classroom image use relative paths.

## Included uploaded content

### MP Board - Class 10 - Science
- 2022 High School Main question paper (S-110, 80 marks)
- 2023 Set A question paper and supplied complete solution
- 2024 Set A question paper and supplied complete solution
- 2025 Main Set A question paper and supplied complete solution
- 2025 Second Examination Set D question paper and supplied solution

### CBSE - Class 12 - Physics
- Question paper codes 55/7/1, 55/7/2 and 55/7/3
- Separate special paper code 55(B)/7, marked in the source as **for visually impaired candidates only**
- The year is not printed on the supplied standard Physics title pages; no year has been guessed.

### NCERT - Class 9 - Science
- Uploaded 219-page textbook PDF, including the 15 chapters listed in the contents page.

The PYQ page lists the supplied question papers and the solution documents. Question papers have a one-preview guest allowance in this prototype. Solution PDFs are displayed in the archive but show the login/premium message.

## Five source-based quizzes
Each quiz has exactly 10 MCQs, a 10-minute timer, instant scoring and answer-wise explanations.
1. MP Board | Class 10 | Science | 2023 Main Set A
2. MP Board | Class 10 | Science | 2024 Main Set A
3. MP Board | Class 10 | Science | 2025 Main Set A
4. MP Board | Class 10 | Science | 2025 Second Examination
5. CBSE | Class 12 | Physics | Paper codes 55/7/1, 55/7/2 and 55/7/3

The Class 10 quizzes are based on the respective uploaded papers and supplied solutions. The CBSE Physics quiz is based on the supplied Physics question papers; their year is not printed on the title pages.

## Admission enquiry via WhatsApp
The Contact form prepares a message with the student's name, mobile number, selected class and enquiry text, then opens WhatsApp to **+91 94074 27002**. The student must press **Send** inside WhatsApp. A local copy is also kept in the current browser's owner enquiry inbox.

## Guest access and owner tools
- Guest quiz allowance: 3 completed quiz attempts per browser (shared across the five quizzes).
- Guest PYQ allowance: 1 question-paper preview per browser.
- The owner panel includes homepage text editing, PDF upload, notice publishing, custom quiz question creation (10 questions are needed before a custom quiz is published), uploaded-file list and enquiry inbox.

## Important prototype limits
- Student login/password and premium membership remain pending, as previously decided.
- Owner uploads, notices, settings and enquiries are stored only in the current browser. They do not synchronise between devices or publish to a live website.
- Guest quotas are browser-only and can be reset by clearing browser storage. They are not production security controls.
- A production launch needs server-side owner authentication, a shared database, cloud file storage, server-side access control, secure PDF delivery and backups.

## Homepage refresh
- Updated homepage hero, clearer call-to-action buttons and more prominent institute highlights.
- Added programme cards for Classes 8th–10th Science, Classes 11th–12th PCMB and Spoken English.
- Added learning-feature cards for study resources, board-paper practice and quizzes.
- The homepage currently displays the requested marketing figures: **15+ years of teaching experience** and **1,000+ students trained**. Please confirm both figures are accurate before publishing; the institute's separately stated establishment year remains 2012.

## Folder map
- `index.html` - site structure
- `styles.css` - blue / white / orange theme and responsive layout
- `app.js` - navigation, paper archive, five quizzes, WhatsApp enquiry and local owner panel
- `content-manifest.json` - uploaded content and quiz inventory
- `assets/images/hero-classroom.jpg` - classroom hero image
- `assets/books/` - uploaded Class 9 Science textbook
- `assets/papers/` - original question papers and solutions supplied in this conversation


## Spoken English learning section
- A 10-question interactive English knowledge check with one-question-at-a-time navigation, instant score, answer review and score-specific encouragement.
- WhatsApp enquiry buttons for Spoken English classes at +91 94074 27002. Students must press Send in WhatsApp.
- Daily Vocabulary Practice contains 200 unique everyday / frequently used English words, Hindi meanings and example sentences. Each click shows the next 5 words (40 rounds); the cycle restarts after all 200 words are shown.
- This is front-end practice content; progress is not synchronised to a server.


## Responsive support
- The layout adapts across phone, tablet, laptop and large desktop widths.
- On compact screens, the navigation collapses into an accessible menu with a visible open/close state.
- Cards, study filters, paper lists, forms, the Spoken English quiz and vocabulary cards reflow for narrow screens.
- Buttons and form controls use larger touch targets on phones, and reduced-motion preferences are respected.
- The page includes a mobile viewport configuration and iPhone safe-area support.
