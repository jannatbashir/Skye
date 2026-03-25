# Skye
A mobile wellness app for neurodivergent people — built for ADHD, autism, and dyslexia.
Live app → https://jannatbashir.github.io/Skye
## What it does
Skye adapts your day based on how you're actually feeling. Every morning, one tap tells Skye your mood. Skye calculates a Capacity Score (1–5) and adjusts what tasks you see, how many, and how hard they are — so your day fits your energy, not the other way around.
- One-tap morning check-in, no forms, no friction
- Capacity-adaptive task list — rest days show 2 tasks, flow days show everything
- "Not today" deferral with undo — tasks move to tomorrow without guilt
- Habit tracking without streaks — shows up as a constellation, never punishes a missed day
- Box breathing, grounding, and body scan built in
- Dyslexia-friendly font toggle
- Everything stored on your device — no account, no server, no data collection
## Why I built this
Most productivity apps were designed for neurotypical users. They use streaks, reminders, and overdue labels — patterns that are actively harmful for people with ADHD or autism. Skye is designed around the research: variable capacity, non-punishing feedback, and low-friction entry points.
## Product decisions worth noting
- Replaced a 3-step morning check-in with a single tap after research showed multi-step rituals have very low completion rates for ADHD users
- Removed streak counters entirely — replaced with a 7-day presence window ("4 of the last 7 days") that can never be "broken"
- Tasks on rest days are filtered by duration, not just count — a 90-minute deep work task doesn't appear on a score-1 day even if it's marked high priority
- "Not today" deferral never moves the task's creation timestamp — stale detection still works correctly after deferral
## How to use it
Open the live link on your phone. Tap the Share button, then "Add to Home Screen" for a full app experience.

## Status

Beta. Built as a 0-to-1 portfolio project — designed, specified, iterated, and shipped without a development budget.
