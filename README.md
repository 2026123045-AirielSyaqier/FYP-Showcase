# FYP-Showcase

**A digital gallery where final-year students pitch their projects to lecturers and industry partners**

[Open the FYP-Showcase live demo](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)

**Group TryToCode:** Aiman, Airiel, Aleef, Khairul, and Adam

## About the project

FYP-Showcase is our group project for final-year students who want their Final Year Project to be seen, not just graded. Students upload a project portfolio. Lecturers review it and give marks, and the admin decides which projects go public. Industry partners and guests can browse the published projects without logging in.

Each project is marked on three criteria: a working prototype (40%), the report (30%) and the presentation (30%). The system combines these into one final FYP score.

## How FYP-Showcase works

1. **Submit a portfolio.** A student adds the project title, technology domain, description, demo link and GitHub link. New projects start as PENDING.
2. **Grade the project.** A lecturer opens the project and enters the prototype, report and presentation marks. The final score is calculated automatically.
3. **Publish.** The admin changes the project status to PUBLISHED, or hides it. Only published projects appear in the public gallery.
4. **Browse and discover.** Guests and industry partners search the gallery, filter by technology domain and open the full project page.
5. **Track engagement.** The admin dashboard shows the most viewed projects, the number of projects per technology domain and industry engagement.

## What to try in the demo

- On the home page, search for `Chatbot` or select a technology tag such as `IoT`, then open a project.
- Select **Login** and choose Student, Lecturer or Admin to see each role's screen.
- As a **student**, look at My Projects. Pending projects can be deleted, but published ones are locked.
- As a **lecturer**, change the marks and watch the final score update. Delete one of your grade entries.
- As an **admin**, change a project's status and delete a project. Then open the dashboard.

This version is a front-end prototype built with HTML, CSS and JavaScript. All projects, scores and statistics are hardcoded sample data. Login, saving and deleting are simulated, there is no database, and any change disappears when the page is reloaded.

## Team members and modules

| Member | Module |
|--------|--------|
| KHAIRUL AIMAN BIN MD ARIFIN | Login and student portfolio (create and delete) |
| AIRIEL SYAQIER | Home page, project gallery, search and filter |
| MUHAMMAD ALEEF AIMAN BIN MOHD RIZAL | Project detail and lecturer grading (weighted scoring) |
| MOHAMAD KHAIRUL ZAINAL BIN JOHNNY FOO TAU FEN @ MOHD ZAIN | Admin publication status and project deletion |
| MUHAMMAD ADAM SYAMIL BIN MOHD KHAIRIN AKMAL | Dashboard and documentation |

## Run it locally

1. Open `FypShowcase` in NetBeans IDE 8.2.
2. Run the project (`F6`).
3. Open `http://localhost:8080/FypShowcase/index.html`.