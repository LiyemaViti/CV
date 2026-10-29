# 3. Product Backlog

## Evidence and status

The uploaded ZIP contains application source files and a README, but it does **not** contain a separate historical product-backlog document or Trello export. The table below is therefore a **backlog reconstructed from the supplied code**, not proof of the team's original backlog or priority decisions.

Use the actual team's backlog if you can recover it. If you create this list now, label it “reconstructed for portfolio evidence”.

| ID | Backlog item | Reason / user value | Suggested priority | Current evidence/status |
|---|---|---|---|---|
| PB01 | Homepage and navigation | Entry point for event discovery | High | Homepage and header source exist; test live behaviour |
| PB02 | Upcoming event cards | Let visitors scan featured events | High | `Home.jsx`, `EventCard.jsx`; uses mock data |
| PB03 | Event search | Find events by title/category | High | Search handling exists; verify in browser |
| PB04 | Location/category/date filters | Narrow event results | High | Controls and mock filtering exist |
| PB05 | Upcoming/previous tabs | Browse events by status | High | Tabs and date filtering exist |
| PB06 | Categories page | Explore event types | Medium | Page and mock category data exist |
| PB07 | Login/register interfaces | Provide account entry points | Medium | Forms exist; authentication uses mock mode |
| PB08 | Backend API integration | Replace mock data with server responses | High | API contract exists; `USE_MOCK = true` |
| PB09 | Error/validation handling | Improve reliability and feedback | Medium | Verify current coverage and list gaps |
| PB10 | Responsive and usability testing | Improve experience on different screens | Medium | Requires testing evidence |
| PB11 | Additional pages/features in wireframes | Align implementation with approved scope | To confirm | Compare against team's approved requirements |

## Prioritisation explanation

The main event-discovery features are central to the project's purpose, so search, event listing and filters are reasonable high-priority candidates. Backend integration is a technical dependency for moving beyond mock data. These are suggested priorities for this reconstructed list, not documented decisions from the original team.

## Add evidence
- [ADD] Screenshot of the actual product backlog with priorities.
- [ADD] Mark items done/in progress/not started based on verified status.
- [ADD] Link relevant commits or issues where possible.

## Reflection — personalise this

Discuss how you decided what was most important, whether priorities changed, and how the backlog helped the team. Refer to a real example. If no formal backlog was maintained, be honest: explain what you learned from reconstructing one and how you would maintain it in future.
