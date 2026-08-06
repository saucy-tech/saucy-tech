<p align="center">
  <img src="img/saucy-tech-logo.png" alt="SaucyTech logo" height="120" />
    <a href="https://saucy.tech"><img src="img/saucy-tech-st-monogram.png" alt="Saucy Tech" height="80" /></a>
</p>

<h1 align="center">Brandon Sauceda</h1>

<p align="center">
  Engineering Manager | Product-minded software leader | Gov-tech, geospatial, and Bitcoin systems
</p>

<p align="center">
  <a href="https://saucy.tech">Website</a> |
  <a href="https://www.linkedin.com/in/saucytech/">LinkedIn</a> |
  <a href="https://github.com/saucy-tech">GitHub</a> |
  <a href="https://twitter.com/Saucy_Tech">X</a> |
  <a href="https://primal.net/p/nprofile1qqsvzs8gfntzjs2wg8670nrfy64h44zy69kc3r8rp5wd7kw6t6njsassf62c7">Nostr</a>
</p>

---

<h2 align="center">What I'm building</h2>

<p align="center">
  Three products get almost all of my building time.
</p>

<table>
  <tr>
    <td width="33%" align="center">
      <a href="https://morningportion.com">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="img/the-morning-portion-logo-dark.png" />
          <img src="img/the-morning-portion-logo.png" alt="The Morning Portion" height="160" />
        </picture>
      </a>
    </td>
    <td width="33%" align="center">
      <a href="https://train-every-day-demo.brandonsauceda.workers.dev/">
        <img src="img/train-every-day-logo.png" alt="Train Every Day" height="160" />
      </a>
    </td>
    <td width="33%" align="center">
      <a href="https://sunday-school-demo.brandonsauceda.workers.dev">
        <img src="img/sunday-school-logo.png" alt="Sunday School" height="160" />
      </a>
    </td>
  </tr>
  <tr>
    <td align="center"><em>The Word, before the day gets loud.</em></td>
    <td align="center"><em>What to do now, what to log, what to do next time.</em></td>
    <td align="center"><em>The whole quarter, in the room, with or without signal.</em></td>
  </tr>
  <tr>
    <td valign="top">
      Weekday scripture reflections rooted in the Sunday School lesson series. I write it and run the whole pipeline: an MDX publishing flow, an email broadcast to subscribers, and a podcast episode, out every weekday.
      <br /><br />
      Publishing is one gate rather than a checklist. Each devotion lands as a labelled pull request; merging it schedules the subscriber broadcast for 7:00 AM Eastern on the morning it belongs to, so the same review that approves the writing is what sends it.
      <br /><br />
      <code>Next.js 16</code> <code>React 19</code> <code>MDX</code> <code>Tailwind</code> <code>Cloudflare Workers</code> <code>GitHub Actions</code>
      <br /><br />
      <a href="https://morningportion.com"><strong>Read it at morningportion.com</strong></a>
    </td>
    <td valign="top">
      The workout logger I use on the gym floor every training day. It scores the three parts of the plan separately, each in the unit its own guideline uses: resistance days, cardio minutes, and mobility days. The targets sit above the WHO and CDC numbers rather than at them, and each bar carries a tick at the guideline minimum underneath, so a lighter week still shows whether it cleared the standard instead of just reading as a miss.
      <br /><br />
      Underneath that, weekly working sets are counted per muscle group against a 10&ndash;12 set band, with back and shoulders flagged as the V-taper priority and core held to a lower band because those bars count direct work only. Progression stays conservative on purpose: it names an exact next load only for machines whose real increment is documented, and effort is recorded only when I actually enter it.
      <br /><br />
      Local-first, so it keeps working with no signal and converges to Cloudflare KV through a commutative merge. No framework, no build step, no runtime dependencies. A read-only <code>/api/export</code> endpoint, authenticated by a Cloudflare Access service token and a verified Access JWT, hands the whole training record to my health dashboard and to the agents I analyze it with &mdash; which is why the logger never had to grow into a health app.
      <br /><br />
      <code>Vanilla JS</code> <code>PWA</code> <code>Cloudflare Workers</code> <code>KV</code> <code>Cloudflare Access</code> <code>JSON export API</code> <code>Offline-first</code>
      <br /><br />
      <a href="https://train-every-day-demo.brandonsauceda.workers.dev/"><strong>Open the demo</strong></a>
      <br />
      <sub>The live app holds my own training record and stays private. The demo is a separately sanitized build with fabricated data.</sub>
    </td>
    <td valign="top">
      The app I teach from on Sunday morning, on an iPad Mini in a classroom where the signal drops. A service worker precaches the menu and every lesson in the quarter, so the whole thing opens with no network at all. When that is not enough, any single lesson or an entire quarter exports as one self-contained HTML file that opens from the Files app with no service worker involved. That is the backup that cannot fail, and a room full of kids is not the place to find out the cache did.
      <br /><br />
      The menu, the lesson dates, and the badge on this Sunday are generated from the lesson files rather than hand-edited, so adding a lesson is dropping a file in a folder. Each quarter carries an optional <code>meta.json</code> for titles, scripture, and the date of the first Sunday; every other date is derived from that one. No framework and no build step beyond a dependency-free Node script, covered by a suite that runs on <code>node --test</code>.
      <br /><br />
      <code>Vanilla JS</code> <code>PWA</code> <code>Service worker</code> <code>Cloudflare Workers</code> <code>Cloudflare Access</code> <code>node --test</code> <code>Offline-first</code>
      <br /><br />
      <a href="https://sunday-school-demo.brandonsauceda.workers.dev"><strong>Open the demo</strong></a>
      <br />
      <sub>The lessons are written against paid curriculum, so the real deployment stays behind Cloudflare Access. The demo is the same app carrying three sample lessons written from scratch and none of the curriculum.</sub>
    </td>
  </tr>
