# TheHolyOneZ-Dream

> *A VSCodium-soul Discord theme. Deep navy, cyan mesh, drifting aurora. Chill. Terminal. Home.*

---

## Gallery

<table>
  <tr>
    <td align="center" width="50%">
      <img src="preview/overview-effect-on.gif" width="100%" alt="With circuit trace effect"/>
      <br/>
      <sub><b>✦ With background effect</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="preview/overview-effect-off.png" width="100%" alt="Without circuit trace effect"/>
      <br/>
      <sub><b>Without background effect</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center" colspan="2">
      <sup>Toggle by setting <code>--cx-bg-effect: 1</code> (on) or <code>0</code> (off) at the top of the theme file</sup>
    </td>
  </tr>
</table>

<br/>

<table>
  <tr>
    <td align="center" width="50%">
      <img src="preview/overview.gif" width="100%" alt="Overview"/>
      <br/>
      <sub><b>Overview</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="preview/chat.png" width="100%" alt="Chat"/>
      <br/>
      <sub><b>Chat</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="preview/sidebar.png" width="100%" alt="Sidebar"/>
      <br/>
      <sub><b>Sidebar &amp; Channels</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="preview/settings.png" width="100%" alt="Settings"/>
      <br/>
      <sub><b>Settings</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="preview/context-menu.png" width="100%" alt="Context Menu"/>
      <br/>
      <sub><b>Context Menu</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="preview/code-block.png" width="100%" alt="Code Blocks"/>
      <br/>
      <sub><b>Code Blocks</b></sub>
    </td>
  </tr>
</table>

<details>
  <summary><b>More screenshots</b></summary>
  <br/>
  <table>
    <tr>
      <td align="center" width="33%">
        <img src="preview/profile.png" width="100%" alt="Profile Popout"/>
        <br/>
        <sub><b>Profile Popout</b></sub>
      </td>
      <td align="center" width="33%">
        <img src="preview/voice.png" width="100%" alt="Voice Channel"/>
        <br/>
        <sub><b>Voice Channel</b></sub>
      </td>
      <td align="center" width="33%">
        <img src="preview/emoji.png" width="100%" alt="Emoji Picker"/>
        <br/>
        <sub><b>Emoji Picker</b></sub>
      </td>
    </tr>
  </table>
</details>

---

## Philosophy

Not a hacker theme. Not neon green on black.  
This is the feeling of settling into VSCodium at midnight — familiar, focused, yours.

Deep navy backgrounds. JetBrains Mono everywhere. A barely-visible cyan mesh grid underneath everything. Two aurora blobs drifting imperceptibly in the background. Every interaction has a smooth, deliberate transition.

---

## Features

- **JetBrains Mono** — monospace font across the entire UI
- **Circuit trace effect** — PCB-style right-angle paths with racing glow streaks and endpoint flashes (toggleable)
- **Drifting aurora** — two slow-moving radial blobs (blue + teal) in the base background
- **Full brand recolor** — Discord's blurple replaced with `#4ec9b0` (VSCode teal) throughout
- **Smooth micro-animations** — channels, server icons, buttons, reactions, badges, switches
- **Zero lag** — no `backdrop-filter` on structural panels, only Discord CSS variables for backgrounds
- **Dark & precise** — carefully tuned neutral scale, muted timestamps, uppercase category labels

---

## Installation

### BetterDiscord

1. Download [`TheHolyOneZ-Dream.theme.css`](./TheHolyOneZ-Dream.theme.css)
2. Move it to your themes folder:
   - **Windows:** `%appdata%\BetterDiscord\themes\`
   - **macOS:** `~/Library/Application Support/BetterDiscord/themes/`
   - **Linux:** `~/.config/BetterDiscord/themes/`
3. Open Discord → **Settings → BetterDiscord → Themes**
4. Enable **TheHolyOneZ-Dream**

### Vencord

1. Download [`TheHolyOneZ-Dream.theme.css`](./TheHolyOneZ-Dream.theme.css)
2. Move it to your themes folder:
   - **Windows:** `%appdata%\Vencord\themes\`
   - **macOS:** `~/Library/Application Support/Vencord/themes/`
   - **Linux:** `~/.config/Vencord/themes/`
3. Open Discord → **Settings → Vencord → Themes**
4. Enable **TheHolyOneZ-Dream**

### Online / Web (Vencord)

No download needed — paste this directly into **Settings → Vencord → Themes → Online Themes**:

```
https://raw.githubusercontent.com/TheHolyOneZ/TheHolyOneZ-Dream/main/TheHolyOneZ-Dream.theme.css
```

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

### Toggle the background effect

Open `TheHolyOneZ-Dream.theme.css` in any text editor and find the top of `:root`:

```css
--cx-bg-effect: 1; /* ← change to 0 to disable */
```

| Value | Result |
|---|---|
| `1` | Circuit trace animation **on** |
| `0` | Circuit trace animation **off** |

Save the file, then press **Ctrl+R** in Discord to reload.

### Other variables

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
