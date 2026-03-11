# time_finder_web

A lightweight, single-page **Flight Time Calculator** for pilots and aviation enthusiasts. Calculates both **Block Time** (Out → In) and **Flight Time** (Takeoff → Landing) in Zulu (UTC) using 24-hour format.

## Features

- Calculates **Block Time** and **Flight Time** independently
- Displays results in both **HH:MM** and **decimal hours** formats
- Auto-formats time input (HHMM → HH:MM) as you type
- Detects and labels **overnight / midnight-crossing** flights
- Input validation with error highlighting
- Live **Zulu (UTC) clock** — current date and time updated every second
- **ICAO airport local time lookup** — type any 4-letter ICAO code to see the airport's current local time (370+ airports worldwide)
- Dark, aviation-styled UI

## Usage

Open `index.html` in any modern browser — no build step or server required.

### Flight Time Calculator

Enter Zulu times in `HH:MM` format:

| Field    | Description                        |
|----------|------------------------------------|
| Out      | Wheels away from the gate          |
| In       | Wheels stopped at the gate         |
| Takeoff  | Wheels-off (airborne)              |
| Landing  | Wheels-on (touchdown)              |

Results update live as you type.

### Zulu Clock

The current UTC date and time are displayed at the top of the page and update every second.

### ICAO Local Time Lookup

Type a 4-letter ICAO airport code (e.g. `CYOW`, `KJFK`, `EGLL`) into the input box to instantly see the airport's current local time in `City · HH:MML` format, updated every second.

Over 370 airports are supported across Canada, USA, Mexico, Caribbean, South America, Europe, Middle East, Asia, Oceania, and Africa.

## Tech

Plain HTML, CSS, and vanilla JavaScript — zero dependencies.

---

**V1.1** — 10 March 2026 · © Marcil25
