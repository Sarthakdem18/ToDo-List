# ✦ TO-DO List

## ✦ Preview

```
┌─────────────────────────────────┐
│                                 │
│  daily workflow                 │
│  TASK S                         │
│                                 │
│  12 total   8 done   4 remaining│
│  ████████████░░░░░░░  67%       │
│                                 │
│  [ add a new task...        ] + │
│  [low]  [mid]  [high]           │
│                                 │
│  [all]  [active]  [done]        │
│                                 │
│  ▌ ☐  Write the README    LOW   │
│  ▌ ☑  Ship the app        HIGH  │
│  ▌ ☐  Touch grass         MID   │
│                                 │
└─────────────────────────────────┘
```

---

## ✦ Features

- **Priority tagging** — mark tasks as `LOW` / `MID` / `HIGH` before adding
- **Filter tabs** — view all, active-only, or completed tasks
- **Progress bar** — glowing acid-green tracker that fills as you complete tasks
- **Live stats** — total, done, and remaining counts update in real time
- **Persistent storage** — tasks survive page reloads via `localStorage`
- **Animations** — tasks slide in on creation and out on deletion
- **Zero dependencies** — pure HTML, CSS, and vanilla JS in a single file

---

## ✦ Usage

No build step. No install. Just open it.

```bash
# Option 1: open directly in your browser
open todo.html

# Option 2: serve locally
npx serve .
# → http://localhost:3000/todo.html

# Option 3: drag the file into any browser tab
```

---

## ✦ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Enter` | Add task |

---

## ✦ Design System

| Token | Value | Usage |
|-------|-------|-------|
| `--bg` | `#0a0a0b` | Page background |
| `--surface` | `#111114` | Task card background |
| `--accent` | `#c8f135` | Primary accent (acid green) |
| `--accent2` | `#ff4d6d` | Destructive actions |
| `--text` | `#e8e8f0` | Body text |
| `--muted` | `#555568` | Placeholder / secondary text |

**Fonts:** `Bebas Neue` (display) · `DM Mono` (body)

---

## ✦ Priority Colors

| Priority | Color | Hex |
|----------|-------|-----|
| LOW | 🟢 | `#4ade80` |
| MID | 🟡 | `#fbbf24` |
| HIGH | 🔴 | `#ff4d6d` |

---

## ✦ File Structure

```
todo.html          ← the whole app (HTML + CSS + JS, ~300 lines)
README.md          ← you are here
```

---

## ✦ Customization

All colors live in CSS custom properties at the top of the file — easy to retheme:

```css
:root {
  --bg: #0a0a0b;
  --accent: #c8f135;   /* ← change this to repaint the whole app */
}
```

---

## ✦ Browser Support

Works in any modern browser. No polyfills needed.

`Chrome` · `Firefox` · `Safari` · `Edge`

---

<div align="center">

</div>
