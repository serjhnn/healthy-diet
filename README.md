# healthy-diet

A single static page (`index.html`) that tells you what to eat today.

- **5 meals a day**: breakfast, morning snack, lunch, afternoon snack and dinner, each with ingredients, short prep steps, approximate kcal and protein
- **Changes every day** but stays the same for a given date. Each meal type works through its whole list before anything repeats, so you don't get the same dish on two days in a row
- **Everything / Vegetarian switch**, a **shopping list** for the day and a **this-week overview** (click a row to open that day)
- Tick meals as eaten, track glasses of water and get a daily tip. These are saved in your browser only
- **Day navigation** that stays at the top while you scroll: ‹ › buttons, a week row (tap any day; a small bar shows how many meals you ticked), tap the date to open a calendar, swipe left/right on the meals, or use the ← / → keys. "Back to today" appears whenever you're on another day
- Each day has its own link (e.g. `…/healthy-diet/#2026-11-20`), so you can bookmark or share a specific day
- **Theme switch** in the header: 🌓 Auto (follows your phone/computer setting), ☀️ Light or 🌙 Dark, remembered per browser

No build step and no dependencies: open `index.html` in a browser, or turn on GitHub Pages
(Settings → Pages → Deploy from branch → `/root`) to get a URL you can bookmark on your phone.

To change the menu, edit the `MEALS` object near the top of the script in `index.html`.
