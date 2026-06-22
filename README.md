# AI Token Efficient

A collection of lightweight AI instruction sets designed to reduce token consumption, limit verbose responses, and improve coding efficiency across any AI assistant.

Compatible with:

* Claude Code
* Trae
* Cursor
* Windsurf
* Cline
* Roo Code
* OpenCode
* VS Code AI extensions
* ChatGPT Projects
* Any AI tool supporting custom instructions or rule files

---

## Why?

Most AI assistants tend to:

* Repeat the user's request
* Generate unnecessary explanations
* Add introductions and conclusions
* Produce excessive educational content
* Waste tokens on low-value output

These rules aim to:

* Reduce token usage
* Improve response density
* Increase coding efficiency
* Keep answers focused on implementation
* Reduce AI operating costs

---

## Available Profiles

### Universal

Balanced profile suitable for most users.

Focus:

* Concise responses
* Minimal explanations
* General-purpose usage

File:

```txt
universal.txt
```

---

### Coding

Optimized for software development.

Focus:

* Code-first responses
* Minimal explanations
* Faster implementation

File:

```txt
coding.txt
```

---

### Debugging

Optimized for troubleshooting.

Focus:

* Root cause identification
* Direct fixes
* Minimal noise

File:

```txt
debugging.txt
```

---

### Minimal

Most aggressive token-saving profile.

Focus:

* Extremely short responses
* Maximum token efficiency
* No unnecessary output

File:

```txt
minimal.txt
```

---

## Installation

Copy the content of the desired profile into your AI tool's custom instructions, system prompt, rules file, or project configuration.

Examples:

* Claude Code → `CLAUDE.md`
* Cursor → Project Rules
* Trae → AI Rules
* Cline → System Prompt
* Roo Code → Custom Instructions

---

## Design Principles

The rules follow these principles:

1. Correctness over verbosity
2. Simplicity over complexity
3. Implementation over education
4. Reuse over duplication
5. Minimal tokens, maximum value

---

## Contributing

Pull requests are welcome.

Ideas:

* New profiles
* AI-specific adaptations
* Performance improvements
* Token reduction experiments

---

## License

MIT License
