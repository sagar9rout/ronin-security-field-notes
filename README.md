# RONIN SECURITY FIELD NOTES

> Practical cybersecurity notes, lab investigations, and writeups by **RONIN.SH**.

This repository documents hands-on learning across web exploitation, digital forensics, general security skills, and reverse engineering. Each writeup aims to explain not only **what** was done, but **why** each step mattered and how to interpret the evidence.

## Categories

| Category | Focus |
|---|---|
| [`01-web-exploitation/`](./01-web-exploitation/) | Authorized web application testing, vulnerability analysis, and remediation |
| [`02-digital-forensics/`](./02-digital-forensics/) | Evidence handling, artifact analysis, timelines, and investigation notes |
| [`03-general-security-skills/`](./03-general-security-skills/) | Networking, Linux, enumeration, security fundamentals, and cross-domain labs |
| [`04-reverse-engineering/`](./04-reverse-engineering/) | Static/dynamic analysis of binaries and understanding program behavior |

## Writeup standards

For each substantial writeup, include where applicable:

1. **Objective and scope** — platform, challenge/lab name, and authorization context.
2. **Environment** — operating system, target type, and relevant tool versions.
3. **Concepts** — the security concepts being tested.
4. **Methodology** — ordered steps and why each step was chosen.
5. **Commands and observations** — actual commands, meaningful output, and interpretation.
6. **Findings or solution** — verified results only; respect platform spoiler rules.
7. **Defensive relevance** — impact, detection opportunities, and remediation.
8. **Lessons learned** — what worked, what did not, and what to investigate next.
9. **Evidence** — sanitized screenshots/logs; remove tokens, credentials, personal data, and sensitive host details.

## Safety and ethics

- Test only systems you own or have explicit permission to assess.
- Stay within the lab's defined scope and rules.
- Never publish credentials, tokens, personal information, or other sensitive data.
- Respect platform rules before sharing flags, answers, or challenge spoilers.
- Distinguish observed facts from hypotheses. Never invent outputs, flags, screenshots, or successful results.

## Reusable writeup template

Copy this outline into a new Markdown file and adapt it to the challenge:

```markdown
# [Writeup title]

## Overview
- **Platform:**
- **Challenge/Lab:**
- **Category:**
- **Difficulty:**
- **Status:** In progress / Completed
- **Scope/Authorization:**

## Objective
What are you trying to learn or verify?

## Environment
List the relevant OS, tools, versions, and lab setup.

## Concepts
Explain the core concepts in your own words.

## Investigation
### Step 1 — [Action]
**Why:** Why this step is useful.

**Command/action:**
```text
Paste the actual command or action here.
```

**Observation:**
Record the actual result, redacting sensitive information.

**Interpretation:**
Explain what the result means and what it does not prove.

## Findings / Verified solution
Document only conclusions supported by evidence.

## Defensive relevance
Explain detection, prevention, or remediation.

## Lessons learned
- What did you learn?
- What would you do differently?
- What should be tested next?

## Evidence
Add sanitized screenshots or log references if useful.
```

## Platforms

Platform names (such as PicoCTF, TryHackMe, Hack The Box, or OverTheWire) belong in each writeup's metadata—not in separate top-level folders.

## Repository status

This starter contains category guides and a reusable template. Individual writeups will be added as labs are completed and evidence is verified.
