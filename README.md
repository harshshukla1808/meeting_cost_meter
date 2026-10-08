# Meeting Cost Meter

A live meeting cost tracker built with HTML, CSS and vanilla JavaScript. Start the meter and watch how much a meeting costs, second by second.

**Live demo:** <apna-netlify-link-yahan>

## Features
- Live cost counter in ₹ that updates in real time
- Multiple roles, each with headcount and hourly rate
- Start, Pause, Resume and Reset controls
- Shows elapsed time, cost per minute and total people
- Last 5 meetings saved in localStorage
- Responsive light-blue UI, works on mobile and desktop
- Input validation with clear error messages

## Tech Stack
- HTML5
- CSS3 (custom properties, grid, flexbox)
- Vanilla JavaScript (ES6+)
- No frameworks, no libraries

## How It Works
Total cost per hour = sum of (people × hourly rate) across all roles.
The timer uses timestamps (`Date.now()`) instead of counting ticks, so the cost stays accurate even if the tab is in the background.

## Run Locally
1. Download or clone this repo
2. Open `index.html` in any browser

## Author
Harsh Shukla
