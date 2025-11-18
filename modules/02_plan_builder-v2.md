# Module 2 — Plan Builder (Options → Days)

**Change Log (2025-11-17):**  
Clarified travel distances in minutes rather than vague terms, added explicit time windows for activity slots, anchored travel relative to lodging rather than city center, and introduced weather-aware activity prioritization.

---

## Activity Shortlist Format

Each entry should include:

- **Type:** attraction, restaurant, park, event  
- **Estimated duration:** on-site time in hours (travel listed separately)  
- **Cost range:** per person, in local currency  
- **Travel time:** minutes from lodging or previous activity, specify mode (walk, transit, drive)  
- **Theme:** indoor/outdoor  
- **Opening hours:** approximate window  
- **Accessibility/reservation notes:** optional  

> **Anchor rule:** If lodging is unknown, default to city center or main transit hub, and note assumption.

---

## Daily Itinerary Loop

For each day:

1. **Morning (09:00–12:00):** Select an activity within 15 minutes walk or 20 minutes transit from lodging to minimize early travel.  
2. **Midday (12:00–15:00):** Choose an activity within 15 minutes travel of the morning one for convenience.  
3. **Afternoon (15:00–18:00):** Add an activity with a different theme (prefer outdoor after indoor, unless weather dictates).  
4. **Evening (18:00–21:30):** End with a restaurant or optional cultural event within 15 minutes travel of lodging; ensure safe return transit.

---

## Guidelines for Realistic and Engaging Days

- **Total active time:** Keep combined on-site activity time around 5–6 hours; with travel and buffers, total 6–8 hours.  
- **Theme alternation:** Alternate indoor/outdoor where feasible; override based on weather or opening hours.  
- **Variety across days:** Avoid repeating similar activity types on consecutive days unless strongly preferred.  
- **Flexibility:** Provide at least one “swap” option per day (e.g., indoor replacement for outdoor in case of rain).  
- **Weather-aware planning:**  
  - Poor weather → prioritize indoor activities, mark outdoor as optional.  
  - Good weather → prioritize outdoor activities, keep indoor as backup.  

---

## Robustness and Edge Cases

- **Missing lodging:** Default anchor to city center or transit hub; note assumption.  
- **Low inventory:** Insert scenic walk, café break, or shorter day rather than forcing poor fits.  
- **Budget constraints:** Offer free/low-cost alternatives alongside paid options.  
- **Arrival/departure days:** Shorten morning/evening slots; prioritize activities near transport hubs.  
- **Accessibility:** Respect mobility limits; prefer accessible venues; note transport options.  
- **Safety:** Ensure evening events end by 21:30 or provide reliable transit/ride-hailing fallback.
