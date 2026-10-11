---
name: ui-resource-library
description: >-
  When building UI, landing pages, SaaS dashboards, or design systems and you need
  inspiration, component kits, motion libraries, icons, templates, AI design tools,
  or reading. Use to pick one best resource by need instead of searching from scratch.
  做落地页/SaaS/动效/图标/设计系统/AI 设计工具时，按需求从精选资源库里选组件与灵感。
---

# UI 资源库 / UI Resource Library

Agent-facing recipe for choosing UI resources. Catalog merged from public pages of [Designeer](https://designeer.xyz/) and [UINice](https://uinice.com/) (attribution only; destination links go to original projects). Full list: `catalog.md` / `resources.json` (~547 unique entries).

## When to use

- Shipping a **landing page**, **SaaS app shell**, **dashboard**, or **marketing site**
- Need **motion**, **icons**, **design tokens**, or a **full design system**
- Looking for **AI UI kits** / agent-friendly component registries
- Want **inspiration galleries** before inventing layout from scratch

## How to pick (by need)

1. **Clarify the job** in one line: landing hero, app chrome, motion polish, icon set, or full system.
2. **Match category** below. Prefer **one** primary kit; add a second only for a clear gap (e.g. icons + components).
3. **Prefer copy-own / open kits** (shadcn-style registries, MIT icons) unless the user asked for a paid polish kit.
4. **Check stack fit**: React+Tailwind vs Vue/Svelte vs pure CSS; skip kits that force the wrong stack.
5. **Open the destination URL**, skim docs/examples, then install or copy only what you need.
6. If the catalog is stale or missing a niche, re-check Designeer / UINice home pages, then fall back to known defaults (shadcn/ui, Lucide, Motion).

### Quick routing

| Need | Start here | Then consider |
| --- | --- | --- |
| Landing / marketing | Inspiration → Templates | Motion, Icons |
| SaaS / dashboard | Components → Design Systems | Templates, Icons |
| Micro-interactions | Motion | Components |
| Brand-consistent app | Design Systems | Interface / tokens |
| Iconography only | Icons | — |
| AI chat / agent UI | AI tools + Components (`AI Elements`, `assistant-ui`) | — |
| Visual craft learning | Reading | Inspiration |

## Practical steps

### Landing page
1. Skim **Inspiration** (Mobbin, Land-book, Saaspo) for structure — do not copy proprietary visuals.
2. Pick **one** template or block kit (Shadcnblocks, Tailwind Plus, Launch UI).
3. Add **one** motion source for hero/CTA only (Motion Primitives, React Bits) — avoid stacking three motion libraries.
4. Lock **icons** (Lucide or Heroicons) and stick to that set.

### SaaS product UI
1. Start from **shadcn/ui** or a design-system kit aligned with the stack.
2. Pull complex widgets from **Dice UI / Kibo UI / ReUI** only when shadcn lacks them (data grid, kanban, Gantt).
3. For billing/auth blocks, prefer kits that already wire Clerk/Polar-style patterns (Elements, Billing SDK) if the product needs them.

### Motion-heavy marketing
1. Choose **React Bits** or **Animata** for breadth, or **Transitions.dev** / **Motion Primitives** for restrained product motion.
2. For WebGL/shaders backgrounds, use **Paper Shaders** or **ShaderGradient** — one background effect max unless asked.

### Icons
1. Default **Lucide** (pairs with shadcn). Alternatives: Tabler (huge set), Phosphor (weights), 3dicons (marketing renders).
2. Animated icons: AnimateIcons / Heroicons Animated / Lucide Animated — only if static icons feel dead.

## Curated catalog (high-signal)

Full tables live in `catalog.md`. Below is a shortlist per category for fast picking.

### Design Galleries / Inspiration (78 in full catalog)

| Name | URL | Note |
| --- | --- | --- |
| Mobbin | https://mobbin.com/ | Real mobile and web product flows. |
| Awwwards | https://www.awwwards.com/ | Awards celebrating exceptional digital web craft. |
| Land-book | https://land-book.com/ | Landing pages organized by industry. |
| Saaspo | https://www.saaspo.com/ | Curated SaaS landing page designs. |
| Collect UI | https://collectui.com/ | Daily UI inspiration tagged by component. |
| Landingfolio | https://www.landingfolio.com/ | Extensive library of landing page designs. |
| SEESAW | https://www.seesaw.website/ | Design inspiration organized by page section. |
| Minimal Gallery | https://minimal.gallery/ | Showcase of minimal and restrained websites. |
| Dark Mode Design | https://www.darkmodedesign.com/ | Showcase celebrating dark-mode websites. |
| Flowbase | https://www.flowbase.co/ | Premium UI components and interaction patterns. |
| Supahero | https://supahero.io/ | Curated collection of website hero sections. |
| Hover States | https://hoverstat.es/ | Showcase of innovative interactive web design. |

### Components (165 in full catalog)

| Name | URL | Note |
| --- | --- | --- |
| shadcn/ui | https://ui.shadcn.com/ | Copy-in React components you own outright — the default starting point for most modern Tailwind apps. |
| React Bits | https://reactbits.dev/ | The largest open collection of animated React components — text, interactions, UI and backgrounds, each with live controls. |
| Kokonut UI | https://kokonutui.com/ | 100+ free components — cards, inputs, AI prompt boxes, buttons and text effects — with a polished marketing-site look. |
| Animate UI | https://animate-ui.com/ | Fully animated, shadcn-style components with smooth, restrained motion at the primitive level. |
| daisyUI | https://daisyui.com/ | A Tailwind plugin that adds semantic component classes and dozens of ready-made themes. |
| HeroUI | https://www.heroui.com/ | Polished React components on Tailwind and React Aria, with soft surfaces and a live theme builder. |
| Kibo UI | https://www.kibo-ui.com/ | A high-quality shadcn/ui registry known for complex components — Gantt charts, kanban boards, calendars. |
| Dice UI | https://diceui.com | The complex components shadcn lacks — data grid, kanban, cropper, angle slider, color picker and compare slider. |
| AI Elements | https://elements.ai-sdk.dev | Vercel's registry of AI interface components — conversations, reasoning, tool calls, code blocks and model pickers. |
| assistant-ui | https://www.assistant-ui.com | A React library for AI chat interfaces — ChatGPT-style threads, branching, attachments and tool calls, with any model. |
| coss ui | https://coss.com/ui | Cal.com's modern component library on Base UI, plus hundreds of ready-made component compositions. |
| Preline UI | https://preline.co/ | Tailwind components and polished full templates — dashboards, AI chat, SaaS sites — with dark mode built in. |

### Motion (51 in full catalog)

| Name | URL | Note |
| --- | --- | --- |
| Motion Primitives | https://motion-primitives.com/ | Restrained motion building blocks for product UIs — text effects, border trails, a magnifier and an infinite slider. |
| React Bits | https://reactbits.dev/ | The largest open collection of animated React components — text, interactions, UI and backgrounds, each with live controls. |
| Animata | https://animata.design | Animation and interaction snippets sorted by type — text, cards, backgrounds, buttons and hover effects. |
| Transitions | https://transitions.dev/ | Production-grade UI transitions from a design engineer, ready to copy as CSS or React. |
| Paper Shaders | https://shaders.paper.design/ | Zero-dependency shaders from the Paper design tool — mesh gradients, liquid metal, halftone and dithering, tunable live. |
| Motion Examples | https://motion.dev/examples | Motion's official gallery of 462 copyable animation snippets, filterable by React, JavaScript and Vue. |
| Cult UI | https://www.cult-ui.com/ | 154 free animated components with an Apple feel — dynamic island, Mac screen, folding cards — plus AI blocks. |
| Eldora UI | https://eldoraui.site/ | 150+ open-source animated components and templates in the vein of Magic UI. |
| Inspira UI | https://inspira-ui.com | The largest motion library for Vue and Nuxt, with many effects ported from Aceternity and Magic UI. |
| Osmo | https://www.osmo.supply | A members' library from award-winning motion designers — page transitions, scroll effects and easings in plain HTML, CSS and GSAP. |
| Hyperiux Vault | https://vault.hyperiux.com | Agency-grade interaction effects — scroll systems, cursor effects, text reveals, page transitions and loaders. |
| unlumen UI | https://ui.unlumen.com/ | Hand-polished shadcn motion primitives and components with measured, unshowy animation. |

### Design Systems (25 in full catalog)

| Name | URL | Note |
| --- | --- | --- |
| Primer Brand | https://primer.style/brand | GitHub's design system for marketing pages — the building blocks behind github.com's product pages. |
| Untitled UI React | https://www.untitledui.com/react | A large, carefully crafted React kit from the Untitled UI team — dashboards, settings and marketing pages included. |
| Achromatic | https://www.achromatic.dev | A paid SaaS starter with multi-tenancy, organizations, billing and dashboards, polished like a finished product. |
| Polar UI | https://polar.sh | The component package of Polar, the open-source billing platform — dark and minimal. |
| Midday UI | https://midday.ai | The UI package of Midday, the open-source business app — black and white, minimal, typographic. |
| Dub UI | https://dub.co | The component package behind Dub, the link attribution platform — clean, Linear-style SaaS interface. |
| Twenty UI | https://twenty.com | The UI package of Twenty, the open-source CRM — a Notion-like table-and-database interface. |
| BoardUI | https://www.boardui.com | A dashboard-first React design system with a dozen full templates — finance, project boards, AI chat. |
| Wedges | https://www.lemonsqueezy.com/wedges | Lemon Squeezy's own React components, built on Radix and Tailwind with its playful purple brand. |
| shadcn/ui | https://ui.shadcn.com/ | Copy-in React components you own outright — the default starting point for most modern Tailwind apps. |
| HeroUI | https://www.heroui.com/ | Polished React components on Tailwind and React Aria, with soft surfaces and a live theme builder. |
| Prompt Kit | https://www.prompt-kit.com/ | Building blocks for AI chat apps with a restrained, Vercel-like feel — including full chat blocks. |

### Templates (18 in full catalog)

| Name | URL | Note |
| --- | --- | --- |
| Tailwind Plus | https://tailwindcss.com/plus | Tailwind Labs' official paid kit: application UI, marketing blocks and full templates like the Catalyst app. |
| shadcnblocks | https://www.shadcnblocks.com/ | The largest library of shadcn blocks and marketing templates — 1,600+ blocks, for Next.js and Astro. |
| TailAdmin | https://tailadmin.com | Tailwind admin templates with e-commerce, analytics and CRM dashboards, in React, Vue and Angular versions. |
| MakerKit | https://makerkit.dev | A long-running SaaS kit in Supabase, Drizzle and Prisma flavors, with a free open-source Lite edition. |
| Efferd | https://efferd.com | Whole-section shadcn blocks — heroes, auth, app shells, dashboards and pricing — with restrained, precise typography. |
| Aura | https://aura.build/ | Meng To's AI landing-page builder with 700+ community templates, exportable as HTML, Tailwind or React. |
| Next Shadcn Dashboard Starter | https://shadcn-dashboard.kiranism.dev | A popular Next.js and shadcn dashboard starter with charts, a product table, kanban and forms. |
| Lexington Themes | https://lexingtonthemes.com | An independent shop of 60+ Astro and Tailwind themes with clean, editorial typography. |
| Studio Admin | https://studio-admin.arhamkhnz.com | A Next.js 16 and shadcn admin template with several dashboards, theme presets and switchable layouts. |
| Square UI | https://square.lndevui.com | 30+ full-page shadcn layouts from the maker of Circle — dashboards, notes, maps and bookmarks, each one clickable. |
| Launch UI | https://www.launchuicomponents.com | Dark, polished landing-page components in the Linear and Vercel vein, delivered through the shadcn registry. |
| Tailark | https://tailark.com/ | Premium-feeling marketing blocks and app pages for shadcn/ui projects. |

### Icons (40 in full catalog)

| Name | URL | Note |
| --- | --- | --- |
| Lucide | https://lucide.dev/ | shadcn's default icon set — 1,600+ line icons forked from Feather and still growing. |
| Heroicons | https://heroicons.com/ | Tailwind Labs' icon set — about 300 icons in outline, solid, mini and micro styles. |
| Tabler Icons | https://tabler.io/icons | 6,200+ free line icons on a 24 grid with a 2px stroke — one of the largest MIT icon sets. |
| Phosphor | https://phosphoricons.com/ | 9,000+ friendly icons, each in six weights from thin to fill and duotone. |
| Iconoir | https://iconoir.com/ | 1,600+ minimal line icons with thin strokes and a geometric feel, completely free. |
| 3dicons | https://3dicons.co | 1,500+ hand-made 3D icon renders, CC0 for commercial use, with Blender source files. |
| Remix Icon | https://remixicon.com/ | 3,000+ neutral icons, each in a matching line and fill pair. |
| Nucleo | https://nucleoapp.com | 40,000+ premium icons with a desktop app to manage them, all in one consistent, polished style. |
| AnimateIcons | https://animateicons.in | 1,170 open-source animated icons in Lucide and Hugeicons styles, triggered on hover. |
| Lobe Icons | https://icons.lobehub.com | Logos for AI models and brands — OpenAI, Claude, DeepSeek and hundreds more, in color, mono and with wordmarks. |
| Heroicons Animated | https://heroicons-animated.com/ | 316 Heroicons animated with Motion, with packages for React, Vue, Svelte and Solid. |
| Pixelarticons | https://pixelarticons.com | 5,400+ pixel-art icons on a 24 grid in four styles, freshly redesigned. |

### Interface / Tokens / Type / Color (23 in full catalog)

| Name | URL | Note |
| --- | --- | --- |
| Figma | https://figma.com/ | Collaborative interface design and prototyping platform. |
| design.dev | https://design.dev/ | AI-assisted design token and system editor. |
| Penpot | https://penpot.app/ | Open-source web design platform supporting SVG. |
| Fontshare | https://fontshare.com/ | High-quality professional fonts free for commercial use. |
| Framer | https://framer.com/ | Visual canvas designing and publishing websites. |
| make.design | https://make.design/ | AI generator turning prompts into polished designs. |
| Spline | https://spline.design/ | Browser-based 3D design software with physics. |
| Interface Craft | https://www.interfacecraft.dev/ | Articles exploring modern digital interface craftsmanship. |
| UI Labs | https://www.uilabs.dev/ | Laboratory deconstructing animated UI components. |
| UIWTF | https://uiw.tf/ | Showcase of experimental web interface patterns. |
| Lab01 | https://lab01.dev/ | Refined UI experiments from a studio. |
| UI Playbook | https://uiplaybook.dev/ | Guide to common UI component states. |

### AI Design Tools / Agents & MCP (35 in full catalog)

| Name | URL | Note |
| --- | --- | --- |
| skills | https://www.skills.sh/shadcn-labs/skills | Agent skills for shadcn registries and developer workflows. |
| Dray | https://www.drayhq.com/ | Unified desktop workspace managing coding agents. |
| Refero | https://styles.refero.design/ | Structured DESIGN.MD specifications for AI agents. |
| designmd.me | https://designmd.me/ | Generator creating machine-readable design specifications. |
| Open Design | https://open-design.ai/ | Standardized design systems formatted for agents. |
| designmd.supply | https://designmd.supply/ | DESIGN.MD templates to guide AI assistants. |
| getdesign.md | https://getdesign.md/ | Interactive generator producing AI design rules. |
| Hyperbrowser Design.md | https://design-md.hyperbrowser.ai/ | DESIGN.MD generator extracting rules from websites. |
| Aura | https://aura.build/ | Meng To's AI landing-page builder with 700+ community templates, exportable as HTML, Tailwind or React. |
| Neuform | https://neuform.ai/ | AI-assisted interface design producing clean code. |
| typeui.sh | https://typeui.sh/ | Command-line tool scaffolding typed UI components. |
| Webclaw | https://webclaw.io/ | Converts any webpage into structured markdown. |

### 3D / Shaders / Visuals (13 in full catalog)

| Name | URL | Note |
| --- | --- | --- |
| Paper Shaders | https://shaders.paper.design/ | Zero-dependency shaders from the Paper design tool — mesh gradients, liquid metal, halftone and dithering, tunable live. |
| Three.js | https://threejs.org/ | JavaScript 3D library rendering WebGL scenes. |
| React Three Fiber | https://r3f.docs.pmnd.rs/ | Declarative React renderer for Three.js scenes. |
| Drei | https://drei.docs.pmnd.rs/ | Helper components for React Three Fiber. |
| Blender | https://blender.org/ | Open-source 3D modeling and animation suite. |
| gltf.report | https://gltf.report/ | Web-based optimizer for 3D glTF files. |
| Poly Haven | https://polyhaven.com/ | Public asset library offering CC0 textures. |
| Book of Shaders | https://thebookofshaders.com/ | Interactive guide to mastering fragment shaders. |
| compute.toys | https://compute.toys/ | Sandbox for authoring WGSL compute shaders. |
| Shaderfrog | https://shaderfrog.com/ | Visual node-based editor for composing shaders. |
| shadercn | https://shadercn.run/ | Shader components for React, built on vgpu and TypeGPU. |
| OpenShaders | https://openshaders.com/ | Open-source shader collection for web projects. |

### Development / Deploy (29 in full catalog)

| Name | URL | Note |
| --- | --- | --- |
| Vite | https://vite.dev/ | Blazing fast frontend build and dev tool. |
| Vercel | https://vercel.com/ | Cloud platform for deploying Next.js applications. |
| Fly.io | https://fly.io/ | Runs Docker containers close to users. |
| Railway | https://railway.app/ | Simplified infrastructure platform for deploying databases. |
| Claude Code | https://claude.com/claude-code | Agentic coding tool inside your terminal. |
| Cursor | https://cursor.com/ | AI-first code editor for rapid development. |
| Zed | https://zed.dev/ | High-performance code editor built for low latency. |
| v0 | https://v0.app/ | Generative AI translating prompts into shadcn code. |
| Bolt.new | https://bolt.new/ | In-browser development sandbox for full-stack applications. |
| Biome | https://biomejs.dev/ | Fast Rust-based formatter and code linter. |
| Playwright | https://playwright.dev/ | Reliable browser automation and end-to-end testing. |
| BuilderTools | https://www.buildertools.sh/ | Focused developer tools for shipping software. |

### Utilities / Desktop / Capture (61 in full catalog)

| Name | URL | Note |
| --- | --- | --- |
| Raycast | https://raycast.com/ | Extendable desktop launcher replacing Spotlight. |
| CleanShot X | https://cleanshot.com/ | Ultimate screen capture and recording utility. |
| Excalidraw | https://excalidraw.com/ | Collaborative whiteboard with hand-drawn sketch aesthetic. |
| tldraw | https://tldraw.com/ | Infinite whiteboard library offering React SDK. |
| Linear | https://linear.app/ | Project management software setting speed standards. |
| SVGOMG | https://svgomg.net/ | Web GUI to optimize and clean SVG files. |
| RegExr | https://regexr.com/ | Interactive sandbox for testing regular expressions. |
| Squoosh | https://squoosh.app/ | Browser image compression with visual comparisons. |
| Fffuel | https://fffuel.co/ | Generative SVG textures, gradients, and patterns. |
| ui.camera | https://ui.camera/ | 3D mockups and scene staging for software. |
| Ray.so | https://ray.so/ | Turn code snippets into shareable screenshots. |
| Transform | https://transform.tools/ | Polyglot code converter for JSON and types. |

### Reading (33 in full catalog)

| Name | URL | Note |
| --- | --- | --- |
| Refactoring UI | https://refactoringui.com/ | Practical design guide for building interfaces. |
| Laws of UX | https://lawsofux.com/ | Psychological principles that influence interface usability. |
| Inclusive Components | https://inclusive-components.design/ | Pattern library teaching accessible component design. |
| Josh Comeau | https://joshwcomeau.com/ | Interactive tutorials breaking down CSS mechanics. |
| Animations.dev | https://www.animations.dev/ | Course on creating web animations that feel right. |
| Codrops | https://tympanus.net/codrops/ | Blog publishing creative frontend experiments and tutorials. |
| Practical Typography | https://practicaltypography.com/ | Essential book covering typographic rules and layout. |
| Design System Checklist | https://designsystemchecklist.com/ | Comprehensive checklist for production design systems. |
| web.dev | https://web.dev/ | Guidance on web performance and modern standards. |
| Design Books | https://design-books.com/ | Directory of essential design literature by discipline. |
| Learn Kernels | https://learn-kernels.com/ | Interactive guide exploring GPU kernel programming. |
| Learn UI | https://learn-ui.com/ | Video course teaching practical user interface design. |

## Sources & attribution

- [Designeer](https://designeer.xyz/) — design galleries, component libraries, motion, AI/MCP tools, reading, and more (`llms-full.txt` catalogue).
- [UINice](https://uinice.com/) — UI kits with real code: Motion / Components / Design Systems / Templates / Icons.
- Featured in community posts: [ianneo_ai on Designeer](https://x.com/ianneo_ai/status/2108732478043402320), [khorn62885776 on UINice](https://x.com/khorn62885776/status/2108747666964586842).

Do not scrape or reproduce proprietary site chrome, screenshots, or paid assets. Link out; credit the original project.

## Maintenance

- Refresh from Designeer `https://designeer.xyz/llms-full.txt` and UINice category pages when the user asks to update the catalog.
- Deduplicate by destination URL; keep both `sources` when the same tool appears on both sites.
