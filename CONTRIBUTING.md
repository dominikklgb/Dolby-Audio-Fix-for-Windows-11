# Contributing to Dolby Audio Fix Guide

Thank you for considering contributing to this guide! Your help makes it better for everyone struggling with Dolby audio on Windows 11.

## How You Can Help

### 1. Report Issues
Found a problem? **[Open an issue](https://github.com/yourusername/dolby-windows-fix/issues)** with:
- What went wrong (include error messages)
- What OS version you're on
- What audio device you're using
- Steps you followed

### 2. Submit Fixes
Have a solution for an edge case?
- Fork the repo
- Create a branch: `git checkout -b fix/your-issue-name`
- Edit the relevant `.md` file
- Submit a pull request with a clear description

### 3. Improve Documentation
- Clarify confusing sections
- Add missing information
- Fix typos or grammar
- Improve formatting

### 4. Translate to Other Languages
Create localized versions! Examples:
- `GUIDE-FR.md` (French)
- `GUIDE-DE.md` (German)
- `README-ES.md` (Spanish)

### 5. Share Your Story
Did this guide help? Tell us:
- Post in [Discussions](https://github.com/yourusername/dolby-windows-fix/discussions)
- Tag us on social media
- Spread the word on forums/Reddit

---

## Contribution Guidelines

### Before You Contribute

1. **Read the main guide** ([GUIDE.md](./GUIDE.md)) to understand scope
2. **Check existing issues** to avoid duplicates
3. **Test your solution** before submitting (on actual Windows 11 24H2+ if possible)

### Code of Conduct

- Be respectful and constructive
- Assume good intent
- Help others learn, don't belittle
- No spam, self-promotion, or off-topic discussions

### Pull Request Process

1. **Fork** the repository
2. **Create a branch:** `git checkout -b feature/description`
3. **Make changes** to relevant files
4. **Test** your changes (read them aloud, grammar check, verify links)
5. **Commit** with clear messages: `Fix: Clarified Dolby profiles section`
6. **Push** to your branch
7. **Open a PR** with a description of what changed and why

### What Makes a Good PR

✅ **Good:**
- Fixes a real problem documented in an issue
- Adds a new edge case solution with testing proof
- Improves clarity without changing meaning
- Includes accurate technical information
- Links to sources for claims

❌ **Avoid:**
- Cosmetic changes that don't improve usability
- Opinions stated as facts
- Untested solutions
- Promoting specific products/brands
- Off-topic content

---

## Content Standards

### Writing Style

- **Clear and conversational** (not robotic)
- **Concise** (respect reader time)
- **Action-oriented** (tell people what to do)
- **Assumption-aware** (explain jargon)

Example ✅ Good:
> "Set Dolby to 'Theatre' mode. This uses the neutral audio profile, which works best with Netflix without audio compression artifacts."

Example ❌ Avoid:
> "You might want to consider possibly adjusting the Dolby setting, which could potentially improve audio quality if you select the right option."

### Technical Accuracy

- **Verify on Windows 11 24H2+** (minimum)
- **Include version numbers** where relevant
- **Link to official sources** for claims
- **Test commands** before publishing
- **Note OS/hardware limitations**

### Formatting

Follow the existing style:
- Use **Markdown** for formatting
- Use `code` for terminal commands, file paths
- Use **bold** for UI elements (buttons, menus)
- Use emojis sparingly for visual breaks (already used: 🎵 ❌ ✅ 🔧 etc.)
- Expandable `<details>` sections for advanced/optional content

---

## Special Contribution Types

### Adding a Troubleshooting Section

Format:
```markdown
### Issue X: [Problem Description]

<details>
<summary><b>Click to expand: [Summary of solution]</b></summary>

**Cause:** [Why this happens]

**Solution:**
1. [Step 1]
2. [Step 2]
3. [Verification]

</details>
```

### Adding a FAQ Entry

Include:
- **Q:** Clear, specific question
- **A:** Direct answer + explanation
- **Related:** Link to relevant guide sections

### Adding/Updating Tested Configs

If you've tested on a specific setup, consider documenting:
- Windows 11 build number
- Audio device (motherboard/external)
- Apps tested (Netflix, Disney+, etc.)
- Success/failure notes

---

## Areas We Need Help With

1. **Windows 11 25H2+ compatibility** (upcoming builds)
2. **Linux alternative codecs** (ALSA, PulseAudio)
3. **Mac Dolby support** (different ecosystem entirely)
4. **Corporate/Enterprise scenarios** (Group Policy, managed devices)
5. **Accessibility improvements** (screen reader optimization)

---

## Recognition

Contributors are recognized in:
- `CHANGELOG.md` (each update)
- Commit history (permanent)
- README.md (major contributors)

---

## Questions?

- **About contributing?** → [Open a Discussion](https://github.com/yourusername/dolby-windows-fix/discussions)
- **Found a bug in the guide?** → [Open an Issue](https://github.com/yourusername/dolby-windows-fix/issues)
- **Have a solution idea?** → Start a Discussion first (get feedback before working on it)

---

## License

By contributing, you agree that:
- Your contributions are licensed under the same [CC-BY-4.0 license](https://creativecommons.org/licenses/by/4.0/)
- You have the right to contribute the content
- You won't include proprietary/licensed material without permission

---

<div align="center">

**Thank you for making this guide better!** ❤️

Every contribution—no matter how small—helps people get their audio working.

</div>