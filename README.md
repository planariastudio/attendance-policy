# Attendance & Compensation Policy

The Planaria Studio policy on attendance, working hours, leave and pay, with the
GoodDay steps attached to each rule.

**Live:** https://planariastudio.github.io/attendance-policy/

It is a chapter of the [Employee Handbook](https://planariastudio.github.io/planaria-employee-handbook/),
which is the parent document. Where this policy and the handbook disagree, the handbook wins.

## What is in it

| Part | Covers |
|---|---|
| 1 | Attendance: what counts as a record, the daily standup, time off requests, the 25th cut-off |
| 2 | Hours and standby windows |
| 3 | Time off and leave: monthly days off, the N+2 rollover, annual leave, sick leave, absence |
| 4 | Compensation: pay schedule, salary structure, overtime, the religious holiday allowance |
| 5 | Quick reference and the legal basis |

Clauses are numbered (1.1, 3.6, 4.5) so a contract, a warning letter or a payroll
query can cite one directly.

## Structure

```
index.html    the whole policy, one self-contained page
```

No build step and no dependencies. The only thing loaded from outside is the web font,
from Google Fonts.

## Editing it

Do not edit `index.html` here. It is generated. The source lives in the working
directory outside this repo:

```
attendance-guide.html     the source
./build-web.sh            regenerates this repo's index.html
```

Edit the source, run the build, then upload the result.

## Who can read it

The page carries `noindex`, so search engines are asked to skip it. That is not a lock:
anyone with the address can open it, and GitHub Pages on a free account is public.
Keep the address to the team. Do not add client names, staff personal data, or anything
confidential.

## Where it appears

Embedded in GoodDay at **Staff Hub → Employee Handbook**, on the
*Attendance & Compensation* tab. The address never changes, so the embed picks up a new
version on its own once this repo is updated.
