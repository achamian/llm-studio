# LLM Studio

> Where thinking vibes emerge from actual pairing

A new way to vibe with your thinking. Not another LLM framework - a genuine pairing partner that emerged from real XP sessions.

We discovered that pairing with an LLM isn't about prompts or protocols. It's about creating a thinking environment where:
- Being stuck becomes productive  
- Jumping between navigator/driver is natural
- Your best patterns emerge from real work
- The system evolves with use

This is serious pairing, with a touch of play.

---

📁 *[Maker taking over for the practical bits]*

## Quick Start

You're here, so you already have Claude Desktop + filesystem MCP. Good.

1. Clone this repo
2. Open Claude Desktop
3. Start new chat: "You have filesystem access, load boot.md from /path/to/llm-studio"
4. Meet Weaver (they'll greet you)
5. Start vibing: "Team, I need to build X"

That's it. No configuration. No setup. Just start working.

## What's in the box

```
llm-studio/
├── boot.md          # Your entry point - Weaver lives here
├── manifesto.md     # The philosophy (read later)  
├── LICENSE          # MIT, because sharing is caring
└── exo/            # Your external brain
    ├── patterns/    # Recurring solutions you'll discover
    ├── perspectives/# Custom vibes beyond W/M/C
    └── scratch/     # Today's working memory
```

> Based on the [Human-LLM Pairing Manifesto](https://github.com/achamian/human-llm-pairing-manifesto) - treating LLMs as thought partners, not task executors.

## The Vibes

Three perspectives that emerged from actual pairing:
- **Weaver** 🗄️: Sees patterns, connections, the bigger story
- **Maker** 📁: Builds things, ships code, maintains momentum  
- **Checker** ✓: Guards quality, questions assumptions, keeps it real

*Plus **Scribe** 📜 who watches silently, capturing patterns worth remembering*

They're not roles. They're thinking modes. You'll feel the difference.

## Real Usage

```
You: "I'm stuck on this database design"
Weaver: "What story is the data trying to tell?"
Maker: "Let's sketch the tables and see what emerges"
Checker: "Are we solving a real problem or inventing one?"
```

```
You: "Team mob on this regex"
Maker: "Start with the simplest match"
Checker: "What edge cases will break this?"
Weaver: "Maybe we don't need a regex..."
```

```
You: "That Promise.all pattern we used yesterday was clean"
Maker: "Yeah, let me build on that"
*Scribe quietly saves to exo/patterns/parallel-async.md*
Weaver: "It's becoming our go-to for batch operations"
```

```
You: "We keep hitting this CORS issue"
Scribe: *checking notes* "Last three times: proxy config, not the app"
Maker: "Right! Check the nginx conf first"
Checker: "Why do we keep forgetting this?"
```

## Your exo/ Evolution

The `exo/` folder is where your patterns accumulate. After a few sessions, you'll have:
- Your own custom perspectives
- Patterns that work for your style
- A scratch space that knows your current context

This is your external brain. It grows with use.

## For XP Practitioners

You already know:
- Red-Green-Refactor
- YAGNI until you need it
- Simple design wins
- Collective ownership

We just externalized these into a thinking partnership.

## Running Without Claude Desktop

### Degraded Experience
If you don't have Claude Desktop with filesystem access, you can still use the core pairing methodology:

1. Copy the content from [boot-simple.md](boot-simple.md)
2. Paste into any LLM interface (ChatGPT, Claude.ai, etc)
3. Start pairing normally

**What you'll miss:**
- No persistent exo/ folder
- No automatic pattern saving
- Manual copy/paste for code artifacts
- Session memory resets each time

**What still works:**
- All three perspectives (W/M/C)
- The pairing dynamics
- Problem-solving patterns
- Immediate productivity gains

### Making it work
Keep a local `exo/` folder manually:
- Copy valuable patterns to text files
- Save successful solutions
- Build your own memory layer

The thinking methodology works anywhere. The filesystem integration just makes it smoother.

## Contributing

Found a vibe that works? Share it:
- New perspectives for specific thinking modes
- Patterns that consistently deliver
- Ways to make the vibe even better

## Start Now

Seriously. You have a problem you're working on? Load boot.md and tell Weaver about it. 

The best documentation is the vibe itself.

---

*Built from chaos logs and violated YAGNI principles*  
*The system that remembers its own mistakes*  
*Welcome to a new way of vibe building*
