# Handover: Instructional Design Portfolio

## Current State
- Repo/workspace: `/Users/marcusrummler/Documents/New project`
- Project folder: `/Users/marcusrummler/Documents/New project/instructional-design-portfolio`
- Branch: `main` at workspace root
- Latest commit: no commits yet in this workspace repository
- Deployment target: GitHub Pages candidate, not yet configured or deployed
- Current production file/version: none

## What Changed In This Session
- Created a new static portfolio mock in `instructional-design-portfolio/`.
- Added `index.html` with a professional one-page structure:
  - Hero/profile
  - Selected work
  - Basic Barista Course case study
  - eLearning Calculator case study
  - Earlier work archive from the old PowerPoint portfolio
  - Learning theory/practice section
  - Resume capability summary
  - Contact/download section
- Added `styles.css` with responsive layout, restrained professional styling, and no build dependency.
- Copied selected Basic Barista Course assets into `instructional-design-portfolio/assets/`.
- Reviewed newly added source files:
  - `Marcus_Rummler_Instructional_Designer_CV_v4.docx`
  - `Marcus Rummler POW v9.pptx`
- Extracted selected PowerPoint media into modern web-ready JPG assets.
- Added `v0-el-earning-estimation-tool/public/og-image.png` as `assets/elearning-calculator-og.png`.
- Updated copy using the current CV: senior instructional designer, 10+ years, ERP/SaaS implementation training, AI-augmented workflows, and recent client profile.
- Reimagined the page for recruiter/client scan behaviour:
  - Hero now leads with `Marcus Rummler` as the primary H1.
  - Added a concise positioning statement and selected client trust strip.
  - Added recruiter/client audience cards in the professional snapshot.
  - Changed the work section to `Portfolio by capability`.
  - Added category jump links: AI-assisted course builds, L&D tools and websites, implementation training, legacy interaction samples.
  - Reorganised older work into capability groups instead of one undifferentiated archive.
- Reviewed current 2026 marketing/portfolio trend signals:
  - Emphasise trust and proof over generic persuasion.
  - Use specific, fast-verifiable evidence.
  - Make the first 30 seconds scannable for both recruiter and client audiences.

## Working And Verified
- Source assets copied from the existing validated barista course project:
  - `assets/barista-course-cover.png`
  - `assets/barista-espresso.jpg`
  - `assets/barista-microfoam.jpg`
  - `assets/barista-certificate.png`
- Source assets extracted from the old PowerPoint portfolio:
  - `assets/proof-veolia-google-workspace.jpg`
  - `assets/proof-suez-training-hub.jpg`
  - `assets/proof-ehealth-storyline.jpg`
  - `assets/proof-ehealth-mobile-app.jpg`
  - `assets/proof-downer-storyline.jpg`
  - `assets/proof-toyota-assessment.jpg`
  - `assets/proof-toyota-branching.jpg`
  - `assets/proof-flexigroup-drag-drop.jpg`
  - `assets/proof-bca-video.jpg`
- The Barista Course itself has previously been validated in SCORM Cloud per `/Users/marcusrummler/Documents/New project/basic-barista-course/HANDOVER.md`.
- eLearning Calculator live URL verified on 2026-05-27: `https://www.elearningcalculator.com/`.
- Local browser preview served at `http://localhost:8081`.
- Verified desktop and mobile layout metrics in the in-app browser:
  - No broken images.
  - No horizontal overflow.
  - First content section appears within the initial viewport below the hero.
  - Mobile navigation text is present: Work, Practice, Experience, Details.
- Verified local link/image references via HTML parser: 32 local links/images checked, no missing files.

## Unfinished Or Risky
- No LinkedIn URL, GitHub URL, or short personal bio beyond the CV/profile copy has been added yet.
- The page currently links to `https://basic-barista-course.netlify.app/` based on the existing barista course handover.
- The page links to `https://www.elearningcalculator.com/` for the eLearning Calculator.
- Local-only project-note links were replaced with in-page project summary links for GitHub Pages safety.
- The old portfolio screenshots include client/project examples. Before public GitHub Pages deployment, review client confidentiality and remove or blur anything sensitive.
- The CV download includes direct contact details. Confirm whether phone number should be public before deployment.

## Critical Logic Not To Refactor Casually
- Do not refactor the SCORM logic in `/Users/marcusrummler/Documents/New project/basic-barista-course` while working on this portfolio.
- The portfolio should reference the barista course as a case study; it should not alter course package files unless explicitly requested.
- If using screenshots or real LMS validation claims, keep them aligned with the validated SCORM Cloud notes in the barista course handover.

## Important Files
- `index.html`: Portfolio content and page structure.
- `styles.css`: Portfolio visual design and responsive behavior.
- `assets/`: Local portfolio image assets copied from the barista course.
- `.nojekyll`: Ensures GitHub Pages serves files directly without Jekyll processing.
- `README.md`: Local preview and deployment notes.
- `Marcus_Rummler_Instructional_Designer_CV_v4.docx`: current CV linked from the portfolio.
- `Marcus Rummler POW v9.pptx`: original PowerPoint portfolio linked as an archive download.
- `HANDOVER.md`: Continuity notes for future work on this portfolio.

## Known Commands And Test Steps
- Open directly in browser:
  `open /Users/marcusrummler/Documents/New\ project/instructional-design-portfolio/index.html`
- Serve locally if browser security or relative links become an issue:
  `python3 -m http.server 8080` from `/Users/marcusrummler/Documents/New project/instructional-design-portfolio`
- Then open:
  `http://localhost:8080`

## Assumptions
- Name used: Marcus Rummler, inferred from the workspace path.
- Role used: instructional designer / learning experience designer, based on the user's request.
- Learning theories included:
  - Mayer's multimedia learning principles
  - Gagne's nine events of instruction
  - Cognitive load theory
  - Performance-first design
- No credentials are required for local preview.
- GitHub Pages deployment will require either a dedicated repo or a configured Pages branch/folder.

## Recommended Next Steps
- Decide whether to convert the CV to PDF for safer browser downloading.
- Add LinkedIn and optional GitHub links.
- Add one or two more case studies from current work if appropriate.
- Browser-test desktop and mobile layouts.
- If deploying to GitHub Pages, change local-only links and document the live URL here.
