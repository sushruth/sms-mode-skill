# sms-mode

Agent replies tend to stack several points and questions into one long message. This skill makes the agent send one point at a time, as a short text message in simple English.

```bash
npx skills add sushruth/sms-mode-skill -a github-copilot
```

Drop `-a github-copilot` to install into every agent the CLI finds. Add `-g` to install under your home folder. In Copilot CLI, say "SMS mode".

## Let the agent install it

Paste this into Copilot CLI or any coding agent:

```text
Install the sms-mode skill from https://github.com/sushruth/sms-mode-skill. Run `npx skills add sushruth/sms-mode-skill -g -y -a <your agent id>`, using the id the skills CLI uses for you (github-copilot for Copilot CLI). If npx is unavailable, download SKILL.md from that repo into your user-level skills folder under sms-mode/. Then tell me the path you installed it to.
```
