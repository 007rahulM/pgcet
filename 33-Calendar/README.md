# Calendar — Overview

Calendar problems find the day of the week for any date, or count forward/backward from a known day. Expect **1–2 questions** in MCA PGCET.

## Patterns in This Folder

| File | Pattern | Recognition Clue |
|------|---------|-----------------|
| [Pattern1-Day-After-N-Days.md](./Pattern1-Day-After-N-Days.md) | Day of week after N days | "If today is Monday, what day is it after 50 days?" |
| [Pattern2-Odd-Days-and-Dates.md](./Pattern2-Odd-Days-and-Dates.md) | Finding the day for a specific calendar date | "What day is 15 August 1947?", "When is the next Friday after 28 Feb 2026?" |

## The Golden Rules

> **Divide N by 7. The remainder = number of days to count forward.**
> e.g. 50 days → 50 ÷ 7 = 7 weeks + **1 remainder** → 1 day ahead of start day.

> **Odd days:**
> - 1 ordinary year = 1 odd day
> - 1 leap year = 2 odd days
> - 100 years = 5 odd days
> - 400 years = 0 odd days (calendar repeats)

## Day Code Table

| Code | Day |
|------|-----|
| 0 | Sunday |
| 1 | Monday |
| 2 | Tuesday |
| 3 | Wednesday |
| 4 | Thursday |
| 5 | Friday |
| 6 | Saturday |

## Leap Year Rules

- Divisible by 4 → leap year (e.g. 2024 ✓)
- Divisible by 100 but NOT by 400 → NOT a leap year (e.g. 1900 ✗, 2100 ✗)
- Divisible by 400 → leap year (e.g. 2000 ✓)

## Study Order

Pattern 1 (simple N-days-forward problems) → Pattern 2 (full date-to-day calculation using odd days).
