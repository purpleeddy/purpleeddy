### Hi, I'm purpleeddy

I work on mobile security, and these days most of that work runs through AI agents.

> _"Exploits are written by AI agents. Defenses should be too."_

Right now that means mobile VAPT: agent-driven SAST, DAST, and red teaming, to see how far
agents get against mobile apps and their protections.

The other half turns it around: checking what agents write. Writing code got fast;
knowing whether the code does what you asked did not. So I write down what software is
supposed to do in a form a machine can read, and have a machine check the code against it.
cladding does that, and LogcatOn is built with it.

#### Building

- **[LogcatOn](https://github.com/purpleeddy/logcat-on-releases)** [![GitHub stars](https://img.shields.io/github/stars/purpleeddy/logcat-on-releases?style=flat&color=gold)](https://github.com/purpleeddy/logcat-on-releases) - The log is where you find out what an app actually did. Bind to a package and LogcatOn follows the PID, re-binding when the app restarts; crashes, ANRs, and native faults land on the timeline the moment they happen. macOS, Windows, Linux · free.
- **[cladding](https://github.com/purpleeddy/cladding)** [![GitHub stars](https://img.shields.io/github/stars/purpleeddy/cladding?style=flat&color=gold)](https://github.com/purpleeddy/cladding) - An integrity layer for AI-coded software: before an agent writes, it supplies the project's intent; after, it checks the result against the spec for drift, tests, architecture, and evidence.
- **[agents-md-lab](https://github.com/purpleeddy/agents-md-lab)** [![GitHub stars](https://img.shields.io/github/stars/purpleeddy/agents-md-lab?style=flat&color=gold)](https://github.com/purpleeddy/agents-md-lab) - Evidence for agent instruction files: ten AGENTS.md and CLAUDE.md files surveyed against sourced criteria, plus a pre-registered experiment on what an instruction file actually changes.
