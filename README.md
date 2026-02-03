# Supalytics Skills

Agent skills for [Supalytics](https://supalytics.co) CLI - works with Claude Code, OpenClaw, and skills.sh.

## Available Skills

| Skill | Description |
|-------|-------------|
| [supalytics-cli](./supalytics-cli/) | Query web analytics data - pageviews, visitors, revenue, conversions, and more |

## Installation

### Claude Code

```bash
cp -r supalytics-cli ~/.claude/skills/
```

### skills.sh (Vercel)

```bash
npx skills add supalytics-co/skills --skill supalytics-cli
```

### OpenClaw / ClawHub

```bash
clawhub install supalytics-cli
```

Or manually:
```bash
cp -r supalytics-cli ~/.openclaw/skills/
```

## Requirements

- [Bun](https://bun.sh) runtime
- [@supalytics/cli](https://www.npmjs.com/package/@supalytics/cli) installed globally

```bash
curl -fsSL https://bun.sh/install | bash
bun add -g @supalytics/cli
```

## License

MIT
