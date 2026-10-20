# Tri Adi S. (Darren Lieu): CEO, Darren Labs · AI architect in progress

I'm Tri Adi S. I work as Darren Lieu. I run **Darren Labs**, an agentic AI studio in Indonesia, and I'm on the path to becoming an AI architect.

Most of my work starts from one annoyance: engineers losing hours to repetitive power-system CAD and calculation work. So I build tools that capture, read, decide, and act, and I publish every app the studio finishes. I set the direction and the priorities. A fleet of AI agents does the execution, and nothing ships until it has been checked working.

**Company site:** [Darren Labs](https://darthsandd.github.io/darren-labs-site/) · **LinkedIn:** [Darren Labs](https://www.linkedin.com/company/darren-labs/) · **Daily builds:** [@darren.lin_ai](https://www.instagram.com/darren.lin_ai)

---

## Darren Labs

![Darren Labs banner](https://darthsandd.github.io/darren-labs-site/docs/assets/darren-labs-banner.png)

The studio site itself is a product: an interactive 3D office you can walk through in the browser, built with real licensed 3D models, plus a working contact form. Everything below shipped from this studio.

---

## Flagships

### [Omni Eyes](https://darthsandd.github.io/omni-eyes-view/) · [source](https://github.com/DarthSandD/omni-eyes-view)

<img src="https://darthsandd.github.io/omni-eyes-view/logo.svg" width="72" alt="Omni Eyes logo">

A real-time earth-intelligence globe built on Cesium. Live aircraft, vessels, satellites, and fire data on one map, extended from the open-source God's Eye viewer with live public CCTV cameras from Indonesian cities, streamed as HLS inside the globe.

`JavaScript` · `Cesium` · `Vite` · `HLS.js` · `Cloudflare Workers`

### [VoltWorks Power](https://darthsandd.github.io/voltworks-power/) · [source](https://github.com/DarthSandD/voltworks-power)

![VoltWorks Power cover](https://darthsandd.github.io/voltworks-power/cover.png)

The electrical engineer's daily driver, in a browser tab. Voltage drop, cable sizing, transformer sizing, fault levels, and arc-flash to IEEE 1584, plus interactive single-line diagrams that save your work. No install, no backend, works offline.

`HTML` · `JavaScript`

### [MEP Suits](https://darthsandd.github.io/mep-suits/) · [source](https://github.com/DarthSandD/mep-suits)

![MEP Suits banner](https://darthsandd.github.io/mep-suits/docs/assets/mep-suits-banner.png)

Eight building-services calculators (HVAC, duct, electrical, plumbing, and more) with live recalculation as you type, and a 3D system viewer with real equipment models where you can switch components and watch the system change. One page, no signup, works on site.

`HTML` · `JavaScript`

---

## More Darren Labs products

### Saku: QRIS finance app (private beta)

![Saku banner](https://raw.githubusercontent.com/DarthSandD/DarthSandD/main/assets/saku-banner.png)

A salary-first finance app for Android, in Bahasa Indonesia. Scan a QRIS code to check and record a payment before you make it, split your salary into buckets that must add up, and turn on Strict Mode when a bucket goes over its limit. Offline first, with optional Supabase sync. Handoff to your bank or wallet app is always a tap you confirm, never automatic.

`Flutter` · `Dart` · `Supabase` · `Hive`

### [Hermes Switzerland](https://switzerland-backend.onrender.com/)

![Hermes Switzerland banner](https://raw.githubusercontent.com/DarthSandD/DarthSandD/main/assets/hermes-switzerland-banner.png)

A virtual company you can open in the browser: buildings, rooms, and AI workers sending heartbeats into an interactive 3D scene, backed by a FastAPI service on Render. It started as an experiment in running a company made of agents, and it is still the best demo of how Darren Labs works inside.

`Python` · `FastAPI` · `Three.js` · `Render`

### [Agent Org Fleet](https://github.com/DarthSandD/agent-org-fleet)

![Agent org chart](https://raw.githubusercontent.com/DarthSandD/agent-org-fleet/main/docs/assets/org-chart.png)

The org chart behind the studio: 115 titled agent roles on a seniority ladder, each with its own written instructions, matched skills, and a reporting line. Public, so anyone can study how a one-person company staffs itself with agents.

### UT Tuton Generator: [live tool](https://ut-tuton-generator.onrender.com/)

![UT Tuton Generator banner](https://raw.githubusercontent.com/DarthSandD/DarthSandD/main/assets/ut-tuton-banner.png)

A small formatter for Universitas Terbuka students: paste a tuton discussion or assignment draft, get it back clean and ready to post. Built because I am one of those students.

`Python` · `Render`

### [JARVIS](https://github.com/DarthSandD/jarvis-apk)

![JARVIS banner](https://raw.githubusercontent.com/DarthSandD/DarthSandD/main/assets/jarvis-banner.png)

A voice-first AI assistant for Android with a HUD-style interface and pluggable AI providers, from cloud APIs to a local gateway. Built for my own phone first.

`Kotlin` · `Material 3`

### [Signal Desk](https://darthsandd.github.io/signal-desk/) · [source](https://github.com/DarthSandD/signal-desk)

<img src="https://darthsandd.github.io/signal-desk/icon-512.png" width="72" alt="Signal Desk icon">

Live forex, crypto, and stock signals with plain BUY/SELL calls instead of chart archaeology. An installable PWA with a dark-first UI.

`HTML` · `JavaScript`

---

## How I think about systems

### [AI Architecture Patterns](https://github.com/DarthSandD/ai-architecture-patterns)

![Context engineering diagram](https://raw.githubusercontent.com/DarthSandD/ai-architecture-patterns/master/assets/context-engineering-diagram.png)

A visual library for how AI systems fit together: diagrams, tradeoffs, runnable demos, and the part most write-ups skip, when not to use each pattern. This is my study notebook for becoming an AI architect, kept in public.

---

## Free reference guides

### [AutoCAD Hotkey and Command Guide](https://darthsandd.github.io/autocad-guide/) · [source](https://github.com/DarthSandD/autocad-guide)

![AutoCAD guide slide](https://raw.githubusercontent.com/DarthSandD/autocad-guide/main/instagram/_stage/slide-1.png)

90+ commands across 8 categories. Search by command, hotkey, or plain intent, and each clip starts at the exact second the command is explained.

### [Autodesk Inventor Complete Guide](https://darthsandd.github.io/inventor-guide/) · [source](https://github.com/DarthSandD/inventor-guide)

![Inventor guide screenshot](https://darthsandd.github.io/inventor-guide/linkedin/shots/crop-desktop.png)

Inventor from first sketch to assemblies, sheet metal, and iLogic, in one searchable page. Every topic is tagged by level and carries a tutorial clip.

---

## How I work

- I decide what gets built and in what order. Agents write, test, and check the work. I review the result before it goes out.
- If something cannot be verified, it does not get claimed. A green build and a screenshot beat a confident sentence.
- I prefer free and open infrastructure when it genuinely does the job. Low running cost is a design choice: it keeps every product alive without a funding round.
- Code goes to GitHub. Live state gets backed up outside any single machine.

## Stack I actually use

`Python` · `JavaScript / TypeScript` · `Flutter / Dart` · `Kotlin` · `HTML / CSS`
`FastAPI` · `Three.js` · `Cesium` · `Supabase` · `Cloudflare Workers` · `GitHub Pages` · `Render`
`AI agent orchestration` · `LLM APIs` · `HLS streaming`

## Currently

- Shipping Saku v2.3.x and hardening it on a real phone (mine)
- Growing Darren Labs from a one-person studio with an agent fleet into a real company
- Studying AI architecture in public, one pattern at a time

## Contact

**GitHub** · [@DarthSandD](https://github.com/DarthSandD)
**Company** · [Darren Labs on LinkedIn](https://www.linkedin.com/company/darren-labs/)
**LinkedIn** · [Tri Adi S.](https://www.linkedin.com/in/tri-adi-setiawan-41b9131b5)
**Instagram** · [@darren.lin_ai](https://www.instagram.com/darren.lin_ai)
**Email** · [darren111@gmail.com](mailto:darren111@gmail.com)

Open to remote AI automation roles and collaborations, worldwide.
