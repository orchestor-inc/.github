<p align="center">
  <a href="https://www.orchestor.io">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/orchestor-inc/.github/main/profile/assets/wordmark-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/orchestor-inc/.github/main/profile/assets/wordmark-light.svg">
      <img src="https://raw.githubusercontent.com/orchestor-inc/.github/main/profile/assets/wordmark-light.svg" alt="Orchestor" width="280">
    </picture>
  </a>
</p>

<h3 align="center">The AI creative platform.</h3>
<p align="center">Generate images, video and audio from the web app, the API, the CLI or your agent.</p>

<p align="center">
  <a href="https://www.orchestor.io">Website</a> ·
  <a href="https://www.orchestor.io/docs/en">Docs</a> ·
  <a href="https://www.orchestor.io/docs/en/mcp">MCP</a> ·
  <a href="https://www.orchestor.io/docs/en/cli">CLI</a> ·
  <a href="https://www.orchestor.io/changelog">Changelog</a> ·
  <a href="https://github.com/orchestor-inc/.github/blob/main/profile/README.ja.md">日本語</a>
</p>

---

Orchestor puts current image, video and speech models behind one account and one job API.

- **Images.** Generate from text and edit with reference images.
- **Video.** Text and image to video, plus editing, upscaling, reframing, background removal, lip sync, dubbing and captions.
- **Audio.** Text to speech and voice changing.
- **Canvas.** Connect nodes to build a repeatable creative workflow.
- **Marketing Studio.** Make ad images and video from templates or product assets.
- **API, CLI and MCP.** Run the same generation jobs from code, a terminal or an agent.

## Quick start

Connect your agent to the hosted MCP server. Claude Code:

```sh
claude mcp add --transport http orchestor https://mcp.orchestor.io/mcp
```

Open `/mcp`, sign in to Orchestor and pick a workspace. Then ask:

> List the available image models, then generate a red cube on a white background and give me the URL when the job finishes.

Codex, Cursor, OpenCode and other clients: [MCP setup](https://www.orchestor.io/docs/en/mcp).

Prefer the terminal? Install the CLI:

```sh
curl -fsSL https://orchestor.io/install | sh
orc auth login
orc creative image generate --model gpt-image-2 --prompt "A red cube on a white background" --wait
```

## Repositories

| Repository | What it is |
| :--- | :--- |
| [**cli**](https://github.com/orchestor-inc/cli) | `orc`, the Orchestor CLI. Releases, install script and issue tracker. |
| [**skills**](https://github.com/orchestor-inc/skills) | Agent skills for Orchestor, installable with `npx skills`. |
| [**orchestor-plugin**](https://github.com/orchestor-inc/orchestor-plugin) | Skills and the MCP connection packaged as one plugin for Claude Code and other coding agents. |

## Community

[Report a CLI bug](https://github.com/orchestor-inc/cli/issues) · [Contribute a skill](https://github.com/orchestor-inc/skills/pulls) · [Contact](https://www.orchestor.io/contact) · [Security](https://github.com/orchestor-inc/cli/blob/main/SECURITY.md)
