### Exploits are written by AI agents. Defenses should be too.

I work on mobile security, and these days most of that work runs through them.

Right now that means mobile VAPT: agent-driven SAST, DAST, and red teaming, to see how far agents get against mobile apps and their protections.

The other half turns it around: checking what agents write. Writing code got fast; knowing whether the code does what you asked did not. So I write down what software is supposed to do in a form a machine can read, and have a machine check the code against it. cladding does that, and LogcatOn is built with it.

#### Building

| Project | Stars | What it does |
|---|---|---|
| **[LogcatOn](https://github.com/purpleeddy/logcat-on-releases)** | [![GitHub stars](https://img.shields.io/github/stars/purpleeddy/logcat-on-releases?style=flat&color=gold)](https://github.com/purpleeddy/logcat-on-releases) | Android logcat that follows your app's PID and flags crashes, ANRs, and native faults the moment they happen. |
| **[cladding](https://github.com/purpleeddy/cladding)** | [![GitHub stars](https://img.shields.io/github/stars/purpleeddy/cladding?style=flat&color=gold)](https://github.com/purpleeddy/cladding) | An integrity layer for AI-coded software: intent in before the agent writes, a spec check after. |
| **[agents-md-lab](https://github.com/purpleeddy/agents-md-lab)** | [![GitHub stars](https://img.shields.io/github/stars/purpleeddy/agents-md-lab?style=flat&color=gold)](https://github.com/purpleeddy/agents-md-lab) | What an AGENTS.md or CLAUDE.md file actually changes: ten files surveyed, one pre-registered experiment. |
