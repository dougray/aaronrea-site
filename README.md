# aaronrea-site

Personal site for **Aaron Rea** — cloud security & infrastructure engineer.
Portfolio, bio, and technical writing.

- GitHub: https://github.com/Aaronrea
- LinkedIn: https://www.linkedin.com/in/aaronmrea/

## Stack

A single hand-written `index.html`. No build step, no dependencies, no JavaScript —
all styling is inline CSS custom properties.

## Local preview

```
python3 -m http.server 4123 -d .
```

Then open http://localhost:4123.

## Theme — "Circuit Mint"

A light take on cyberpunk: pale ground, near-black ink, neon used only as accent.
The cyberpunk read comes from mono type, `//` labels, chamfered corners and the grid
background rather than from darkness.

Palette tokens live on `:root` in `index.html`:

| Token | Value | Notes |
|---|---|---|
| `--bg` | `#eef3ef` | pale phosphor ground |
| `--ink` | `#0d1a13` | near-black, green cast |
| `--accent` | `#007a50` | terminal green |
| `--hot` | `#b34a08` | signal orange |

⚠️ `--accent` and `--hot` are contrast-tuned to roughly 4.8:1 against `--bg` and 4.5:1
on the tinted chip backgrounds. They carry small mono text (`//` labels, post tags,
chips). Brighter, prettier versions of these colors fail WCAG AA — don't lighten them.

## TODO

- [ ] Aaron to confirm the GitHub handle used for the project cards
- [ ] Replace placeholder About copy (3 paragraphs, marked in-file)
- [ ] Replace the 4 sample post titles/dates in the Writing section
- [ ] Fill in the email address in the About sidebar
- [ ] Decide: stay static, or move to Hugo so posts are markdown
- [ ] Pick a deploy target (GitHub Pages likely)
