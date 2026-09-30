# Fitwell

Fitwell is a dependency-free starter dashboard for a coaching web app. It mirrors the supplied desktop dashboard reference with responsive mobile behavior.

## Current starter surface

- Blue Fitwell sidebar navigation
- Top utility bar with trainer, trial, support, alerts, messages, and account controls
- Check-ins chart and published check-in cards
- Meal plan, supplement, training, and cardio assignment panels
- Goals, habits, client notes, tracking, programs, and notes summaries
- Toast feedback for dashboard actions
- Responsive mobile navigation and stacked cards

## Run locally

From the project root:

```sh
ruby -run -e httpd . -p 4173 -b 0.0.0.0
```

Open `http://localhost:4173/` on the Mac. For iPhone testing, connect the phone to the same Wi-Fi and open the Mac's local network URL on port `4173` in Safari.

This is a visual and interaction starter. Dashboard buttons currently provide feedback but do not connect to a backend or persist data.
