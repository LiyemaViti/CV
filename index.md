# Event Guide Website — Agile Digital Portfolio

**Module:** Project Presentation 3 (PRP370S/PRP372S)  
**Assessment:** Assessment 2 — October 2026  
**Student:** [Your full name]  
**Project:** Event Guide Website  
**Portfolio URL:** [Insert your published GitHub Pages URL]  
**Project repository:** [Insert the actual repository URL]

## Project overview

The Event Guide Website is a student group project intended to help people discover upcoming events and browse previous events. The supplied frontend uses React, Vite and React Router. The homepage includes a search field and upcoming-event section; the Events page includes location, category and date filters and upcoming/previous tabs. The project also includes Categories, About, Login and Register pages.

The project README states that the frontend runs on mock data until the Java Spring Boot backend is available. In `frontend/src/services/eventService.js`, `USE_MOCK` is set to `true`. Therefore, this portfolio describes the current source accurately and does not claim that a live backend/database integration is complete.

## Portfolio sections

- [Agile Team Charter](01-agile-team-charter.md)
- [User Stories and Tasks](02-user-stories-and-tasks.md)
- [Product Backlog](03-product-backlog.md)
- [Sprint Backlog](04-sprint-backlog.md)
- [Agile Logbook](05-agile-logbook.md)
- [Evidence checklist](06-evidence-checklist.md)

## My contribution

[Describe only the work you personally completed. Mention specific pages, components, commits, testing, documentation or design tasks that you can substantiate.]

## Overall reflection

[Write a truthful reflection: what you personally learned, one specific challenge, how you responded, and what you would improve next time.]

## Source code references

- `frontend/src/App.jsx` — registered routes/pages
- `frontend/src/pages/Home.jsx` — homepage, upcoming events and search navigation
- `frontend/src/pages/Events.jsx` — event filters, tabs and result list
- `frontend/src/pages/Categories.jsx` — category page
- `frontend/src/pages/About.jsx` — project information and team names
- `frontend/src/pages/Login.jsx` and `Register.jsx` — authentication forms
- `frontend/src/components/EventCard.jsx` and `EventListItem.jsx` — event presentation components
- `frontend/src/services/eventService.js` — mock-data and API service logic
- `frontend/src/data/mockData.js` — sample events, categories and team-name list
- `API_CONTRACT.md` — planned frontend/backend API agreement
- `README.md` — setup instructions and statement that the frontend uses mock data
