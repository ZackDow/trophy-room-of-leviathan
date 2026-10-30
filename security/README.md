# Security

Capture-the-flag challenges, wargames and practice rooms: what I solved and what it taught me.

| OverTheWire levels | picoCTF challenges | TryHackMe rooms |
| :----------------: | :----------------: | :-------------: |
| **48** | **41** | **19** |

## OverTheWire

Progress and lessons only. No passwords, no full solutions.

| Game | Focus | Levels cleared | Status |
| ---- | ----- | -------------: | :----: |
| [Bandit](overthewire/bandit.md) | Linux basics | 33 of 33 | ✅ |
| [Leviathan](overthewire/leviathan.md) | Abusing setuid programs | 4 of 7 | 🟨 |
| [Natas](overthewire/natas.md) | Web security | 11 | 🟨 |

## picoCTF

Writeups for past competitions and the picoGym practice gym only.

| Learning path | Modules | Challenges | Completed |
| ------------- | :-----: | :--------: | --------- |
| The Beginner's Guide to the Challenge Library | 28 of 28 | 24 | 2026-10-21 |
| General Skills in CTF's | 20 of 20 | 17 | 2026-10-21 |

| Challenge | Category | Event | Points | Solved |
| --------- | -------- | ----- | -----: | ------ |
| *First writeup coming soon* | | | | |

## TryHackMe

19 free rooms on Linux, networking, the web and Windows. [Full list](tryhackme.md).

## Next

| Step | Status |
| ---- | :----: |
| Finish Leviathan, levels 4 → 7 | 🟨 |
| Finish Natas, from level 11 | 🟨 |
| PortSwigger Web Security Academy: Apprentice labs | ⬜ |
| picoCTF: one challenge in every category, with writeups | ⬜ |
| pwn.college: Linux Luminarium, then Program Security | ⬜ |
| Hack The Box: Starting Point, then a first Easy machine | ⬜ |

Only systems I own or have permission to test.

## Layout

```
security/
├── picoctf/
│   └── <event or picogym>/
│       └── <challenge>.md      ← from templates/challenge-writeup.md
├── overthewire/
│   └── <game>.md               ← from templates/wargame-progress.md
└── tryhackme.md
```

Downloaded challenge files stay in `_private/`, never in the repo.
