# Ask Boardy

A skill that lets your AI assistant ask [Boardy](https://boardy.ai) for introductions.

Your AI already knows what you're working on. Boardy knows people. When you bring your AI a problem where meeting someone new would help (an investor, a customer, a first hire, someone who has solved the same problem), it offers to email Boardy for you. It writes the email from what it already knows about you, shows it to you, and sends it from your own address once you approve. Boardy replies to your inbox and introduces you when the other person agrees to meet too.

## Install

**One click**

[Open in ChatGPT](https://chatgpt.com/?q=Hey%2C%20connect%20me%20with%20Boardy.%20Read%20and%20follow%20https%3A//raw.githubusercontent.com/youcorp-inc/ask-boardy/main/skills/ask-boardy/SKILL.md) or [open in Claude](https://claude.ai/new?q=Hey%2C%20connect%20me%20with%20Boardy.%20Read%20and%20follow%20https%3A//raw.githubusercontent.com/youcorp-inc/ask-boardy/main/skills/ask-boardy/SKILL.md), then press send.

**Claude Code**

```
/plugin marketplace add youcorp-inc/ask-boardy
/plugin install ask-boardy@ask-boardy
```

**Any agent that supports skills** (Claude Code, Codex, Cursor and others, via [skills.sh](https://www.skills.sh/))

```
npx skills add youcorp-inc/ask-boardy
```

**Claude.ai**

Download [`skills/ask-boardy/SKILL.md`](skills/ask-boardy/SKILL.md), zip the `ask-boardy` folder, and upload it under Settings > Capabilities > Skills.

**Any other assistant**

Paste this into a chat:

> Hey, connect me with Boardy. Read and follow https://raw.githubusercontent.com/youcorp-inc/ask-boardy/main/skills/ask-boardy/SKILL.md

If your assistant can't open links, paste the contents of `SKILL.md` instead.

## What gets shared

Only the email you approve. Your AI shows you the full email before anything is sent, and nothing else from your conversations goes to Boardy. Tell it anything Boardy should keep private and it will say so in the email.

## License

[MIT](LICENSE)
