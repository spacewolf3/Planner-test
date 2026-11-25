# Family Planner

A shared planner for both parents: who has the kids, what's on the calendar, what's for dinner and what needs buying. Runs as a claude.ai artifact, from a phone, tablet or computer.

## Sections

| Tab | What it's for |
| --- | --- |
| **Today** | Quick add (see below), school day or not, who has each child for each part of the day, today's and tomorrow's events, the weather, care gaps for this week and next, tasks due, and tonight's dinner. |
| **Week** | Seven days (one at a time on phones: tap a day or swipe) with the weather, a care strip per child (gaps in red), events and dinner. Tap a block to assign it for one day or every week from that day on. |
| **Meals & groceries** | A weekly meal plan (the meals turned on in Setup, plus "+ Meal" to add another meal to just one day), a recipe box (recipes from Instagram, websites, anywhere, or your own meals), suggestions from Claude that can fill the plan and the grocery list, and one shared grocery list grouped by store, with one-tap quick add for recent and common items. |
| **Tasks** | Family to-dos with a person, a due date and notes. Tap a task to edit it. Tasks can repeat (daily to yearly); ticking one off creates the next. Tasks also appear in the Week view on their due day (overdue ones on today). |
| **Setup** | Kids, who can cover care, usual school days, care blocks, the usual weekly schedule, meals to plan, calendars, stores, weather location and backups. |

## How care is organized

- **School days** have Drop-off, Pickup and After school. **No-school days** have Daytime. **Evening** and **Overnight** apply every day. Each block can be turned on or off in Setup.
- A child who isn't in school always gets the no-school blocks.
- No-school days come from Google Calendar: a "No school" event marks the day, and the mark goes away if the event does. The planner only reads Google Calendar; it never changes it. Days someone set by hand are left alone.
- A weekly choice ("every Wednesday") applies from the chosen day forward and fills only days nobody has set. One-off choices are kept.

## Quick add

Type or say what's coming up, paste a school email, or add a photo or screenshot. Claude finds the events, to-dos and no-school days in it; you tick the ones to add.

## Recipe box

Save a recipe you want to try: paste its link plus the caption or recipe text, or add screenshots, and Claude pulls out the name, ingredients and steps. The planner can't open links itself. From a saved idea, plan it for a day (and add its ingredients to the grocery list), or pick it from a day's meal. Recipes can be tagged (Quick, Kid-friendly, Slow cooker…), marked a family favorite or "not again", and filtered or searched. Each recipe counts how often it's been planned. "Cook it" opens a big-text view of the ingredients and steps that keeps the screen on. Any meal in the plan can be saved to the box. Claude's meal suggestions favor family favorites, skip "not again" recipes and avoid recent repeats.

## Kitchen display

Add `#kitchen` to the planner's link (or tap Kitchen display on Today) for a full-screen, big-text view meant for a tablet or old phone on the counter: the time, weather, who has the kids today, today's events, dinner (tap to cook) and tasks due, and tomorrow. It updates by itself, dims from 9pm to 6am, and can keep the screen on.

## Connections

The page uses the viewer's own claude.ai connectors, so each person connects their own accounts.

| Connector | Used for |
| --- | --- |
| Google Calendar | Showing events and finding no-school days (read only) |
| AccuWeather® | Daily forecast on Today and in the Week view |
| Google Drive | Backups |

It also uses Claude (quick add and meal ideas), voice input where the browser supports it, and file downloads (backups).

## Where data is kept

Family data (schedules, events, meals, groceries, tasks) is stored with the artifact on claude.ai and shared by everyone with edit access. **None of it is in this repository.** Setup → Backups can save a copy to Google Drive or download one, and restore from a backup file.
