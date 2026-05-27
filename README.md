# 🏠 Our Week — Family Planner

A personal AI-powered family planning app built with love (and Claude).

## What it does

**Our Week** is a weekly planning tool for our family — it pulls in our Google Calendar, plans our meals, generates a smart shopping list, tracks our pantry stock, and flags anything that needs action during the week.

### Features

- **Weekly overview** — pulls events from our family Google Calendar and summarises the week at a glance
- **AI meal planner** — generates a 7-day meal plan based on our preferences, dietary needs, and what's already in the pantry
- **Smart shopping list** — auto-generated from the meal plan + weekly staples, copyable straight into AnyList
- **Pantry inventory** — tracks our standard stock levels with +/− buttons; shows a colour-coded bar for each item so we can see at a glance what needs restocking
- **Stock alerts** — cross-references the meal plan against the pantry and flags things like "stock up on pasta after Thursday"
- **Action items** — surfaces things that need doing: birthday presents to buy, school kit to prepare, appointments to book
- **Bookings** — add date nights, hairdresser appointments, travel, kids' activities with automatic conflict checking
- **Ask anything** — a chat interface to ask questions about the week ("is Tuesday free?", "what's for dinner Friday?")

## Tech

- Single HTML file — no framework, no build step, no dependencies
- Powered by the [Claude API](https://anthropic.com) (claude-sonnet-4)
- Google Calendar connected via iCal feed
- Settings and inventory saved to browser localStorage
- Hosted on GitHub Pages

## How to use

Open the app → go to **Setup** → fill in your family details, meal preferences and pantry staples → hit **✦ Plan our week**.

That's it. Every Sunday morning, one button does everything.

---

*Built by Mari & Brandon · Powered by Claude · Made with ☕ and a lot of sticky notes*
