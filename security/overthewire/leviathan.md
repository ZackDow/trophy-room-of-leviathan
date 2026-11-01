# OverTheWire: Leviathan

| Levels cleared | Last updated |
| :------------: | ------------ |
| **4** | 2026-10-18 |

> Lessons only. No passwords, no commands that solve a level.

## Level log

| Level | Concept | Lesson in one line |
| ----- | ------- | ------------------ |
| 0 → 1 | Hidden files | Hidden folders in the home directory are the first place to look |
| 1 → 2 | Tracing a binary | `ltrace` shows what a program compares your input against |
| 2 → 3 | Check versus use | When a program checks a filename one way and uses it another way, the gap between the two is the exploit |
| 3 → 4 | Tracing a binary | The level 1 idea again; recognising a repeat is the skill |

## Biggest lessons

- **The level loop:** look (`ls -la`, spot the setuid bit) → read every message → run it → trace it → name the gap between what it checks and what it does → craft the input → run it for real.
- **Tracing drops privileges.** The kernel ignores setuid on a traced process, so trace to read the logic and run it plainly to use the privilege.
- **Folder permissions matter.** The target user needs execute permission on every folder in a path, including my own working folder in `/tmp`.
- **Never pass untrusted text to a shell.** Spaces, `;`, `$()` and backticks get re-read as commands.

## Tools I now use comfortably

ltrace, strace, strings, file, ln
