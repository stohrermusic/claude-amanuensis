# Claude Amanuensis

Conversation memory for Claude Code.

**No code. Just say the magic words.**

## What is it?

A memory system for Claude Code. It watches your conversations, identifies meaningful moments (decisions, insights, solutions), and preserves them in a searchable log system (stored locally).

([What's an amanuensis?](https://en.wikipedia.org/wiki/Amanuensis))

## How to install

1. Open the [guide](https://stohrermusic.github.io/claude-amanuensis/)
2. Copy the setup prompt
3. Paste it into Claude Code
4. Restart your session

That's it. Claude builds the entire system for you.

## Requirements

- Claude Code CLI
- Python 3.10+
- `ANTHROPIC_API_KEY` environment variable
- **Anthropic API credits** — $5 minimum purchase, should last months unless you're an exceptionally heavy user

## Commands

After setup:

```bash
aman search "query"                  # search your conversation history
aman topic "topic"                   # AI summary of work on a topic
aman remember                        # save last 3 interactions verbatim
aman remember <literally anything>   # AI interprets and saves appropriately
```

## License

MIT
