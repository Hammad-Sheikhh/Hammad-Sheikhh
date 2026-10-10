# Hammad Sheikh

Engineer in Islamabad, Pakistan, working across embedded firmware and web applications.

Most of what I build starts as a written spec and ends as something that runs outside my own laptop: on a rover, on a phone, or on a public URL. The repositories below are the working record of that.

[Portfolio](https://hammad-sh.netlify.app) · [Email](mailto:hammadsheikh.cs@gmail.com) · [Instagram](https://instagram.com/hamad.exe_)

## Current work

- **Streakwise** - core features are live. A final polish pass is next.
- **RED FLAG** - the AI driving mode runs on the simulator and is waiting for its test on the real rover.
- **vocabtracker** - planning stage. Choosing the stack and the data format before writing any code.

## Projects

| Project | Summary | Stack | Source |
|---|---|---|---|
| **Streakwise** | Time and progress tracker for people running several courses, projects and goals in parallel. Includes reports, share links and a per-account Claude connector. [Live](https://streakwise-ap.netlify.app) · [Demo](https://streakwise-ap.netlify.app/demo) | TypeScript, React, Vite, Tailwind, Supabase | [streakwise](https://github.com/Hammad-Sheikhh/streakwise) |
| **RED FLAG** (Mars rover) | Two-board ESP32 rover. One board drives and logs telemetry, the other streams camera images, and a Python ground station lets an AI model choose the next move within firmware safety limits. | C++, ESP32, ESP32-CAM, Python, Supabase | [mars-rover](https://github.com/Hammad-Sheikhh/mars-rover) |
| **Ledger** | Household money tracker with a monthly spending diary and budgeted shopping sessions. Installable on a phone, signs in by email link, and has no build step. | JavaScript, HTML, CSS, Supabase | Private |
| **vocabtracker** | German vocabulary app that gives words from a teacher, videos, AI tools and self-study one consistent structure for review. | To be decided | Private |
| **Portfolio** | The static site behind [hammad-sh.netlify.app](https://hammad-sh.netlify.app). Self-hosted fonts, no third-party requests, strict security headers. | HTML, CSS, Netlify | Private |

## How I work

- **Spec first.** Requirements and milestones are written down before the code, and kept in the repository next to it.
- **Tested.** Unit and browser tests on the web side, a simulator on the hardware side, and CI on every push.
- **Documented.** Each public repository has a README that gets a new reader from clone to running, plus a licence.
