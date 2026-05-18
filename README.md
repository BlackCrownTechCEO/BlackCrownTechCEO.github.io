# BlackCrownTech — Portfolio Site

Source for **https://blackcrowntechceo.github.io**.

Astro 6 static site for the BlackCrownTech engineering studio. Dark royal-gold theme. Tailwind v4 + React 19 islands. Built on top of the [PowerAI Astro](https://github.com/sitepins/powerai-astro) template by Sitepins, heavily rebranded and trimmed for portfolio use.

## What's on the site

- **/** — hero, mission pillars, statistics, featured projects, why-us, FAQ, CTA
- **/projects** — full project showcase (eleven shipping initiatives)
- **/about** — studio, founder profile, mission & vision
- **/contact** — direct line to BlackCrownTech

## Featured projects

| Project | Status | What it is |
|---|---|---|
| Anti-Sloper | Live | Universal quality skill for AI coding agents — Claude Code, Codex, Cursor, Gemini CLI |
| VOID OMEGA Network | Beta | Backend-first autonomous secure-relay system with onion-capable transport |
| BlackCrownAgent | Beta | Offline AI coding agent — local LLM, DAG-orchestrated multi-agent, Next.js dashboard |
| VOID OMEGA Security Brain v6 | Beta | Security-intelligence platform with 4D rotating threat-correlation sphere |
| VOID.Chat | Live | Real-time encrypted messaging platform |
| Black Aether | Alpha | Encrypted social platform — no phone-number identity, no ad tracking |
| CrownForge Harness | Beta | Issue-driven coding-agent harness, Codex + Claude adapters |
| claude-code-mcp | Live | MCP server exposing Claude Code to other AI agents |
| JARVIS V.I | R&D | OSINT agent streamed to Meta Ray-Ban smart glasses |
| Void Bound | Alpha | Grimdark Godot 4 RPG with a persistent-graph world (Libram of Deeds) |
| OpenClaude (VOID OMEGA Network ed.) | Live | Multi-provider coding-agent CLI for 200+ LLMs |

## Local development

```bash
npm install
npm run dev
# http://localhost:4321
```

```bash
npm run build      # static output → ./dist
npm run preview    # serve ./dist
```

## Deployment

Pushes to `main` are built and published to GitHub Pages by `.github/workflows/deploy.yml` (Astro → `actions/upload-pages-artifact@v3` → `actions/deploy-pages@v4`).

Enable once in GitHub repo settings → **Pages** → **Build and deployment** → **Source: GitHub Actions**.

## Tech

- [Astro 6](https://astro.build) (static)
- [Tailwind v4](https://tailwindcss.com)
- React 19 islands (interactive widgets)
- [Motion](https://motion.dev) for scroll animations
- MDX, Sharp image pipeline, sitemap generator
- Inter typeface (Google Fonts via Astro Font)

## Credits

- Underlying template: [PowerAI Astro](https://github.com/sitepins/powerai-astro) — MIT licensed.
- Logo, content, and brand: BlackCrownTech.

## Contact

Jason Lechner — Founder & CEO
[jasonlechner.business@gmail.com](mailto:jasonlechner.business@gmail.com)
Wattens, Tirol — Austria