</table>

---

## About

I lead small engineering teams and ship software that solves operational problems for real people. My background spans product engineering, government technology, GIS, and modern web development, with a consistent focus on clarity, execution, and systems that are easier to maintain than the ones they replace.

I am most effective where product, engineering, and delivery overlap: shaping scope, improving team throughput, modernizing legacy workflows, and helping teams move from ambiguity to working software.

## What I Do

- Lead engineering work across planning, delivery, and continuous improvement
- Build product direction with a bias toward user value, maintainability, and measurable outcomes
- Modernize legacy and public-sector systems without losing operational context
- Design and ship web products using TypeScript, React, Next.js, Node.js, and Python
- Work comfortably in GIS and mapping-heavy environments with ArcGIS Online and ArcGIS Pro
- Explore Bitcoin and Lightning-native products with an emphasis on practical utility and self-sovereign tools

## Current Focus

- Engineering management for small, high-trust teams
- Product delivery in gov-tech and operationally complex environments
- AI-assisted workflows that improve execution without adding noise
- Bitcoin, Lightning, and local-first software patterns

## Other Projects

The two products above get the bulk of my time. These are the rest.

| Project | Summary | Stack |
| --- | --- | --- |
| **[Field Manual](https://github.com/saucy-tech/field-manual)** | Open-source Claude Code skill that turns a project into one HTML file you use to drive the agent: decision sections, owner-badged task board, copy-prompt chips, status-sync loop | `Claude Code` `HTML` `AI agents` |
| **[Personal Site](https://github.com/saucy-tech/personal-site)** | Portfolio and writing platform with Lightning payments, MDX content, and a strong focus on accessibility and performance | `Next.js` `React` `TypeScript` `Tailwind` `MDX` |
| **[Lightning Tip Jar](https://github.com/saucy-tech/lntipjar)** | Bitcoin tipping experience built around Nostr Wallet Connect for straightforward Lightning payments | `Next.js` `React` `TypeScript` `NWC` `@getalby/sdk` |
| **[Work Time Visualizer](https://github.com/saucy-tech/work-time-visualizer-rust)** | Lightweight Windows taskbar widget showing daily and weekly work-time progress bars, built with native Win32 API | `Rust` `Win32 API` `Cargo` |

## Open Source Contributions

| Project | Contribution |
| --- | --- |
| **[hubble.md](https://github.com/bholmesdev/hubble.md)** | Three merged PRs to the notepad I use daily: Windows desktop build support ([#115](https://github.com/bholmesdev/hubble.md/pull/115)), system-follow dark mode ([#147](https://github.com/bholmesdev/hubble.md/pull/147)), and workspace-switcher cleanup ([#196](https://github.com/bholmesdev/hubble.md/pull/196)) |
| **[neon-orbit](https://github.com/ATLBitLab/neon-orbit)** | Power-ups: repair, Overdrive, and Shield pods ([#6](https://github.com/ATLBitLab/neon-orbit/pull/6)) &middot; [play it](https://neon-orbit-eight.vercel.app/) |
| **[Warp](https://github.com/warpdotdev/warp)** | Repo-picker fix for multi-repo workflows ([#9451](https://github.com/warpdotdev/warp/pull/9451)) |
| **[Abbot](https://github.com/ATLBitLab/abbot)** | Core features for the Bitcoin/Lightning bot for Nostr and Telegram |

## Recognition

Work I led has been recognized by Esri, GMIS, and NASCIO:

- **Esri Special Achievement in GIS (SAG) Award** — 2020
- **GMIS G2B Award, Government to Business** — GMIS International + Georgia Chapter, 2019
- **NASCIO State IT Recognition Award, ICT Innovations** — national finalist, 2019
- **Legends of Lightning Vol. 2 Hackathon** — Community & Education Award, 2023

Full list on my [portfolio](https://saucy.tech/portfolio).

## Core Tools

**Languages** &middot; `TypeScript` `JavaScript` `Python` `Swift` `Rust` `C#` `PowerShell` `SQL`

**Web** &middot; `React` `Next.js` `Astro` `Node.js` `MDX` `Tailwind CSS` `Three.js`

**Platform** &middot; `Cloudflare Workers` `KV` `D1` `Vercel` `Azure` `Docker`

**Data & GIS** &middot; `MS SQL` `PostgreSQL` `ArcGIS Pro` `ArcGIS Online`

**Bitcoin** &middot; `Lightning Network` `Nostr Wallet Connect` `Nostr`

**AI tooling** &middot; `Claude Code` `MCP servers` `agent workflows`

## How I Work

- Keep teams aligned on the problem, not just the ticket queue
- Prefer simple systems, explicit tradeoffs, and steady delivery
- Use documentation and tooling to reduce repeated coordination cost
- Care about product quality, developer experience, and operational reliability together

## Connect

I am interested in thoughtful conversations around engineering leadership, product development, civic technology, geospatial systems, and Bitcoin-native software.
