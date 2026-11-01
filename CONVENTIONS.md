# Conventions

## Commit messages

```
<area>: <what was finished>
```

| Area | Use for | Example |
| ---- | ------- | ------- |
| `course` | Course units, weeks or whole courses | `course: finish CS50x week 2 (arrays)` |
| `ctf` | picoCTF writeups | `ctf: picoGym "Mod 26" writeup` |
| `otw` | OverTheWire progress | `otw: Bandit levels 0-10, progress and lessons` |
| `leetcode` | LeetCode problems | `leetcode: 0001 two-sum (hash map)` |
| `note` | Note summaries | `note: linear algebra, eigenvalues summary` |
| `trophy` | Trophy pages | `trophy: add futures backtesting engine` |
| `timeline` | Monthly entries | `timeline: close November` |
| `docs` | README and templates | `docs: add CS50x to the front page` |
| `chore` | Repo housekeeping | `chore: compress images in notes/` |

- Lowercase after the colon, present tense, 72 characters or fewer.
- One finished thing per commit.
- Commit when the work happens. Never change commit dates and never split work into extra commits to fill the graph.

## Naming

- Folders and files: lowercase with hyphens, e.g. `courses/harvard/cs50x/README.md`.
- LeetCode: four-digit problem number first, e.g. `leetcode/0001-two-sum/`.
- Timeline: `timeline/YYYY-MM.md`.
- Dates inside pages: `YYYY-MM-DD`.

## Images

- Prefer a written summary. Add an image only when a diagram or screenshot says something text can't.
- Screenshots as `.png` or `.webp`; photos as `.jpg` or `.webp`.
- At most 1600 px wide and under 300 KB each.
- Strip metadata before committing. Phone photos carry GPS location. On Windows: right-click the file → Properties → Details → *Remove Properties and Personal Information*.
- Put images next to the page that uses them, in an `img/` folder.

## Keep it local

Anything that must never be published goes in `_private/` at the repo root. Git ignores it. Use it for university work, OverTheWire passwords, downloaded challenge files and raw photos.

## Before every commit

- [ ] No assessed university work
- [ ] No OverTheWire passwords or full solutions
- [ ] picoCTF writeup is for a past competition or the practice gym
- [ ] No course solutions that the course's honour code asks me to keep private
- [ ] No student ID, email, address or location, including in screenshots and image metadata
- [ ] Images compressed
- [ ] Front page and timeline updated with what was finished
- [ ] Only done and in progress: no plans, no "next", no disclaimers on public pages
