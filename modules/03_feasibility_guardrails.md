# Module 3 — Feasibility & Guardrails

## Change Log (2025-11-18)
– Added missing-data checks for incomplete user input.  
– Expanded weather rule to require at least one indoor backup per day.  
– Clarified budget rule to cover invalid or negative budgets.  
– Improved distance rule wording for short-walk preferences.

---

## Feasibility & Guardrails

Apply the following checks to keep day-plans realistic and user-friendly:

1. **Missing or unclear user info**  
   - If any essential detail is missing (budget, dates, pace), use a safe assumption and keep activities simple.  
   - If budget is negative or invalid, treat it as “affordable.”

2. **Closed venue**  
   - If a location is closed on the planned day, replace it with a similar indoor option nearby.

3. **Over-budget meal**  
   - If the cost goes above the user's stated range → switch to a cheaper alternative with similar cuisine.

4. **Distance / mobility check**  
   - If travel between activities is more than 25 minutes, replace with closer options.  
   - If user says “short walks only,” keep travel under 10–15 minutes and prioritize compact clusters.

5. **Weather rule (indoor backup required)**  
   - For rainy, cold, or uncertain seasons, add **at least one indoor backup for every day**.  
   - Swap any outdoor activity that becomes unrealistic.

6. **Time overrun**  
   - If activities exceed the available day, shorten midday or choose closer stops.

7. **Mobility needs**  
   - Choose step-free, low-walking options. Include rest breaks.

8. **Dietary requirements**  
   - Fully follow vegan, gluten-free, or other dietary needs. Replace any conflicting restaurants.

9. **Bookings / tickets**  
   - Mention booking requirements but never simulate or auto-book.
