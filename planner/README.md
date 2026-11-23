# Family Planner

A shared planner for both parents: who has the kids, what's on the calendar, what's for dinner and what needs buying. Runs as a claude.ai artifact, from a phone, tablet or computer.

## Sections

| Tab | What it's for |
| --- | --- |
| **Today** | School day or not, who has each child for each part of the day, today's and tomorrow's events, the weather, care gaps for this week and next, tasks due, and tonight's dinner. |
| **Week** | Seven days with the weather, a care strip per child (gaps in red), events and dinner. Tap a block to assign it for one day or every week from that day on. |
| **Meals & groceries** | A weekly meal plan, meal ideas from Claude that can fill the plan and the grocery list, and one shared grocery list grouped by store. |
| **Tasks** | Family to-dos with a person, a due date and notes. Tap a task to edit it. Tasks also appear in the Week view on their due day (overdue ones on today). |
| **Setup** | Kids, who can cover care, usual school days, care blocks, the usual weekly schedule, meals to plan, calendars, stores, weather location and backups. |

## How care is organized

- **School days** have Drop-off, Pickup and After school. **No-school days** have Daytime. **Evening** and **Overnight** apply every day. Each block can be turned on or off in Setup.
- A child who isn't in school always gets the no-school blocks.
- Days whose Google Calendar events say "No school" are marked automatically, unless someone already chose for that day.
- A weekly choice ("every Wednesday") applies from the chosen day forward and fills only days nobody has set. One-off choices are kept.

## Connections

The page uses the viewer's own claude.ai connectors, so each person connects their own accounts.

| Connector | Used for |
| --- | --- |
| Google Calendar | Showing events, adding planner events to Google, finding no-school days |
| AccuWeather® | Daily forecast on Today and in the Week view |
| Google Drive | Backups |

It also uses Claude (meal ideas), voice input where the browser supports it, and file downloads (backups).

## Where data is kept

Family data (schedules, events, meals, groceries, tasks) is stored with the artifact on claude.ai and shared by everyone with edit access. **None of it is in this repository.** Setup → Backups can save a copy to Google Drive or download one, and restore from a backup file.
