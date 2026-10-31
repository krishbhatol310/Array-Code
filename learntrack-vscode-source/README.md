# LearnTrack AI — VS Code project

This is a browser-only HTML, CSS, and JavaScript prototype. It has no build step and needs no package installation.

## Run it in Visual Studio Code

1. Download and extract `learntrack-vscode-source.zip`.
2. In VS Code, choose **File → Open Folder…** and select the extracted folder.
3. Open `index.html` and launch it in a browser. For convenient reloads, install the **Live Server** extension, then right-click `index.html` and choose **Open with Live Server**.

The editable multi-file version loads its high-resolution hero photo, web fonts, and Chart.js from online CDNs, so those assets need an internet connection. The chart has a canvas fallback if Chart.js cannot load. `learntrack-standalone.html` is the single-file version with the hero image embedded; open that file directly for a portable demo.

## Demo sign-ins

Choose **Open demo** and use one of these fictional accounts:

- Student: `student@learntrack.ai` / `learn123`
- Teacher: `teacher@learntrack.ai` / `teach123`
- Admin: `admin@learntrack.ai` / `admin123`

These are front-end demo sign-ins only. There is no server authentication. Use only fictional demo information.

## Project files

- `index.html` — page structure, landing page, forms, and dashboard mount point
- `styles.css` — responsive styles, dashboard layout, and motion design
- `app.js` — demo data, interactions, charts, and explainable topic/risk rules
- `interventions.js` — gap analysis, teacher workflow, and browser-local tracking
- `learntrack-standalone.html` — one-file demo with inline code and an embedded hero photo

Admins can add subjects from **Admin → Subjects → + Add subject**. New subject names are saved in browser localStorage and appear in the subject catalog. The fictional sample score dataset currently covers Mathematics; newly added subjects display “No scores yet.”

The demo explains its 75% expected-mastery threshold and uses explainable, rule-based logic. It does not contain a trained ML model. Data is fictional and browser-local; this prototype does not provide a backend, secure authentication, or server-side privacy controls.
