# healthy-diet

A single static page (`index.html`) that tells you what to eat today.

The page has a day bar (date, week row, ‹ › buttons) and an Everything / Vegetarian switch at the top. Below them are four tabs. On phones the tabs sit in a bar at the bottom of the screen; on a computer they're a pill switch under the header. Every tab follows the selected day and diet, and the page remembers the last tab you used.

- **Menu**: 5 meals a day (breakfast, morning snack, lunch, afternoon snack, dinner). Each card shows the time, calories, protein, a "Veggie" tag where it applies, the ingredients, and the cooking steps (tap "How to make"). On today, the next meal you haven't eaten is marked **Up next**. Tap the round check to mark a meal eaten
- **Week**: a card per day with its calories, an eaten-meals ring and the five meals, plus week totals. Tap a card to open that day's menu. On phones, past days shrink to one line
- **Shopping**: ingredients for **This day** (one card per meal) or the **Rest of week** (one card per day, from the selected day to Sunday). Tick items off as you buy them
- **Water**: tap glasses to log water (goal 8), see a 7-day bar chart, and read the tip of the day

Other details:
- **The menu changes every day** but stays the same for a given date. Each meal type works through its whole list before anything repeats, so you don't get the same dish on two days in a row
- **Day navigation**: ‹ › buttons, tap a day in the week row, tap the date to open a calendar, swipe left/right on the meals, or use the ← / → keys. "Back to today" appears whenever you're on another day
- Each day has its own link (e.g. `…/healthy-diet/#2026-11-20`), so you can bookmark or share a specific day
- **Theme switch** in the header: Auto (follows your phone/computer setting), Light or Dark
- Ticks, water, shopping items and settings are saved in your browser only

No build step and no dependencies: open `index.html` in a browser, or turn on GitHub Pages
(Settings → Pages → Deploy from branch → `/root`) to get a URL you can bookmark on your phone.

To change the menu, edit the `MEALS` object near the top of the script in `index.html`.
