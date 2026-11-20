# CUBS Daily Record

Mobile questionnaire prototype for parents to record a child's day on a 24-hour timeline:
school/childcare, night sleep, nap, physical activity (type + indoor/outdoor), screen time and
non-screen activities, followed by three questions about time outdoors.

Live page: https://ziwaka99.github.io/cubs-daily-record/

- Single self-contained `index.html` (no build step).
- On wide screens the page is shown inside a phone frame; on phones it runs full screen.
- Note: responses are not sent anywhere yet. On submit the page keeps the answers in the browser
  and posts them to a parent window (`child-schedule-submit` message) for embedding in a survey platform.
