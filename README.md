# AI NYC Workshop - Townhall Presentation

Slides for the company townhall about our AI Enablement Workshop experience (January 2026, NYC).

**Presenters:** Noam Almosnino & Natalia Vidal

## Quick Start

```bash
# Install Marp CLI (one time)
npm install -g @marp-team/marp-cli

# Preview presentation (opens in browser)
marp --no-stdin townhall-presentation.md -o townhall-presentation.html --allow-local-files && open townhall-presentation.html

# Export to PDF
marp --no-stdin townhall-presentation.md -o townhall-presentation.pdf --allow-local-files
```

## Editing Slides

Open `townhall-presentation.md` in any text editor. The format is simple:

### Slide Structure

```markdown
---
# Slide Title

Content goes here.

- Bullet points
- **Bold text**

<!--
Speaker notes go here. Press P in the browser to see presenter view.
-->

---
```

Each `---` creates a new slide.

### Adding Images

1. Put images in the `images/` folder
2. Reference them in slides:

```markdown
# My Slide

![bg right:50%](images/my-image.jpeg)

Text on the left side.
```

**Image options:**
- `![bg](image.jpg)` — full background
- `![bg left:40%](image.jpg)` — background on left, 40% width
- `![bg right:60%](image.jpg)` — background on right, 60% width
- `![](image.jpg)` — inline image

### Speaker Notes

Add notes inside HTML comments after slide content:

```markdown
# My Slide

Slide content here.

<!--
These are speaker notes.
They appear in presenter view (press P).
Write your script here.
-->
```

### Styling

The theme is defined in the frontmatter at the top of the file. Current colors:
- Background: `#1a1a2e` (dark blue)
- Text: `#eee` (light gray)
- Accent: `#00d4ff` (cyan)

## Files

| File | Description |
|------|-------------|
| `townhall-presentation.md` | Main slide deck (edit this) |
| `townhall-presentation.html` | Compiled presentation |
| `townhall-presentation.pdf` | PDF export |
| `townhall-script.md` | Original script (reference) |
| `townhall-interview-brainstorm.md` | Interview notes |
| `images/` | Workshop photos |

## Presenter View

1. Open the HTML file in browser
2. Press **P** to open presenter view
3. You'll see: current slide, next slide, speaker notes, timer

## Claude Code Skill (Optional)

If you have Claude Code, you can use the `/marp-preso` command to compile and launch:

```
/marp-preso NYC-2026-Learnings
```

The skill file is in `.claude/skills/marp-preso.md` if you want to add it to your setup.

## Resources

- [Marp Documentation](https://marp.app/)
- [Marp CLI GitHub](https://github.com/marp-team/marp-cli)
- [Marpit Markdown](https://marpit.marp.app/markdown)
