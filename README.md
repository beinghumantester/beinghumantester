<div align="center">

## `whoami`

```
$ whoami
Ujjwal Kumar Singh — quality engineer, chronic skeptic, agentic AI builder

$ cat mission.txt
Started out writing test cases. Kept asking "why did that fail?"
until the question became the job. Now I build systems — human
and AI — that investigate failure instead of just reporting it.
```

<a href="https://github.com/BeingHumanTester">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=1B6E92&center=true&vCenter=true&width=650&lines=I+break+software+so+users+don't+have+to.;Transforming+flaky+tests+into+deterministic+insights.;Teaching+AI+agents+to+investigate%2C+not+just+execute.;Building+autonomous+testing+and+reasoning+engines." alt="Typing SVG" />
</a>

<br/>

<a href="https://www.linkedin.com/in/BeingHumanTester/"><img src="https://img.shields.io/badge/LinkedIn-1B6E92?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://beinghumantester.com/"><img src="https://img.shields.io/badge/Newsletter-FF6719?style=for-the-badge&logo=substack&logoColor=white"/></a>
<a href="https://www.youtube.com/@BeingHumanTester/"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/></a>
<a href="mailto:automatealchemist@gmail.com"><img src="https://img.shields.io/badge/Email-2E9E7A?style=for-the-badge&logo=gmail&logoColor=white"/></a>

</div>

<br/>

<details open>
<summary><h2>Issue Tracker — About Me</h2></summary>

<table>
<tr>
<td valign="top">

| # | Title | Labels | Status |
| :-- | :-- | :-- | :-- |
| <sub>#001</sub> | <sub>Doesn't fully trust "it works on my machine"</sub> | `skepticism` `evidence-based` | ![open](https://img.shields.io/badge/-open-2E9E7A) |
| <sub>#002</sub> | <sub>Prompts AI agents to investigate failures, not just run scripts</sub> | `agentic-testing` `ai` | ![open](https://img.shields.io/badge/-open-2E9E7A) |
| <sub>#003</sub> | <sub>Building an AI interview-prep assistant that grades reasoning</sub> | `side-project` `interviews` | ![in%20progress](https://img.shields.io/badge/-in%20progress-1B6E92) |
| <sub>#004</sub> | <sub>Writes about QA + AI on Substack instead of keeping notes private</sub> | `writing` `substack` | ![open](https://img.shields.io/badge/-open-2E9E7A) |
| <sub>#005</sub> | <sub>Used to just write test cases. Now asks *why* things break</sub> | `career-growth` | ![closed](https://img.shields.io/badge/-closed-8957e5) |

</td>
<td width="190" valign="top" align="center">
<img src="./assets/error.gif" width="180"/>
<br/>
<sub>me, encountering the one bug that only happens in prod</sub>
</td>
</tr>
</table>

<br/>


</details>

<details open>
<summary><h2>Journey So Far</h2></summary>

```
2021 ─ Started as a manual tester
        │ Learned to break things before users could
        │
2022 ─ Moved into automation
        │ Selenium, Pytest, CI pipelines
        │
2023 ─ Started asking "why," not just "what failed"
        │ Root-cause diagnostics over pass/fail reports
        │
2024 ─ Started writing prompts, not just test cases
        │ Prompt engineering for structured, testable AI output
        │
2025 ─ Evaluating LLMs, not just web applications
        │ Testing model behaviour, reasoning, and failure modes
        │
2026 ─ Now: teaching AI agents to investigate
        └ Agentic testing, autonomous root-cause analysis
```

<br/>


</details>

<details open>
<summary><h2>How My AI Agent Investigates a Failure</h2></summary>

```mermaid
flowchart LR
    A(["Signal detected<br/>failure / anomaly / crash"]) --> B["Agent ingests context:<br/>logs · stack trace · DOM snapshot"]
    B --> C["Form hypothesis on root cause"]
    C --> D["Reproduce in sandbox"]
    D --> E{"Hypothesis confirmed?"}
    E -- No --> F["Discard & generate<br/>new hypothesis"]
    F --> C
    E -- Yes --> G["Classify root cause<br/>flaky · regression · env · code"]
    G --> H{"Confidence high enough?"}
    H -- No --> I["Flag for human review"]
    I --> J(["Engineer investigates"])
    H -- Yes --> K["Auto-generate report:<br/>cause · evidence · suggested fix"]
    K --> L(["Handed off to dev queue"])

    style A fill:#1B6E92,color:#fff
    style F fill:#0F6E56,color:#fff
    style I fill:#D85A30,color:#fff
    style K fill:#2E9E7A,color:#fff
    style L fill:#2E9E7A,color:#fff
```

<sub>The loop behind my <strong>Agentic Testing Framework</strong> project — an AI agent doing the root-cause investigation on its own, escalating to a human only when it isn't confident.</sub>

