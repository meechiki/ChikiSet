# LOGSET — Workout Set, Rest & Day Tracker

A single-file HTML workout tracker: log sets and reps, run a rest timer, and
build your own training-day schedule (e.g. a 5-day split) with per-date
history.

**Note:** Unofficial personal tool. Not a substitute for coaching or medical
advice — adjust weights and volume to your own condition.

## Usage

Open `workout-tracker.html` in any browser — no install, no server needed.

### คลังท่าออกกำลังกาย (Exercise Library)
- ~140 exercises across 12 muscle-group categories (Chest, Back, Shoulders,
  Biceps, Triceps, Forearms, Abs/Core, Quads, Hamstrings, Glutes, Calves,
  Cardio & Plyo, Olympic & Power).
- Filter by category tab or search by name.
- Tap an exercise to expand it, log weight (kg) and reps per set, delete sets
  individually.

### ตารางของฉัน (My Schedule)
- Create your own training days (e.g. `Day 1 - Chest/Triceps`).
- Add exercises to each day from the full library via the picker.
- Each day has a date selector (defaults to today) — sets are logged **per
  date**, so history doesn't overwrite itself.
- History chips let you jump back to any previously logged date for that day.
- A 7-day streak strip shows which days this week you actually trained.

### Rest Timer
- Floating widget, collapsible.
- Presets: 30 / 60 / 90 / 120 / 180 seconds, or trigger straight from any
  exercise's "⏱ พัก 90s" button.
- Beeps (and vibrates, on supported devices) when the countdown hits zero.

## Data & storage

Everything — logged sets, custom days, and session history — is saved to your
browser's `localStorage`. It stays on this device/browser only:
- Clearing browser data or switching devices resets everything.
- Nothing is sent over the network; all calculation and storage is local.

## What it does not do (yet)

- No cloud sync or multi-device support.
- No progress charts (e.g. weight lifted over time per exercise).
- No export to PDF/CSV.

Let me know if you'd like any of these added.
