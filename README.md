<!-- INGEN CORP // RESTRICTED DOCUMENT -->

<div align="center">

```
 ______  ______  ______  ______  ______  ______     ______  ______  ______  ______  
/\  ___\/\  ___\/\  ___\/\  ___\/\  ___\/\  ___\   /\  ___\/\  __ \/\  == \/\  == \ 
\ \  __\\ \ \___\ \ \___\ \  __\\ \___  \ \___  \  \ \ \___\ \ \_\ \ \  __<\ \  _-/ 
 \ \_____\ \_____\ \_____\ \_____\/\_____\/\_____\  \ \_____\ \_____\ \_\ \_\ \_\   
  \/_____/\/_____/\/_____/\/_____/\/_____/\/_____/   \/_____/\/_____/\/_/\/_/\/_/   
```

**`INGEN CORP // SITE B // ISLA SORNA`**

[![Live Site](https://img.shields.io/badge/LIVE-spac3gh0st00.github.io%2Fmagic--word-00ff41?style=flat-square&logo=github&logoColor=black)](https://spac3gh0st00.github.io/magic-word/)
![Status](https://img.shields.io/badge/STATUS-OPERATIONAL-00ff41?style=flat-square)
![Victims](https://img.shields.io/badge/VICTIMS-UNKNOWN-ffb000?style=flat-square)
![Made With](https://img.shields.io/badge/MADE_WITH-HTML_CSS_JS-00cfff?style=flat-square)
![Hosted On](https://img.shields.io/badge/HOSTED_ON-GitHub_Pages-ff2d2d?style=flat-square)

</div>

---

```
[SYS] Initializing...
[NET] Secure channel established...
[AUTH] Identity unverified. Proceed at your own risk.
```

## What is this?

An InGen Corp restricted-access terminal. Unauthorized personnel are prompted to enter **the magic word** before gaining access to Site B systems.

They will not gain access to Site B systems.

> *"Ah ah ah... you didn't say the magic word."*
> — Dennis Nedry, visionary

## How it works

```
index.html  ──►  INGEN landing page
                    │
                    ▼
             magicword.html  ──►  Enter the magic word
                    │
          ┌─────────┴──────────┐
          │                    │
       WRONG               correct
          │                    │
          ▼                    ▼
    Dennis Nedry          ACCESS GRANTED
    appears 🦕            (fake loading bar)
    "AH AH AH..."              │
                               ▼
                      fullscreen rick roll 🎵
                      [beforeunload trap armed]
                      [escape re-trap active]
                      [fake ✕ EXIT button]
```

## Features

| Feature | Description |
|---|---|
| 🖥️ CRT terminal aesthetic | Scanlines, vignette, phosphor glow, corner HUD decorations |
| 🦕 Dennis Nedry popups | 9+ escalating roast messages each wrong attempt |
| ⚡ Glitch animation | Terminal glitches on every wrong answer |
| 🔒 Fullscreen rick roll | Triggered directly in user gesture context — no bypass |
| 🚫 Fake EXIT button | Does nothing. Shows taunts instead |
| 🔁 Escape re-trap | `fullscreenchange` listener catches Escape key attempts |
| ⚠️ `beforeunload` trap | Browser "Leave site?" dialog on close/navigate |
| 🦖 Raptor claw favicon | SVG, embedded as data URI — no extra file |
| ⏱️ Live system clock | Running in the status bar at all times |

## File structure

```
magic-word/
├── index.html                    # INGEN landing page
├── magicword.html                # The trap
├── dennis_nedry.jpg              # The man himself
├── jurassic_park_background.jpg  # Background asset
├── jurassic_park_background_main.jpg
└── not here_fall.jpg
```

## Tech

Pure HTML, CSS, and vanilla JS. No frameworks, no dependencies, no build step. Hosted on GitHub Pages.

The fullscreen API fires synchronously inside the user gesture handler — this is intentional and required for browsers to honour the request. All the trap logic lives client-side in `magicword.html`.

---

<div align="center">

**[→ Enter if you dare ←](https://secrets.spac3gh0st.lol/)**

*InGen Corporation is not responsible for any loss of productivity, dignity, or sanity.*

</div>
