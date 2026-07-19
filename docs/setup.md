# Setup

This profile is intentionally made from portable SVG, Markdown, and a single GitHub Action. Fork or create a repository whose name exactly matches your GitHub username, then replace the example handle `Ayushsingh3129` everywhere it appears.

## Personalize the profile

1. In `README.md`, change each `Ayushsingh3129` URL and stats parameter to your GitHub username.
2. Open `assets/banner.svg`, `assets/about.svg`, `assets/terminal.svg`, and `assets/footer.svg` in any text editor. Change visible copy such as the name, role, project name, and terminal output.
3. Change the ICARUS repository and documentation links in `assets/project.svg` to real destinations.
4. In `.github/workflows/snake.yml`, the action automatically uses the repository owner, so no username edit is needed. It commits generated files to an `output` branch.

## Colors

All custom artwork shares the same palette. Search the SVG files for these values to retheme it consistently:

| Purpose | Color |
| --- | --- |
| Deep background | `#05010F` |
| Panel background | `#0D0221` |
| Purple primary | `#B026FF` |
| Pink secondary | `#FF2FBE` |
| Soft glow | `#E879F9` |
| Main text | `#EAEAEA` |
| Muted text | `#9CA3AF` |

## Stats and integrations

The README uses public, remote image services for typing text, stats, streaks, activity graph, skill icons, quote, and badges. Each URL includes `username=Ayushsingh3129`; replace that value. Spotify, Discord, and WakaTime are tasteful placeholders until you connect a provider of your choice.

## Preview

GitHub sanitizes SVGs in READMEs, so the artwork avoids scripts and external SVG dependencies. View `README.md` on GitHub after pushing to confirm remote widgets load. Local SVG files can be opened directly in a browser.
