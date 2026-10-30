# OverTheWire: Bandit

| Levels cleared | Finished |
| :------------: | -------- |
| **33 of 33** ✅ | Before 2026-10-18 |

> Progress and lessons only. No passwords, no commands that solve a level.

## Level log

| Levels | Concept | Lesson in one line |
| ------ | ------- | ------------------ |
| 0 → 6 | Files and search | Odd filenames (leading dashes, spaces, hidden files) need careful paths, and `find` can filter by size, owner and permissions |
| 6 → 12 | Text processing | Small tools chained with pipes turn a huge file into the one line that matters |
| 12 → 13 | File formats | `file` tells you what something really is; the extension can lie |
| 13 → 17 | Networks and keys | SSH keys need strict permissions; plain TCP and TLS services need different clients; scan before guessing a port |
| 17 → 19 | Remote commands | SSH can do more than open an interactive shell |
| 19 → 20 | setuid | A setuid program runs with its owner's rights, not yours |
| 20 → 24 | Jobs and cron | Background jobs, scheduled tasks, and my first shell script |
| 24 → 25 | Scripting | A loop over one connection beats thousands of manual tries |
| 25 → 27 | Shell escapes | Pagers and editors can often launch a shell |
| 27 → 32 | Git | Secrets survive in history, branches and tags long after they're "deleted" |
| 32 → 33 | Restricted shells | Knowing how the shell works lets you step around its restrictions |

## Biggest lessons

- Read the task, the hints and every error message before guessing.
- `man` decides how a command's options work. One dash for letters, two for words, with old exceptions like `find` and `openssl`.
- When a trick repeats from an earlier level, recognising it is the skill.

## Tools I now use comfortably

ssh, scp, find, grep, sort, uniq, strings, base64, tr, xxd, gzip, bzip2, tar, nc, openssl, nmap, cron, git
