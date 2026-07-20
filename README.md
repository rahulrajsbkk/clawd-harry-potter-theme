# Harry Potter — Clawd on Desk Theme

A chibi Harry Potter desk pet theme for [Clawd on Desk](https://github.com/rullerzhou-afk/clawd-on-desk): messy hair, round glasses, lightning scar, Gryffindor scarf — and a golden snitch that never leaves him alone.

He reacts in real time to your coding agent's activity — thinking, working, errors, permission prompts, and task completion — for any agent Clawd on Desk supports (Claude Code, Codex CLI, Copilot CLI, Cursor, Gemini CLI, and more).

All assets are pure CSS-animated SVG, no GIFs or external dependencies.

## Preview

<p align="center">
  <img src="assets/hp-idle.svg" alt="Harry Potter theme preview" width="220">
</p>

<table>
  <tr>
    <td align="center"><img src="assets/hp-idle.svg" width="120" alt="Idle"><br><sub>Idle</sub></td>
    <td align="center"><img src="assets/hp-thinking.svg" width="120" alt="Thinking"><br><sub>Thinking</sub></td>
    <td align="center"><img src="assets/hp-working.svg" width="120" alt="Working"><br><sub>Working</sub></td>
    <td align="center"><img src="assets/hp-juggling.svg" width="120" alt="Juggling"><br><sub>Juggling</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="assets/hp-attention.svg" width="120" alt="Attention"><br><sub>Attention</sub></td>
    <td align="center"><img src="assets/hp-notification.svg" width="120" alt="Notification"><br><sub>Notification</sub></td>
    <td align="center"><img src="assets/hp-sleeping.svg" width="120" alt="Sleeping"><br><sub>Sleeping</sub></td>
    <td align="center"><img src="assets/hp-error.svg" width="120" alt="Error"><br><sub>Error</sub></td>
  </tr>
</table>

## States

Clawd maps your agent's lifecycle events to animation states. Here's how Harry plays each one:

| State | When | Harry Potter behavior |
|-------|------|-----------------------|
| idle | No agent activity | Eye tracking (follows your cursor), breathing, scarf sway, golden snitch buzzing around |
| thinking | Prompt submitted | Head tilt, gold sparkles of a spell forming |
| working | Agent using tools | Writing with a quill on parchment |
| juggling | Subagent running | Wingardium Leviosa — levitating three potion bottles |
| sweeping | Context compaction | Sweeping up with the Nimbus 2000 |
| carrying | Worktree created | Hauling a stack of library books |
| error | Tool failure | Spell backfire — smoke, sparks, soot on cheek |
| attention | Task complete | Caught the snitch! |
| notification | Permission request / alert | Hedwig delivers a wax-sealed letter |
| sleeping | 60s of no mouse activity | Yawn → doze → collapse → sleep (glasses folded on the floor) → wake on mouse move |

### Working tiers

`working` scales with the number of concurrent agent sessions:

- **1 session** — writing with a quill on parchment
- **2 sessions** — Wingardium Leviosa, levitating three potion bottles
- **3+ sessions** — shelving a stack of spellbooks

## Reactions

- **drag** — flailing, scarf flying
- **click / double-click** — Lumos! wand sparks
- **poking repeatedly** — annoyed, arms crossed

## Capabilities

- **Eye tracking** — Harry's eyes follow your cursor while idle
- **Full sleep sequence** — yawn → doze → collapse → sleep → wake
- **Click & drag reactions** — see above
- Mini mode is not supported

In Clawd's `Settings… → Theme`, the capability badges on each theme card confirm what it supports.

## Install with Claude Code (copy-paste prompt)

Paste this into [Claude Code](https://claude.com/claude-code) (or any coding agent) and it will install the theme for you:

```text
Install the Clawd on Desk theme from https://github.com/rahulrajsbkk/clawd-harry-potter-theme
Clone the repo and copy theme.json and the assets/ folder into my Clawd on Desk
user themes directory as "harry-potter":
  - macOS:   ~/Library/Application Support/clawd-on-desk/themes/harry-potter
  - Windows: %APPDATA%\clawd-on-desk\themes\harry-potter
  - Linux:   ~/.config/clawd-on-desk/themes/harry-potter
Don't touch the app's built-in themes. When done, remind me to restart
Clawd on Desk and select "Harry Potter" under Settings → Theme.
```

## Install manually

1. Copy this folder to your Clawd user themes directory as `harry-potter/` (the folder holding `theme.json` must sit directly under `themes/` — no extra nesting):
   - **macOS**: `~/Library/Application Support/clawd-on-desk/themes/harry-potter/`
   - **Windows**: `%APPDATA%\clawd-on-desk\themes\harry-potter\`
   - **Linux**: `~/.config/clawd-on-desk/themes/harry-potter/`
2. Restart Clawd on Desk, then `Settings… → Theme → **Harry Potter**`.

Don't reuse a built-in theme id (`clawd`, `calico`, `cloudling`) — built-in themes take priority over user themes with the same id.

## Credits

Unofficial fan-made theme. Harry Potter belongs to its respective rights holders. Built on the [Clawd on Desk](https://github.com/rullerzhou-afk/clawd-on-desk) theme system, referencing the built-in Clawd, Calico, and Cloudling themes. The Clawd character belongs to Anthropic; Clawd on Desk is itself an unofficial fan project.
