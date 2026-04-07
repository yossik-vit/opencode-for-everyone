# OpenCode Adaptation Guide

This document explains how the "Claude Code for Everyone" course has been adapted for OpenCode users.

## What Changed

### 1. Core References
- All references to "Claude Code" have been changed to "OpenCode"
- References to "Opus 4.5" have been changed to "MiMo model"
- Terminal commands updated from `claude` to `opencode`

### 2. Lesson Modules
Each lesson module has been adapted:
- `CLAUDE.md` files → `OPENCODE.md` files
- Instructions updated for OpenCode workflow
- Interactive prompts maintained but context adjusted

### 3. Installation Instructions
The installation process differs between tools:

**Claude Code (Original):**
```bash
# Install
curl -fsSL https://claude.ai/install.sh | bash
# Or with Homebrew
brew install --cask claude-code
# Authenticate
claude
```

**OpenCode (Adapted):**
```bash
# Install (refer to OpenCode documentation)
# Authenticate (refer to OpenCode documentation)
opencode
```

### 4. Course Structure
The overall structure remains the same:
- **Module 0:** Getting Started (Introduction, Installation, Download & Start)
- **Module 1:** Fundamentals (8 lessons covering core features)
- **Module 2:** Vibe Coding (5 lessons building a real app)

## Key Differences Between Claude Code and OpenCode

| Feature | Claude Code | OpenCode |
|---------|-------------|----------|
| **Model** | Opus 4.5 (Claude) | MiMo (Xiaomi) |
| **Installation** | Custom installer | Standard package manager |
| **Authentication** | Claude account | OpenCode auth |
| **Ecosystem** | Anthropic tools | Open-source ecosystem |

## How to Use This Adaptation

### For Learners
1. Clone this repository
2. Follow the adapted installation instructions
3. Work through the lesson modules in order
4. Use the interactive prompts as designed

### For Contributors
1. Fork this repository
2. Create a feature branch
3. Make your changes to the OPENCODE.md files
4. Submit a pull request

## Lesson Module Files

Each lesson module contains:
- `CLAUDE.md` - Original Claude Code instructions
- `OPENCODE.md` - Adapted OpenCode instructions

The adaptation maintains:
- Interactive learning format
- "STOP" points for user engagement
- Step-by-step progression
- Practical exercises

## Future Improvements

Areas for further adaptation:
1. **Tool-specific features** - Highlight unique OpenCode capabilities
2. **Examples** - Add OpenCode-specific examples
3. **Troubleshooting** - Create OpenCode-specific troubleshooting guides
4. **Community** - Build OpenCode community around the course

## Credits

- **Original Course:** Carl Vellotti ([X](https://x.com/carlvellotti) / [LinkedIn](https://www.linkedin.com/in/carlvellotti/))
- **OpenCode Adaptation:** [Yossik Vit](https://github.com/yossik-vit)

## License

This adaptation follows the same license as the original course. Please refer to the original repository for licensing information.
