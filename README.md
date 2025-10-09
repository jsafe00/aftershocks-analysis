# PHIVOLCS Aftershocks Analysis

This project is for my **personal learning**.
I became interested in understanding **earthquakes and aftershocks** after the **Magnitude 6.9 earthquake in Cebu on September 30, 2025**.

It fetches earthquake records (date, magnitude, depth, and location) and displays them using charts and maps to help me better visualize earthquake aftershock patterns.

---

## Visualizations

### 🗺️ Map
- This shows the locations of the aftershocks.
- Each circle is an earthquake.
- The size of the circle depends on the earthquake’s magnitude (stronger = bigger).
- The color tells you if it’s a smaller or stronger quake (e.g. orange for smaller, red for stronger).
👉 You can look at this map to see where aftershocks are happening.

---

### 📈 Magnitude vs Time
- This is a scatter chart (dots on a graph).
- The X-axis (horizontal) is time – when the aftershock happened.
- The Y-axis (vertical) is magnitude – how strong it was.
👉 This lets you see how the strength of aftershocks changes over time (for example, if they’re getting weaker as days go by).

---


### 📊 Magnitude Frequency (Histogram)
- This is a bar chart.
- The X-axis is the magnitude values (like 2.5, 3.0, 3.5…).
- The Y-axis is how many earthquakes happened at each magnitude.
👉 It shows what magnitudes are most common (usually many small quakes, fewer big ones).
---


### 🌊 Depth vs Magnitude
- This is another scatter chart.
- The X-axis is the depth (how deep underground the quake started, in kilometers).
- The Y-axis is the magnitude (strength).
👉 This helps to see if deeper earthquakes tend to be stronger or weaker than shallow ones.
---

### 📈 Cumulative Aftershocks
- This is a line chart.
- It shows the total number of aftershocks over time.
- The line keeps going up every time a new aftershock happens.
👉 You can see if aftershocks are happening quickly at first and then slowing down, or still coming steadily.
---

### 📊 Daily Aftershocks (Count, Average, Max Magnitude)
- This chart mixes bars and lines:
- Bars = how many aftershocks happened each day.
- Red line = the average magnitude of quakes that day.
- Orange dashed line = the strongest quake that day.
👉 This lets you compare days:
  - Were there many small quakes?
  - Or a few stronger ones?
  - Did the biggest quake happen early or later?

- Data source: PHIVOLCS (Philippine Institute of Volcanology and Seismology).
