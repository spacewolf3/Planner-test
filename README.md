# The Zhang-Wolfe House

A household book for one family: cleaning, upkeep, appliances and the cleaners' visits. The app is a single file, `app/index.html`.

- **To do**: what's due now, this week or this month, narrowed to the time you have (10 min to 2 hrs). Cleaning and home upkeep are listed separately. Also a shopping list from "Need supplies", plus the tasks not set up yet.
- **House cleaners**: log each visit and check what they did. Those tasks reset as done "by Cleaners." Keeps a usual checklist, cost and house-rules notes to send them.
- **Cleaning**: every cleaning task, including the 2.5 baths, wood floors, silk and wool rugs, instruments and plants.
- **Home**: appliances (brand, model, serial, warranty, manual link, notes) with their own care tasks, plus upkeep for home systems, safety, pool and pond.
- **Week**: tasks done, time, money, savings vs. hiring out, who did what, and the cleaners' visits.
- **Guide**: never-mix rules, notes for this house (floors, rugs, instruments, plants with cats), and the gentle and stronger cleaning kits.
- **Settings** (gear icon): house name, who logs tasks, cleaner schedule, cost and notes, savings rate, backup.

As a claude.ai artifact the data is saved to your account and syncs. Opened as a plain file, it saves in that browser only.

## Family Planner (`planner/index.html`)

Phase 1 of the Family Planner spec: a shared planner both parents use from their phones.

- **Today**: whether it's a school day, who has the kids for each care block, today's and tomorrow's calendar, care gaps for the next two weeks, tasks due, tonight's dinner.
- **Week**: seven days with a care strip (gaps in red) and events. Tap a block to assign it for that day or every week.
- **Meals & groceries**: a weekly meal plan, meal ideas from Claude that fill the plan and the grocery list, and one shared grocery list grouped by store.
- **Tasks**: family to-dos with an owner and due date.
- **Setup**: kids, who can cover care, usual school days, care blocks (school days: drop-off, pickup, after school; no-school days: daytime; every day: evening, overnight), the usual weekly schedule, meals to plan, calendars, stores, and backups (Google Drive, download, restore).

Google Calendar events show alongside planner events (read through each viewer's own claude.ai Google Calendar connector). New planner events can also be added to Google Calendar. Google Tasks are not included: the connector only reaches calendar events.
