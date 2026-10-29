# 2. User Stories and Tasks

## Evidence from the source code

The supplied code supports the following current interface behaviours:
- `Home.jsx`: a visitor can enter a search term and navigate to `/events` with a `q` query parameter.
- `Events.jsx`: the page has location, category and date controls, upcoming/previous tabs, a clear-filters button, and a result list.
- `Categories.jsx`: a category browsing page exists.
- `Login.jsx` and `Register.jsx`: login and registration interfaces exist.
- `eventService.js`: mock event filtering and mock authentication are enabled.

The presence of a form/interface does not by itself prove that a real server or production authentication is connected.

## User stories derived from the implemented interface

### US1 — Find events
**As a visitor, I want to see upcoming events on the homepage so that I can discover activities that interest me.**

Tasks:
- Display an upcoming-events section.
- Render events using the reusable `EventCard` component.
- Show a loading state while the event service returns data.

**Source evidence:** `frontend/src/pages/Home.jsx`, `frontend/src/components/EventCard.jsx`.

### US2 — Search events
**As a visitor, I want to search by event name or category so that I can find relevant events.**

Tasks:
- Capture text from the homepage search field.
- Navigate to `/events` with the search term in the query string.
- Filter mock event titles/categories in the event service.

**Source evidence:** `Home.jsx`, `Events.jsx`, `eventService.js`.

### US3 — Filter events
**As a visitor, I want to filter events by location, category and date so that I can narrow the results.**

Tasks:
- Render location, category and date controls.
- Pass selected values to `eventService.getEvents`.
- Provide a clear-filters action.
- Show an empty-state message when no events match.

**Source evidence:** `frontend/src/pages/Events.jsx`, `eventService.js`.

### US4 — Browse upcoming and previous events
**As a visitor, I want to switch between upcoming and previous events so that I can explore events by status.**

Tasks:
- Provide Upcoming and Previous tabs.
- Filter events according to date/status.
- Sort upcoming events in ascending date order and previous events in descending date order.

**Source evidence:** `Events.jsx`, `eventService.js`.

### US5 — Explore categories
**As a visitor, I want to browse event categories so that I can discover events that match my interests.**

Tasks:
- Display categories from `MOCK_CATEGORIES`.
- Provide category navigation/filtering where implemented.
- Check that category labels are consistent.

**Source evidence:** `frontend/src/pages/Categories.jsx`, `mockData.js`.

### US6 — Use account forms
**As a visitor, I want to access login and registration forms so that I can try the account-related interface.**

Tasks:
- Display login and registration forms.
- Handle form input and validation as implemented.
- Verify mock authentication behaviour.
- Document that production authentication requires backend integration.

**Source evidence:** `Login.jsx`, `Register.jsx`, `eventService.js`, `AuthContext.jsx`.

## Add task-management evidence
- [ADD] Screenshot of real Trello cards or other task board, if one exists.
- [ADD] Screenshot/link to your actual commits or pull requests.
- [ADD] Identify which user stories/tasks you personally worked on.

## Reflection — personalise this

Explain how breaking a feature into smaller tasks helped (or did not help) you. Refer to one specific story, such as event search or filtering. State one actual difficulty and what you did about it. Avoid claiming a task was completed by you unless that is true.
