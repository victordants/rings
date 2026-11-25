# Drawing, cut-plan (plano de corte / nesting) and slab-layout tools + open-source marmoraria projects

Research date: 2026-11-25. **Method caveat:** in this session the network blocked direct fetches of wayssoft.com.br, stonify.com.br, stonify.io, slabwise.com, slabsmith (azurewebsites) and stonespecialist.com. Facts about those products come from search-engine snippets of their own pages, which are less reliable than reading the full page. They are marked **(snippet)**. GitHub repos were cloned and read directly, so those facts are verified. "Unverified" means only one vendor page or snippet supports the claim.

**Naming warning:** two products are called "Stonify". **stonify.com.br** is a Brazilian tool with a free 3D designer and cut plan. **stonify.io** is a US ERP for stone shops, founded in 2023. They are different products.

---

## 1. Value proposition, target customer, platforms

### Takeaway
The Brazilian tools are cheap or free and sit at opposite ends. MarmoDraw (R$69/month, 1 PC) is a desktop CAD and cut-plan tool aimed at shops with a CNC. Stonify.com.br is free, runs in the browser on a phone, and offers a 3D designer plus cut plan, but no pricing. The US tools (Slabsmith, Laser Products, SlabWise, CounterGo) target mid-to-large shops with saws, lasers and photo rigs, at US$100 to 8,000+. None is built for a one-person marmoraria quoting from a phone with a built-in price.

