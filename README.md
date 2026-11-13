# sms-mode

`sms-mode` makes a coding agent reply like a text message. Each reply carries one point or one question.

```bash
npx skills add sushruth/sms-mode-skill -a github-copilot
```

## Install for another agent

Remove `-a github-copilot` to install into every agent the CLI finds. Add `-g` to install in your home folder.

## Let the agent install it

Paste this prompt into Copilot CLI or another coding agent:

```text
Install the sms-mode skill from https://github.com/sushruth/sms-mode-skill. Run `npx skills add sushruth/sms-mode-skill -g -y -a <your agent id>`, using the id the skills CLI uses for you (github-copilot for Copilot CLI). If npx is unavailable, download SKILL.md from that repo into your user-level skills folder under sms-mode/. Then tell me the path you installed it to.
```

## Turn it on

Say "SMS mode" to the agent. The agent also loads the skill when you ask for short replies.

## What changes

The agent writes in Simplified Technical English (ASD-STE100). Sentences are short and active, with one idea each. The whole skill is `SKILL.md`, under 1 KB.
