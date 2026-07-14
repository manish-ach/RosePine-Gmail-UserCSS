# 🌹 Rose Pine Gmail

A [Rosé Pine](https://rosepinetheme.com/) (main variant) UserCSS theme for Gmail,
built for [Stylus](https://github.com/openstyles/stylus). Base `#191724` — matches
Rose Pine terminals and editors seamlessly.

Two-tone layout: sidebar and header sit on **base** (`#191724`), the mail list and
reading pane on **surface** (`#1f1d2e`), unread rows raised on **overlay** (`#26233a`).

## ✨ Features

- Full Rose Pine main palette across the Gmail UI — header, sidebar, mail list,
  reading pane, compose window, menus, dialogs, search
- Rethemes Gmail at the source by overriding its Material 3 design tokens
  (`--gm3-sys-color-*`), so native components (buttons, pills, hovers, tooltips)
  follow the palette automatically
- Configurable accent color: Rose / Love / Gold / Pine / Foam / Iris
- Unread rows visually raised, subtle read rows, accent-highlighted selected folder
- Themed scrollbars (width configurable)
- Optional dark backdrop behind email bodies (toggleable — HTML emails keep
  their own colors)

## 📦 Install

1. Install the [Stylus](https://chromewebstore.google.com/detail/clngdbkpkpeebahjckkjfobafhncgmne)
   browser extension
2. **Recommended:** set Gmail's built-in theme to **Dark**
   (⚙ → Theme → View all → Dark) so anything the style doesn't cover falls back
   to dark instead of white
3. Open the raw file and Stylus will show its install screen:

   https://github.com/manish-ach/RosePine-Gmail-UserCSS/raw/main/RosePineGmail.user.css

   Or manually: Stylus → Manage → tick **"as UserCSS"** → Write new style →
   paste the file contents → Save

## ⚙️ Configuration

Click the style's gear icon in the Stylus popup:

| Option | Default | Description |
| ------ | ------- | ----------- |
| Accent color | Rose | Rose / Love / Gold / Pine / Foam / Iris |
| Dark backdrop behind email bodies | On | HTML emails keep their own colors; rare emails with dark text on transparent backgrounds may need this off |
| Scrollbar width | 8px | Themed scrollbar thickness |

## 🎨 Palette

| Role | Color |
| ---- | ----- |
| Sidebar / header | `#191724` (base) |
| Content area | `#1f1d2e` (surface) |
| Unread rows / menus | `#26233a` (overlay) |
| Text | `#e0def4` / `#908caa` / `#6e6a86` |
| Accents | `#ebbcba` `#eb6f92` `#f6c177` `#31748f` `#9ccfd8` `#c4a7e7` |

## ⚠️ Known limitations

- Email bodies are intentionally left untouched — HTML emails carry their own
  colors, and CSS cannot safely invert them
- Gmail's obfuscated class names change between builds; if a surface goes white
  after a Gmail update, open an issue with a screenshot and the element's class
  from DevTools

## 🙏 Credits

- Palette by [Rosé Pine](https://rosepinetheme.com/)
- Built with [Claude Code](https://claude.com/claude-code)