### Cited Findings
**MarmoDraw (Wayssoft, Brazil)**
- Described as a "CAD 2D para marmorarias" with DXF export for CNC, m² calculation and cut plan **(snippet)** — [Wayssoft MarmoDraw](https://www.wayssoft.com.br/marmodraw/)
- Draws countertops in 2D and nests pieces automatically on the slab to improve yield, for marble, granite, quartz and porcelain **(snippet)** — [Wayssoft MarmoDraw](https://www.wayssoft.com.br/marmodraw/)
- Licence is "para 1 computador", which points to a desktop (Windows) program and not a web or mobile app **(snippet; Windows-only is my inference)** — [Wayssoft MarmoDraw](https://www.wayssoft.com.br/marmodraw/)
- Wayssoft's other main products are workshop software (oficina mecânica OS, stock, NF-e), so MarmoDraw is a side line of a generalist SMB software house — [Wayssoft](https://www.wayssoft.com.br/); [Sistema oficina](https://www.wayssoft.com.br/ordem-servico-oficina-mecanica.html)

**Stonify.com.br (Brazil)**
- Free to start, priced at "R$0"; runs in the browser on computer, tablet or phone with no install **(snippet)** — [Stonify.com.br](https://stonify.com.br/); [Software para marmoraria](https://stonify.com.br/software-para-marmoraria/)
- 3D designer for sinks, countertops, islands, tables and stairs, shown with real slab photos and 100+ ready templates **(snippet)** — [Software para marmoraria](https://stonify.com.br/software-para-marmoraria/)
- Free cut plan with PDF export that opens on a phone **(snippet)** — [Plano de corte de chapas](https://stonify.com.br/plano-de-corte-de-chapas/)
- **It does not price.** It outputs a piece list with measurements, and the site says it does not replace the shop's price table: the shop applies its own m² price and labour **(snippet)** — [Stonify.com.br](https://stonify.com.br/); [Modelo de orçamento](https://stonify.com.br/modelo-de-orcamento-para-marmoraria/)
- Uses SEO content to attract shops: a free Excel/Sheets quote template and articles such as "Quanto custa uma bancada de granito" — [Modelo de orçamento](https://stonify.com.br/modelo-de-orcamento-para-marmoraria/); [Quanto custa bancada](https://stonify.com.br/quanto-custa-bancada-de-granito/)

**Stonify.io (US, different company)**
- All-in-one ERP for stone fabricators: leads, quotes, drawings, slab inventory, production, installation and accounting. Founded in 2023 — [Capterra](https://www.capterra.com/p/10049101/Stonify/); [Stonify.io blog](https://www.stonify.io/blog/what-is-stonify-the-all-in-one-erp-for-stone-fabrication-shops)

**Slabsmith (Northwood Designs, US)**
- Desktop suite for slab photography, inventory and layout: Slab Maker, Perfect Match, Slab Manager, plus a scanner interface — [Slabsmith pricing page (azurewebsites, may not be official)](https://slabsmith.azurewebsites.net/slabsmithpricing)
- Vendor claims ROI in 6 months or less (vendor claim, not a review) — [SourceForge](https://sourceforge.net/software/compare/Slabcloud-vs-Slabsmith)
- Moraware itself says its CounterGo "isn't as powerful as SlabSmith" — [Moraware CounterGo](https://www.moraware.com/countergo)

**Laser Products Industries ("Prodigi")**
- **I found no product named "Prodigi".** Two searches returned only LPI's templating line:
  - LT-2D3D Laser Templator, TemplatePro (3D templating that works only with LPI lasers), and LT3 Raptor (templating plus a cloud management hub) — [Stone World TemplatePro](https://www.stoneworld.com/articles/88396-templatepro-by-laser-products-industries); [Stone World LT3 Raptor](https://stoneworld.com/articles/93725-lt3-raptor-laser-products-industries)
  - LPI says it has sold more than 8,000 digital laser templating systems. Its software avoids "confusing CAD symbols", converts output to the specs of various CNC brands, and integrates with Slabsmith and Moraware — [Stone World search summary](https://www.stoneworld.com/articles/91535-technology-update-lt-2d3d-laser-templator)
- Target: shops that template on site with a laser, with hardware plus software, and no price published.

**SlabWise (US)**
- Positioned as "Nesting, Quoting, and DXF Tools for Countertop Fabricators" — [SlabWise](https://slabwise.com/)
- Takes DXF templates as input. Outputs a CNC file (DXF or G-code), a visual layout, yield %, a remnant map and a cut sequence **(snippet)** — [SlabWise AI nesting guide](https://slabwise.com/guide/ai-slab-nesting)
- The site is a large set of SEO and comparison pages ("vs Moraware", "vs Fab-Pak" and others), so it reads as content marketing — [SlabWise vs Moraware](https://slabwise.com/compare/slabwise-vs-moraware)

**Moraware CounterGo (US, a useful reference for drawing UX)**
- Drawing, layout and estimating tool. You draw with a fingertip on an iPad or with a mouse; ft² and edge linear feet are computed as you draw. Pieces can be laid on slabs, rotated and seamed to estimate slab count, with slab images — [Moraware CounterGo](https://www.moraware.com/countergo); [CounterGo onboarding: Slab layouts](https://www.moraware.com/onboarding/countergo-onboarding-slab-layouts/)

**Generic cut-plan apps used in Brazil (the low end)**
- CutSoft: web, for marcenarias and marmorarias, unlimited cut plans for R$97.90/month — [CutSoft](https://cutsoft.com.br/)
- PlanoCorte: phone, tablet and PC; free plan limited to 2 slabs and 10 pieces — [PlanoCorte](https://planosdecorte.com.br/)
- MaxCut: free iPhone and Android app, works offline, no signup — [MaxCut](https://www.maxcut.app/en)
- MarmoCut: sold on Hotmart as a course on cut plans, DXF and CNC prep — [Hotmart MarmoCut](https://hotmart.com/pt-br/marketplace/produtos/marmocut-software/O105724755O)
- Siemens DDX EasyStone: industrial CAD/CAM with nesting for stone CNC (high end) — [Siemens](https://www.siemens.com/pt-br/products/ddx-easystone/)

### Inferences
- No product combines "draw on a phone, auto cut plan, priced quote, WhatsApp PDF" for a solo Brazilian shop. Stonify.com.br draws but does not price. MarmoDraw is desktop CAD for CNC. The quote-only tools do not draw. The Marmofácil prototype is the only one trying all of it (see section 4).
- Stonify.com.br is the most dangerous free competitor for a solo shop, because it costs nothing and works in a phone browser. Its gap is pricing, profit and the commercial PDF.

### Gaps
- No paid-plan details, free-tier limits or company info for Stonify.com.br. The site was blocked and snippets show only "free to start".
- Platform details for MarmoDraw (Windows version, offline use) are not confirmed.
- "Prodigi" could not be identified. It may be a misremembered name, perhaps Prodim's Proliner (a different company). This is speculation.

---

## 2. Features matrix (drawing, nesting, waste, DXF/CNC, photos, vein matching, quote link, PDF)

### Takeaway
Auto-nesting and DXF are now table stakes for CNC shops (MarmoDraw, SlabWise, Slabsmith). Slab photos and vein matching are high-end features (Slabsmith, SlabWise, CounterGo images). For a quoting app, the feature that changes the price is a slab-count estimate; true nesting and DXF matter only to shops with CNC saws.

### Cited Findings
| Feature | MarmoDraw | Stonify.com.br | Slabsmith | LPI | SlabWise | CounterGo |
|---|---|---|---|---|---|---|
| Piece drawing | 2D CAD, imports DXF and DWG, 25 edge profiles **(snippet)** [src](https://www.wayssoft.com.br/marmodraw/) | 3D designer, 100+ templates incl. stairs **(snippet)** [src](https://stonify.com.br/software-para-marmoraria/) | Takes drawings from templating/CAD [src](https://slabwise.com/guides/how-to-do-countertop-layout-on-a-slab-using-slabsmith) | Laser-measured 2D/3D [src](https://www.stoneworld.com/articles/88396-templatepro-by-laser-products-industries) | Input is DXF templates **(snippet)** [src](https://slabwise.com/guide/ai-slab-nesting) | Finger/mouse "drag and draw" [src](https://www.moraware.com/countergo) |
| Auto nesting | Yes **(snippet)** [src](https://www.wayssoft.com.br/marmodraw/) | Cut plan, free **(snippet)** [src](https://stonify.com.br/plano-de-corte-de-chapas/) | Manual/assisted layout on photo [src](https://slabsmith.azurewebsites.net/slabsmithpricing) | Via Slabsmith/Moraware | "AI nesting" (claims 10 to 15% better yield, unverified) [src](https://slabwise.com/best/slab-nesting-software) | Manual: rotate and seam pieces on slab [src](https://www.moraware.com/onboarding/countergo-onboarding-slab-layouts/) |
| Remnants/waste | not found | not found | Slab Manager inventory | n/a | Remnant map [src](https://slabwise.com/guide/ai-slab-nesting) | shows unused slab |
| DXF/CNC | DXF R12 with layers per operation **(snippet)** [src](https://www.wayssoft.com.br/marmodraw/) | not found (PDF only) | yes (industry standard) | CNC-brand output [src](https://www.stoneworld.com/articles/91535-technology-update-lt-2d3d-laser-templator) | DXF or G-code [src](https://slabwise.com/guide/ai-slab-nesting) | no |
| Slab photos/vein | not found | real slab photos in 3D | core feature (Perfect Match) | n/a | optional photo for vein matching at seams; mark areas to avoid [src](https://slabwise.com/for/natural-stone) | slab images on drawing [src](https://www.moraware.com/onboarding/countergo-onboarding-slab-layouts/) |
| Priced quote | not found | **No**, only a piece list [src](https://stonify.com.br/) | no | no | "Quoting" claimed [src](https://slabwise.com/) | Yes, price lists [src](https://www.moraware.com/countergo) |
| PDF | not found | Yes (cut plan) | n/a | n/a | n/a | Yes |

- SlabWise's own pages contradict each other on vein matching: one comparison calls its layout "data-driven, not photo-based" — [SlabWise compare pages](https://slabwise.com/compare/slabwise-vs-stonegrid)
- In CounterGo, when material is priced per ft², slab count does not change the price; layout is only for viewing — [CounterGo onboarding](https://www.moraware.com/onboarding/countergo-onboarding-slab-layouts/)

### Inferences
- CounterGo's split between "price per m²" and "price per whole slab" matches Brazilian practice. Shops often charge per m² with a loss %, or by the whole slab for exotic stone. That choice should exist from day one. Marmofácil's `calc.js` already has it (`P.charge==='m2'` vs `priceSlab`).
- DXF and vein matching are irrelevant to a one-person shop without CNC. Leave them for later phases.

### Gaps
- No direct confirmation of whether MarmoDraw links to a quote or PDF.
- No independent tests of nesting quality for any product.

---

## 3. Pricing and plans (exact numbers)

### Takeaway
Brazil: MarmoDraw R$69/month (1 PC, 30-day trial, no card); Stonify.com.br free; CutSoft R$97.90/month. US: CounterGo US$100/user/month, SlabWise about US$99 to 799/month (its own pages conflict), Slabsmith US$3,500 to 8,000 per licence.

### Cited Findings
- **MarmoDraw:** single plan at R$69.00/month, no lock-in, no per-user fee, no extra modules, licence for 1 computer, 30-day trial with no credit card **(snippet)** — [Wayssoft MarmoDraw](https://www.wayssoft.com.br/marmodraw/)
- **Stonify.com.br:** "R$0", free to start; paid tiers unknown **(snippet)** — [Stonify.com.br](https://stonify.com.br/)
- **Stonify.io (US):** unclear. One directory's structured data says US$500, another says "from $99"; neither is confirmed — [SoftwareAdvice UK](https://www.softwareadvice.co.uk/software/556653/Stonify); [SourceForge](https://sourceforge.net/software/product/Stonify/)
- **Slabsmith:** each additional Essentials licence (Slab Maker, Perfect Match, Slab Manager) US$8,000; Slab Scanner Interface US$2,500; reduced-function Layout US$3,500; Slabsmith Lite US$8,000; hardware not included. **(snippet, from a page on an azurewebsites domain that may not be official)** — [Slabsmith pricing](https://slabsmith.azurewebsites.net/slabsmithpricing). A SlabWise guide gives about US$100 to 200 (likely per month or per module; conflicts with the above) — [SlabWise guide](https://slabwise.com/guides/what-software-do-countertop-fabricators-use-for-quoting)
- **SlabWise:** its pages conflict.
  - Comparison pages say Standard US$199/month and Enterprise US$349/month — [SlabWise vs Quote Countertops](https://slabwise.com/compare/slabwise-vs-quote-countertops-pricing)
  - The pricing page shows Starter US$99/month and the homepage shows a US$299/month tier with the nesting optimizer **(snippet)** — [SlabWise pricing](https://slabwise.com/pricing)
  - Another page cites US$799/month Enterprise **(snippet)** — [SlabWise](https://slabwise.com/)
- **CounterGo:** US$100/month per user — [Moraware CounterGo](https://www.moraware.com/countergo)
- **LPI:** no published prices; sold as hardware plus software with a renewable one-year warranty — [Stone World](https://www.stoneworld.com/articles/91535-technology-update-lt-2d3d-laser-templator)
- **iCounterSoft:** about US$200/month; **SlabOS:** US$1,250 flat/month — [SlabWise vs iCounterSoft](https://slabwise.com/compare/slabwise-vs-icountersoft-for-commercial); [Capterra SlabOS](https://www.capterra.com/p/10047460/SlabOS/)
- **CutSoft (BR):** R$97.90/month for unlimited cut plans — [CutSoft](https://cutsoft.com.br/)

### Inferences
- Brazilian price anchors for a solo shop are R$0 (Stonify.com.br, free generic apps) to about R$70 to 100/month (MarmoDraw, CutSoft). A quoting app priced well above R$100/month would need clear profit features, such as margin, closed-quote snapshot and WhatsApp PDF, that these do not have.

### Gaps
- No exact paid tiers for Stonify.com.br. No confirmed official Slabsmith prices.

---

## 4. User reviews / feedback

### Takeaway
Independent reviews are almost absent for every product. Directory sites (Slashdot, SourceForge) show 0 ratings for Slabsmith and Stonify. Available "reviews" are vendor content, such as SlabWise's self-review pages.

### Cited Findings
- Slabsmith and Stonify show 0 user ratings on Slashdot and SourceForge comparison pages — [Slashdot Slabsmith vs Stonify](https://slashdot.org/software/comparison/Slabsmith-vs-Stonify/)
- SlabOS has only 4 reviews on Capterra — [Capterra SlabOS](https://www.capterra.com/p/10047460/SlabOS/)
- SlabWise hosts its own "SlabWise Review 2026" (self-published, not independent) — [SlabWise review](https://slabwise.com/reviews/slabwise-review)
- LPI software is called "one of the most user-friendly digital templating software in the industry" in trade press — [Stone World](https://www.stoneworld.com/articles/91535-technology-update-lt-2d3d-laser-templator)

### Inferences
- The niche is small and word-of-mouth driven. Validation has to come from direct interviews with marmoristas, not online reviews.

### Gaps
- No reviews found for MarmoDraw or Stonify.com.br (Reclame Aqui, Google Play and YouTube comments were not reachable or not found).

---

## 5. GitHub / open-source projects

### Takeaway
There is no mature open-source marmoraria tool. **Danielhsantos1/Marmofacil** is the most relevant: an active (Nov 2026), tested, phone-first PWA with pure calculation functions you can study, but **no licence**, so the code cannot legally be reused. Only its ideas can be copied. **duducoBS/orcamentos-marmoraria** is a simple quote-sheet PDF generator with no geometry. The rest are mostly marmoraria landing pages.

### Cited Findings (verified by cloning and reading; GitHub API metadata was blocked, so stars and licence come from GitHub search and the repo page)

**Danielhsantos1/Marmofacil** — [repo](https://github.com/Danielhsantos1/Marmofacil); live at danielhsantos1.github.io/Marmofacil
- **Activity:** first commit 2026-10-19, latest 2026-11-21 (v42). 52 commits, 0 stars. Built mostly with AI coding agents: it has `CLAUDE.md`, `AGENTS.md` and `.claude/agents/` (3d-editor, geometry-pricing-qa, backend-security and others)
- **Stack:** one large `index.html` (1,657 lines, about 147 KB) in vanilla JS with no build. `calc.js` holds pure functions; `model3d.js` and `viewer3d.js` use Three.js (bundled in vendor/); jsPDF for PDFs; a service worker for offline; GitHub Pages hosting; `node --test` with `tests/golden.json` price baselines.
- **Data:** localStorage key `pedrafacil.v1`; no login or cloud. Photos are stored as base64 in localStorage, with a roughly 5 MB limit risk.
- **License:** none found (no LICENSE file; README does not state one). By default all rights are reserved.
- **Features:**
  - Parametric piece types: reta, L, U, ilha, lavatório, escada, nicho, livre
  - Saia and rodabanca as linear metres
  - Cutouts for sink and cooktop, charged as services
  - Cut plan with a "shelf" heuristic: kerf 0.4 cm, splits oversize pieces into seams
  - Pricing with margin and tax on the selling price
  - Closed-quote snapshot
  - Sales funnel (rascunho, enviado, negociação, fechado, perdido) and dashboard
  - PDF with 3D images, plus WhatsApp
  - 46-stone photo catalogue
  - v40 project sheet with numbered cut plan and useful remnants; v41 remnant stock; v42 production-order PDF without prices
- **Reusable calculation logic** (ideas, rewritten in your own code):
  - Default linear metres: `reta=A`, `L=A+B−P`, `U=A+B+C−2P`, `ilha` saia = `2(A+B)`
  - L/U decomposition into rectangles: L = A×P + P×(B−P); U = A×P + P×(B−P) + P×(C−P)
  - Seams: `k=ceil(L/SL)`, `m=ceil(W/SW)`, `emendas = k·m − 1`
  - Shelf packing: sort by height, place in shelves left to right, open a new slab when full
  - Utilisation = used area / (n slabs × slab area)
  - Material cost = per m² with loss % **or** n slabs × slab price
  - `price = cost / (1 − margin − tax)`, blocked when margin + tax > 95%
  - Cost = material + labour (m² × rate) + services (qty × price) + installation (m² × rate + fixed) + freight
- **Honest self-diagnosis** (`DIAGNOSTICO.md`, `ROADMAP.md`):
  - The cut plan is a heuristic with no grain direction, no smart rotation and no validation against real jobs
  - Data lives only on the device ("perder o celular perde o negócio")
  - Untested on a low-end Android
  - No customer validation; the founder skipped customer interviews
  - The product grew into glass and window-frame modules (v37, v38), then rolled back to marmoraria-only on 2026-10-31 because it became confusing without validated demand
- The roadmap names a Brazilian competitor **"marmoristapro3d"** whose videos inspired the project sheet, remnant stock and production-order features. I could not find this product online (unverified).
- **Mobile 3D UX notes from the README:**
  - On a phone, 1 finger rotates horizontally while the page keeps scrolling vertically; 2 fingers zoom and tilt
  - Green handles on dimension ends change a measure by dragging, and price recalculates live
  - Undo/redo and autosave indicator
  - Portrait layout: 3D on top, menu at the bottom; landscape: side menu
  - Touch targets 40 to 44 px
  - Dragging pieces with a finger was not yet possible at first; added later for moving pieces only
  - Freehand point-by-point floor plan was built (v35) and then removed in the rollback

**duducoBS/orcamentos-marmoraria** — [repo](https://github.com/duducoBS/orcamentos-marmoraria)
- **Activity:** 13 commits, all on 2026-09-17 and 18 (a short burst, then idle). 0 stars.
- **Stack:** vanilla HTML/CSS/JS (`app.js` about 1,286 lines), PWA with service worker, Android WebView wrapper in .NET/C#, Windows installer. Ships an 83 MB APK and a 47 MB zip committed to git, a code-hygiene red flag.
- **License:** none formal; the README says it is free to customise and use commercially in marmorarias.
- **Features:**
  - Replicates a traditional paper quote: logo, CNPJ, client, items table with free-text values, auto installments every 30 days, signature lines
  - SVG illustrations of edge finishes (simple, thick, 45º with apron) and column styles
  - ViaCEP address lookup and CPF/CNPJ masks
  - WhatsApp text, LocalStorage, JSON export
  - **No geometry, m², slab or cut-plan logic**
- **Reusable ideas:** the edge-finish illustration sheet (`acabamentos.js`), the Brazilian quote layout, the installments generator, CEP lookup.

**Other repos found (GitHub search, 2026-11-25)**
- prizeant/CountertopCutter: React, Vite and Tailwind; one 1,875-line `CountertopOptimizer.jsx` that "programmatically plans out how many countertop slabs you need". 1 star; last commit 2025-05-30; no licence seen — [repo](https://github.com/prizeant/CountertopCutter)
- Time-AAA/MarmorariaSaoJoao: Ruby, MIT, "Sistema para gerenciamento de uma marmoraria", 3 stars, updated 2026-02 — [repo](https://github.com/Time-AAA/MarmorariaSaoJoao)
- RogerioLPD/Madigran: Dart/Flutter, "orçamento mármore", updated 2025-10 — [repo](https://github.com/RogerioLPD/Madigran)
- marmorariaprojeto1-cmd/marmoraria-3d (TypeScript, 2026-06) and juary-junior/Orcamento_marmore (TypeScript, 2026-07) — [repo](https://github.com/marmorariaprojeto1-cmd/marmoraria-3d); [repo](https://github.com/juary-junior/Orcamento_marmore)
- Most other "marmoraria" repos are landing pages (dozens, 0 to 2 stars) — [GitHub search "marmoraria"](https://github.com/search?q=marmoraria&type=repositories)
- General-purpose open-source nesting engines exist: SVGnest and Deepnest (Jack000), plus the deepnest-next fork. They do true irregular-shape nesting and could power a later phase. Licence and metadata were not verified this session (API blocked); I believe SVGnest is MIT and Deepnest GPL-3.0, but this is **unverified** — [SVGnest](https://github.com/Jack000/SVGnest); [Deepnest](https://github.com/Jack000/Deepnest)

### Inferences
- Copy Marmofácil's **architecture discipline**: pure `calc` functions, golden-file price tests, closed-quote snapshot, a "m² vs whole slab" switch, and "estimado vs medido" tags on measurements. Do not copy its scope creep. Its biggest lesson is non-technical: 42 versions in about 5 weeks with zero customers.
- Its shelf algorithm is fine for a slab-count estimate on rectangles. Real L/U nesting with rotation, grain and remnants is much harder and is where MarmoDraw and SlabWise compete.
- Licensing: Marmofácil has no licence and duducoBS has only an informal grant, so treat both as inspiration only.

### Gaps
- Exact last-push dates and licences from the GitHub API were not available (403). Commit dates come from the clones.
- I did not read CountertopCutter's algorithm in detail.

---

## 6. Strengths, weaknesses, what to copy, what to avoid

### Takeaway
Copy these: parametric shapes (reta, L, U, ilha) with live m² and price, a slab-count estimate, and a priced PDF over WhatsApp. Avoid these for an MVP: freehand CAD, true nesting, DXF/CNC, vein matching and heavy 3D.

### Cited Findings
- MarmoDraw: strong DXF/CNC and CAD depth (DXF R12 layers, DWG import, 25 edges); weak because it is bound to 1 PC and is not a quoting tool **(snippet)** — [Wayssoft MarmoDraw](https://www.wayssoft.com.br/marmodraw/)
- Stonify.com.br: strengths are free, phone browser, real slab photos and 100+ templates; weakness is no pricing **(snippet)** — [Stonify.com.br](https://stonify.com.br/)
- CounterGo shows draw → slab layout → price works as a sales tool at US$100/user — [Moraware CounterGo](https://www.moraware.com/countergo)
- Marmofácil's own risk list: unvalidated cut plan, device-only data, untested on low-end Android — [Marmofacil ROADMAP](https://github.com/Danielhsantos1/Marmofacil/blob/main/ROADMAP.md)
- Marmofácil marketing honestly says "O plano de corte é uma estimativa: confira com o seu cortador" — [Marmofacil vendas](https://github.com/Danielhsantos1/Marmofacil/tree/main/vendas)

### Inferences
- **Copy:**
  - Template-first drawing (Stonify's 100+ models, Marmofácil's parametric types) instead of freehand
  - Live price as you type a measure
  - Cutouts (cuba, cooktop) as priced services, not geometry
  - Remnant stock (Marmofácil v41) as a later differentiator for solo shops, who often reuse retalhos
  - Installments and edge-finish illustrations (duducoBS)
  - CounterGo's m² vs whole-slab pricing toggle
- **Avoid:**
  - Desktop-only licensing (MarmoDraw)
  - Data only in localStorage with no backup (Marmofácil, duducoBS)
  - Large binaries in git
  - Multi-vertical scope creep
  - Claiming precise yield without validation (SlabWise's unverified 10 to 15%)

### Gaps
- No hands-on test of any competitor UI.

---

## 7. Drawing UX on a phone and the MVP-or-later decision

### Takeaway
Freehand countertop CAD on a phone is hard. Even Marmofácil, after many versions, built a point-by-point free plan and then dropped it, and finger-dragging of pieces came late. Good mobile examples use **parametric templates with numeric fields and draggable dimension handles** (Marmofácil 3D handles, CounterGo's "drag and draw" on iPad, Stonify templates). Recommendation (inference): the MVP should have template shapes with an auto m² and slab-count estimate. Full nesting, DXF and photo/vein matching belong to a later phase.

### Cited Findings
- CounterGo targets iPad fingertip drawing (tablet, not phone) with a 6-step drag-and-draw tool — [Moraware CounterGo](https://www.moraware.com/countergo)
- Stonify.com.br offers 100+ ready models and says the cut plan opens on a phone **(snippet)** — [Stonify plano de corte](https://stonify.com.br/plano-de-corte-de-chapas/)
- Marmofácil phone patterns: parametric fields, plus 3D dimension handles that recalculate price live, undo/redo, 1-finger rotate with page scroll kept, pinch zoom, 44 px targets, and 3D above with menu below in portrait. Free-shape planta (v33, v35) was built and then removed in the 2026-10-31 rollback — [Marmofacil README](https://github.com/Danielhsantos1/Marmofacil); [DECISOES.md](https://github.com/Danielhsantos1/Marmofacil/blob/main/docs/DECISOES.md)
- Marmofácil's cut plan is a declared estimate with no grain or rotation, still unvalidated after 42 versions — [ROADMAP](https://github.com/Danielhsantos1/Marmofacil/blob/main/ROADMAP.md)
- MaxCut and PlanoCorte prove rectangle cut planning works on phones (free or freemium) — [MaxCut](https://www.maxcut.app/en); [PlanoCorte](https://planosdecorte.com.br/)

### Inferences
- **MVP:**
  - Shapes: reta, L, U, ilha, lavatório, plus "peça livre" as a list of rectangles
  - A 2D schematic, not 3D, with dimensions; per-piece measurements; saia and rodabanca in metres
  - Cutouts as services
  - A simple rectangle slab-count estimate (shelf/guillotine) shown as "estimativa" with seams count
  - Pricing per m² with loss % or per slab
  - PDF and WhatsApp
- **Phase 2:**
  - Visual cut plan per slab with remnants
  - Remnant stock
  - Slab photo as background
  - Manual drag-to-rotate on the slab
- **Phase 3:**
  - True irregular nesting (Deepnest-style), DXF export for CNC, vein matching
  - Only for clients with CNC; MarmoDraw at R$69 already covers this
- 3D looks good in a sales demo but is costly to build, and its performance on low-end Android is unknown (Marmofácil's own open risk). It is optional, not core.

### Gaps
- No usability data or user testing of phone drawing for countertops was found. YouTube demos for MarmoDraw and Stonify could not be reviewed in this session.
