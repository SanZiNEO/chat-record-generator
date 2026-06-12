# Chat Record Generator

A highly customizable tool for generating chat record screenshots, designed for academic researchers preparing experimental stimuli and survey materials.

## Quick Start

1. Open `聊天记录生成器.html` in any modern browser
2. Add messages and adjust styles in the left panel — preview updates in real time on the right
3. Click **Export JSON** to save configuration and messages; import to restore later

No installation, no server — a single HTML file that works offline.

## Features

- **Message types**: text, image, and system messages
- **Per-role style controls**: independently configure avatars (show/hide, size, position), nicknames, timestamps, bubble color/radius/shadow/arrow, text font size/color/line height/alignment/bold/italic — separately for each side
- **Layout presets**: left-right, all-left, all-right, centered, text-only flow, staggered — one-click switching without resetting custom styles
- **Customizable header bar**: name text/size/color/alignment, back button, avatar (show/hide, position left/center/right, local image upload)
- **Configurable chat area**: background color, preview width (300–900px or auto-fit)
- **JSON import/export**: complete serialization of configuration + messages for reproducibility and version control
- **Message selection**: click to select any message, then edit or delete

## Research Applications

Chat screenshots are widely used as experimental stimuli in:

- Consumer behavior (customer service interactions, product inquiries)
- Human–computer interaction (AI assistant and chatbot evaluation)
- Educational technology (online tutoring, peer dialogue)
- Social psychology (interpersonal communication, emotional expression)

Every visual parameter is exposed as an independent control, allowing researchers to precisely manipulate each detail while keeping experimental conditions isolated to the intended independent variables. Exported JSON files can be included as supplementary materials in papers for full reproducibility.

## Technical Notes

Pure static HTML (CSS + JavaScript). No frameworks, no build tools, no dependencies (icon library optional). Data-driven rendering — configuration changes refresh the preview instantly.

## License

MIT