<br/>


</details>

<details open>
<summary><h2>Test Coverage Report — Skills</h2></summary>

```
$ pytest --cov=beinghumantester --cov-report=term

Automation & Testing
  Python           ████████████████████  96%
  Selenium         ███████████████████░  92%
  Playwright       █████████████████░░░  85%
  Pytest           ██████████████████░░  88%

AI & Backend
  FastAPI          ██████████████░░░░░░  70%
  PyTorch          ████████████░░░░░░░░  60%
  OpenAI / LLMs     ████████████████░░░░  80%
  MCP              █████████████░░░░░░░  65%

DevOps & CI/CD
  Docker           ███████████████░░░░░  75%
  Jenkins          █████████████░░░░░░░  65%
  GitHub Actions   ████████████████░░░░  80%
  Git              ████████████████████  98%

------------------------------------------------
TOTAL                                     80%   PASSED
```

<br/>


</details>

<details open>
<summary><h2>Active Experiments & Flagship Projects</h2></summary>

<table>
<tr>
<td width="50%" valign="top">

**Pytest + Selenium Diagnostics** &nbsp; ![status](https://img.shields.io/badge/status-open-2E9E7A)
> Automated failure root-cause analysis
- Captures DOM state, browser logs, and network telemetry automatically on failure
- Turns raw stack traces into actionable reports

</td>
<td width="50%" valign="top">

**AI Interview Prep Assistant** &nbsp; ![status](https://img.shields.io/badge/status-in%20progress-1B6E92)
> Evaluating reasoning over memorization
- Scenario-driven AI interviewer
- Scores problem-solving pathways, not keyword matches

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Agentic Testing Framework** &nbsp; ![status](https://img.shields.io/badge/status-open-2E9E7A)
> Autonomous QA agents
- Runs exploratory test loops on its own
- Classifies crashes and reasons about root cause

</td>
<td width="50%" valign="top">

**Field Notes & Media** &nbsp; ![status](https://img.shields.io/badge/status-ongoing-8957e5)
> Thought leadership in QA & AI
- Long-form essays on automation architecture
- Talks & workshops on AI in testing

</td>
</tr>
</table>

<br/>


</details>

<details>
<summary><strong>Known Issues (aka quirks) — click to expand</strong></summary>
<br/>

| # | Behaviour | Repro Steps | Fix? |
| :-- | :-- | :-- | :-- |
| #101 | Rewrites a test 4 times before trusting it | Give it any flaky test | Won't fix |
| #102 | Reads the stack trace before reading the ticket | Assign any bug | By design |
| #103 | Asks "have you tried reproducing it?" mid-conversation | Report "it's broken" with no steps | Working as intended |

</details>

<br/>

<details open>
<summary><h2>GitHub Telemetry</h2></summary>

<div align="center">

<a href="https://github.com/BeingHumanTester?tab=followers"><img src="https://img.shields.io/github/followers/BeingHumanTester?style=for-the-badge&color=2E9E7A&labelColor=1B6E92"/></a>
<img src="https://img.shields.io/badge/Achievements-view%20on%20profile-1B6E92?style=for-the-badge"/>

<sub>GitHub's own Achievement badges (Pull Shark, Quickdraw, etc.) are earned automatically from activity and can't be embedded in a README — they show natively on your profile page as you merge more PRs.</sub>

<br/><br/>

<img height="165" src="https://streak-stats.demolab.com/?user=BeingHumanTester&theme=tokyonight&hide_border=true&ring=2E9E7A&fire=1B6E92&currStreakLabel=2E9E7A" />

<br/><br/>

<img src="https://raw.githubusercontent.com/BeingHumanTester/BeingHumanTester/output/github-contribution-grid-snake.svg" width="95%"/>

</div>

<br/>


</details>

<details open>
<summary><h2>Recent Activity</h2></summary>

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

<sub>Populated automatically by <a href="https://github.com/jamesgeorge007/github-activity-readme">jamesgeorge007/github-activity-readme</a> — add the action's workflow to this repo once, and your last 5 GitHub events (PRs, issues, commits) will refresh here on every push.</sub>

</details>

<br/>

## Words I Test By

<table>
<tr>
<td width="60%" valign="top">

> "Information is power. But like all power, there are those who want to keep it for themselves."
> — Aaron Swartz

</td>
<td width="40%" valign="top">

```
$ ./run_tests.sh
> When I don't test the code,
> I code to test the code.
```

</td>
</tr>
</table>

## Let's Connect & Collaborate

<div align="center">

I'm always open to discussing **test architecture, agentic AI frameworks, or quality engineering strategy**.

<a href="mailto:automatealchemist@gmail.com"><img src="https://img.shields.io/badge/Let's_Talk_Testing-2E9E7A?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1B6E92,100:2E9E7A&height=100&section=footer"/>

</div>
