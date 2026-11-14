# healthy-diet

A single static page (`index.html`) that tells you what to eat today.

- **5 meals a day**: breakfast, morning snack, lunch, afternoon snack and dinner, each with ingredients, short prep steps, approximate kcal and protein
- **Changes every day** but stays the same for a given date. Each meal type works through its whole list before anything repeats, so you don't get the same dish on two days in a row
- **Vegetarian mode**, a **shopping list** for the day and a **this-week overview** (click a row to open that day)
- Tick meals as eaten, track glasses of water and get a daily tip. These are saved in your browser only
- Use the ← / → keys or buttons to look at other days
- **Theme button** cycles Auto (follows your phone/computer setting) → Light → Dark, and remembers your choice

No build step and no dependencies: open `index.html` in a browser, or turn on GitHub Pages
(Settings → Pages → Deploy from branch → `/root`) to get a URL you can bookmark on your phone.

To change the menu, edit the `MEALS` object near the top of the script in `index.html`.
