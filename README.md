# TheHolyOneZ-Dream

> *A VSCodium-soul Discord theme. Deep navy, cyan mesh, drifting aurora. Chill. Terminal. Home.*

---

## Preview

![TheHolyOneZ-Dream Theme Preview](preview/preview.png)

---

## Philosophy

Not a hacker theme. Not neon green on black.  
This is the feeling of settling into VSCodium at midnight — familiar, focused, yours.

Deep navy backgrounds. JetBrains Mono everywhere. A barely-visible cyan mesh grid underneath everything. Two aurora blobs drifting imperceptibly in the background. Every interaction has a smooth, deliberate transition.

---

## Features

- **JetBrains Mono** — monospace font across the entire UI
- **Cyan mesh grid** — subtle two-layer graph-paper background (48px + 24px)
- **Drifting aurora** — two slow-moving radial blobs (blue + teal), GPU-composited
- **Full brand recolor** — Discord's blurple replaced with `#4ec9b0` (VSCode teal) throughout
- **Smooth micro-animations** — channels, server icons, buttons, reactions, badges, switches
- **Zero lag** — no `backdrop-filter` on structural panels, only Discord CSS variables for backgrounds
- **Dark & precise** — carefully tuned neutral scale, muted timestamps, uppercase category labels

---

## Installation

### BetterDiscord

1. Download [`TheHolyOneZ-Dream.theme.css`](./TheHolyOneZ-Dream.theme.css)
2. Move it to your BetterDiscord themes folder:
   - **Windows:** `%appdata%\BetterDiscord\themes\`
   - **macOS:** `~/Library/Application Support/BetterDiscord/themes/`
   - **Linux:** `~/.config/BetterDiscord/themes/`
3. Open Discord → **Settings → BetterDiscord → Themes**
4. Enable **TheHolyOneZ-Dream**

---

## Palette

| Role | Hex | Preview |
|---|---|---|
| Background void | `#07090f` | ![](https://placehold.co/12x12/07090f/07090f) |
| Background base | `#0b0e1a` | ![](https://placehold.co/12x12/0b0e1a/0b0e1a) |
| Background panel | `#131829` | ![](https://placehold.co/12x12/131829/131829) |
| Cyan accent | `#4ec9b0` | ![](https://placehold.co/12x12/4ec9b0/4ec9b0) |
| Blue secondary | `#5294e2` | ![](https://placehold.co/12x12/5294e2/5294e2) |
| Sky (links) | `#9cdcfe` | ![](https://placehold.co/12x12/9cdcfe/9cdcfe) |
| Text normal | `#a8b2c8` | ![](https://placehold.co/12x12/a8b2c8/a8b2c8) |
| Text muted | `#5d6a86` | ![](https://placehold.co/12x12/5d6a86/5d6a86) |
| Online | `#4ec994` | ![](https://placehold.co/12x12/4ec994/4ec994) |
| Idle | `#e0af68` | ![](https://placehold.co/12x12/e0af68/e0af68) |
| DND | `#f7768e` | ![](https://placehold.co/12x12/f7768e/f7768e) |

---

## Customization

Open the theme file and edit the variables at the top of `:root` to make it yours:

```css
:root {
  --cx-cyan:   #4ec9b0;  /* primary accent — change this to shift the whole theme */
  --cx-blue:   #5294e2;  /* secondary accent */
  --cx-bg-0:   #0b0e1a;  /* darkest background */
  --cx-font:   'JetBrains Mono', monospace;  /* swap font here */
}
```

---

## Compatibility

- ✅ BetterDiscord (stable)
- ✅ Discord dark mode
- ⚠️ Discord light mode (usable, not optimized)

---

## License

MIT — do whatever you want, just don't claim you made it from scratch.

---

<p align="center">made with too much coffee by <strong>TheHolyOneZ</strong></p>
