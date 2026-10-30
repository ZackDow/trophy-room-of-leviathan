# OverTheWire: Natas

| Levels cleared | Started | Last updated | Status |
| :------------: | ------- | ------------ | ------ |
| **11** | 2026-10-21 | 2026-10-23 | 🟨 In progress, next is level 11 |

> Progress and lessons only. No passwords, no requests that solve a level.

## Level log

| Level | Date | Concept | Lesson in one line |
| ----- | ---- | ------- | ------------------ |
| 0 → 1 | 2026-10-21 | Page source | Developers leave things in HTML comments |
| 1 → 2 | 2026-10-21 | Client-side blocks | Blocking right-click hides nothing; the browser's developer tools see everything |
| 2 → 3 | 2026-10-21 | Directory listing | An open folder listing exposes every file in it |
| 3 → 4 | 2026-10-21 | robots.txt | Telling search engines what to skip also tells attackers where to look |
| 4 → 5 | 2026-10-22 | Request headers | The Referer header is set by the client, so it proves nothing |
| 5 → 6 | 2026-10-22 | Cookies | A cookie that says "logged in" can be edited by the user |
| 6 → 7 | 2026-10-23 | Included files | Files the server includes can sometimes be fetched directly |
| 7 → 8 | 2026-10-23 | Local file inclusion | A page parameter that takes a path can read files it was never meant to |
| 8 → 9 | 2026-10-23 | Encoding is not encryption | A homemade encoding can be undone by running its steps backwards |
| 9 → 10 | 2026-10-23 | Command injection | User input placed inside a shell command becomes part of the command |
| 10 → 11 | 2026-10-23 | Filter bypass | A blocklist of bad characters always misses something |

## Biggest lessons

- Anything the browser sends (headers, cookies, form fields) is under the attacker's control.
- Read the source the page offers before trying anything clever.

## Tools I now use comfortably

Browser developer tools
