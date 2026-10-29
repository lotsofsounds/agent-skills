# Lots of Sounds agent skills

CC0 sound effects for Claude Code, Codex, Cursor and other coding agents.
The agent searches [Lots of Sounds](https://lotsofsounds.com) and adds the
sound file to your project. All sounds are CC0, so no credit is necessary.

## Install

Claude Code:

```bash
/plugin marketplace add lotsofsounds/agent-skills
/plugin install lotsofsounds@lotsofsounds
```

Any agent that reads Agent Skills (Claude Code, Codex and others):

```bash
npx lotsofsounds skill install
```

Or with skills.sh:

```bash
npx skills add lotsofsounds/agent-skills
```

## Use

Ask your agent in plain words:

- "Add a click sound to the buttons."
- "The game needs jump, coin and game-over sounds."
- "Find rain ambience for the meditation page."

Free sample search works with no account. To search the full catalog and
download sounds, run `npx lotsofsounds login`. It opens the browser to sign in
or sign up.

Docs: https://lotsofsounds.com/docs/cli

## Privacy and license

- Privacy policy: https://lotsofsounds.com/privacy
- The skill and plugin files are MIT licensed. The sounds are CC0.
