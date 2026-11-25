# Cross-Cultural Report Skill

An AI-agent skill for J-1 exchange teachers: generate blank English report forms, draft compliant domestic/virtual cross-cultural activity reports and lesson plans, and audit drafts against U.S. federal requirements (22 CFR §62.10).

## What's inside

| File | Purpose |
|---|---|
| `cross-cultural-report/SKILL.md` | Skill instructions (workflow, regulations, style rules) |
| `cross-cultural-report/references/requirements.md` | Field-by-field compliance checklist for audit mode |
| `cross-cultural-report/assets/01_cross_cultural_report.html` / `.docx` | Blank cover-sheet form |
| `cross-cultural-report/assets/02_lesson_plan.html` / `.docx` | Blank lesson-plan form |
| `cross-cultural-report/assets/03_domestic_report.html` / `.docx` | Blank domestic activity report form |
| `cross-cultural-report/assets/04_virtual_report.html` / `.docx` | Blank virtual exchange report form |

All four forms are fully blank, in English, and work in a browser (type directly, then print/save as PDF) or in Word/WPS.

## Install (WorkBuddy)

1. Copy the folder `cross-cultural-report/` into your skills directory:
   - Windows: `C:\Users\<you>\.workbuddy\skills\`
   - macOS/Linux: `~/.workbuddy/skills/`
2. Restart WorkBuddy (or reload skills).
3. The skill is available automatically. Try: "Help me write my domestic cross-cultural report" or "Give me a blank lesson plan form".

## Install (Claude Code / other SKILL.md-compatible agents)

Place `cross-cultural-report/` in the agent's skills directory (e.g. `.claude/skills/`). The SKILL.md frontmatter follows the standard `name` / `description` format.

## Use

The skill activates on requests like:

- "Make me a blank Cross-Cultural Report form"
- "Help me write my virtual exchange report"
- "Write the lesson plan for my culture activity"
- "Check my report — will it be accepted?"

Templates contain no personal data. When a filled report is requested, the skill asks for the teacher name, sponsor, dates, location, audience, and partner details rather than inventing them.

## License

MIT — free to use, share, and adapt. See `LICENSE`.

## Privacy note

This version contains no personal information about any teacher, school, or student. The templates are blank. If you adapt it for your own program, add your program's specific sponsor name, submission portal, and deadline in SKILL.md under "Program specifics".
