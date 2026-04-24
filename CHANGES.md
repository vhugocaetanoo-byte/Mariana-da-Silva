# CHANGES — RafaVet → Missão Aprovação Brand Swap

## Files touched

| File | Change |
|---|---|
| `.aidesigner/mcp-latest.html` | Full content + theme swap (Phases A–D) |
| `public/placeholders/*.svg` | 23 placeholder SVGs created (Phase B) |
| `CHANGES.md` | This file |

---

## Phase A — CSS variables / palette swap

| Role | Old value | New value |
|---|---|---|
| Primary dark BG | `#11091b`, `#130a1e`, `#0b0512`, `#1a0f2b` | `#1A2E1B` |
| Card dark BG | `#1d132d`, `#1f1635` | `#2D4A2B` |
| Deep purple boxes | `#2a134a`, `#1a0a2e`, `#2b184a` | `#1A2E1B` / `#2D4A2B` |
| Accent / highlight | `#D946EF`, `#E879F9`, `#C084FC` (pink/magenta) | `#C9A961` (gold) |
| Scrollbar thumb hover | `#a855f7` | `#C9A961` |
| `text-gradient-highlight` gradient | `#E879F9 → #C084FC` | `#C9A961 → #D4B874` |
| `highlight-box` background | `rgba(45,27,78,0.5)` | `rgba(26,46,27,0.5)` |
| `highlight-box` border | `rgba(76,46,133,0.8)` | `rgba(201,169,97,0.5)` |
| `image-ring-pulse` shadow | `rgba(168,85,247,0.15)` | `rgba(201,169,97,0.15)` |
| `credibility-bar` BG | `rgba(14,8,23,0.85)` | `rgba(20,35,20,0.85)` |
| Body background | `#F3F3F7` | `#F5F1E8` |
| Light section BG | `bg-[#f9fafb]`, `bg-[#F3F3F7]`, `bg-[#F9FAFB]` | `bg-[#F5F1E8]` |
| Hero blobs (HSL) | `hsl(270/183/320)` family | `hsl(120/60/90)` family |
| Hero image border | `hsl(270_50%_60%/0.45)` | `rgba(201,169,97,0.45)` |
| Badge border/BG | `hsl(270_60%_...)` | `rgba(201,169,97,...)` |
| Card borders on dark | `border-purple-900/50` | `border-[#C9A961]/20` |
| Icon circles on dark | `bg-purple-900/40 text-pink-400` | `bg-[#2D4A2B] text-[#C9A961]` |
| Summary strip | `from-purple-100 to-pink-100 border-purple-200` | `from-[#E8E0C8] to-[#F0E8D0] border-[#C9A961]/40` |
| Card header text | `text-purple-700` | `text-[#1A2E1B]` |
| Card page/count badges | `bg-purple-50 text-purple-600` | `bg-[#F5F1E8] text-[#1A2E1B]` |
| Quiz badge text | `text-purple-600` | `text-[#C9A961]` |
| Quiz answer hover/checked | `hover:border-purple-200 peer-checked:border-purple-500 peer-checked:bg-purple-50` | gold equivalents |
| Quiz CTA box | `bg-purple-50 border-purple-100 text-purple-900 text-purple-700` | cream + dark green |
| Quiz CTA button | `bg-pink-500 hover:bg-pink-600` | `bg-[#C9A961] hover:bg-[#B89751]` |
| Comparison CTA button | `bg-purple-600 hover:bg-purple-700` | `bg-[#1A2E1B] hover:bg-[#2D4A2B]` |
| Preview section label BGs | `bg-[#1f1635] border-purple-800` | `bg-[#2D4A2B] border-[#C9A961]/40` |
| Preview unlock button | `bg-[#b32790] hover:bg-[#921f75]` | `bg-[#C9A961] hover:bg-[#B89751]` |
| Transition offer box | `from-[#2a134a] to-[#1a0a2e] border-purple-800` | `from-[#1A2E1B] to-[#2D4A2B] border-[#C9A961]/40` |
| Offer box CTA | `from-pink-600 to-purple-600` | `from-[#C9A961] to-[#D4B874]` |
| Bonus card borders | `border-purple-900` | `border-[#C9A961]/20` |
| Bonus featured border | `border-pink-500/30` | `border-[#C9A961]/50` |
| Bonus featured glow | `bg-pink-500/20` | `bg-[#C9A961]/20` |
| Bonus badge | `bg-pink-600` | `bg-[#C9A961]` |
| Bonus blob | `hsl(270_60%_40%/0.1)` | `hsl(120_40%_15%/0.1)` |
| Author photo border | `border-purple-100` | `border-[#C9A961]/20` |
| Author divider bar | `bg-pink-500` | `bg-[#C9A961]` |
| Footer border | `border-purple-900/40` | `border-[#C9A961]/20` |
| Footer icon + hover links | `ph-paw-print text-pink-500`, `hover:text-pink-400` | `ph-medal text-[#C9A961]`, `hover:text-[#C9A961]` |
| Tailwind `theme.colors.theme` | bgDark `#130a1e`, highlight `#d946ef`, highlightDark `#a855f7`, accent `#1B9198` | `#1A2E1B`, `#C9A961`, `#B89751`, `#C9A961` |

**Preserved unchanged (semantic):**
- `bg-red-500` — "APOSTILA GENÉRICA" card header (bad-result red)
- `bg-[#1B9198]` and `border-[#1B9198]/20` — "MISSÃO APROVAÇÃO" comparison card header (success green)
- `bg-[#25D366]` — WhatsApp float button (brand green)
- `from-orange-400 to-red-500` — center "Material Principal" badge (original kept)
- All body neutral grays (`text-gray-400`, `text-slate-*`, `border-gray-*`)

---

## Phase B — Image placeholders created

| File | Dimensions | Represents |
|---|---|---|
| `hero-product-mockup.svg` | 800×600 | Mockup do PDF Missão Aprovação com capa verde militar e insígnia dourada |
| `pdf-preview-page-1.svg` | 800×600 | Questões de Frações — Matemática |
| `pdf-preview-page-2.svg` | 800×600 | Questões de Operações Matemáticas |
| `pdf-preview-page-3.svg` | 800×600 | Questões de Razão e Proporção |
| `pdf-preview-page-4.svg` | 800×600 | Questões de Geometria Plana |
| `pdf-preview-page-5.svg` | 800×600 | Questões de Interpretação de Textos |
| `pdf-preview-page-6.svg` | 800×600 | Questões de Figuras de Linguagem |
| `pdf-preview-page-7.svg` | 800×600 | Questões de Ortografia e Acentuação |
| `pdf-preview-page-8.svg` | 800×600 | Questões de Classes de Palavras |
| `pdf-preview-page-9.svg` | 800×600 | Amostra Final — última página visível com lock |
| `comparison-before.svg` | 700×500 | Apostila genérica sem organização |
| `comparison-after.svg` | 700×500 | Missão Aprovação — material organizado |
| `testimonial-1.svg` | 400×300 | Depoimento família CMBH |
| `testimonial-2.svg` | 400×300 | Depoimento família CMC |
| `testimonial-3.svg` | 400×300 | Depoimento família aprovada |
| `testimonial-4.svg` | 400×300 | Depoimento a confirmar |
| `testimonial-5.svg` | 400×300 | Depoimento a confirmar |
| `testimonial-6.svg` | 400×300 | Depoimento a confirmar |
| `bonus-1-cover.svg` | 400×500 | Capa do Guia de Rotina de Estudos de 12 Semanas |
| `price-card-product.svg` | 400×500 | Mockup do PDF Missão Aprovação (card central) |
| `bonus-2-cover.svg` | 400×500 | Capa dos Mapas Mentais dos 20 Assuntos |
| `creator-photo.svg` | 400×400 | Foto do criador do Missão Aprovação |
| `og-card.svg` | 1200×630 | Open Graph card para redes sociais |

---

## Phase C — Copy swap summary

| Section | Key changes |
|---|---|
| Meta/head | Title, description, OG tags updated to Missão Aprovação |
| Promo bar (6.1) | `📚 PROMOÇÃO DE VOLTA ÀS AULAS` → `🎖️ PREPARAÇÃO ADMISSÃO AOS COLÉGIOS MILITARES` |
| Hero badge | `Saia na frente do concorrente` → `Saia na frente de 95% dos candidatos` |
| H1 | Full headline replaced; highlight span: `Nunca Mais Esqueça` → `Aprovado no Colégio Militar` |
| Sub-headline | Veterinary text → `1.149 questões reais das provas oficiais de 2024 e 2025` |
| Description box | Veterinary content → Missão Aprovação pitch |
| Hero CTA | `Quero Garantir Meu Acesso` → `Quero Garantir a Aprovação →` (→ wiapy.com) |
| Hero badge pill | `🔥 + 100 páginas` → `+ 1.149 questões` |
| Credibility bar | 4 stats replaced with Colégios Militares theme |
| Para Quem É (6.3) | 4 persona cards: veterinary students → parents of 4th/5th graders, families |
| Para Quem É banner | Updated to "sua família" framing |
| Conteúdo Completo (6.4) | 7 cards: pharmacology topics → Matemática + Português subjects with question counts |
| Stats strip | `15 tópicos / 120+ páginas / 7 áreas / 30+ exercícios` → `22 tópicos / 1.149 questões / 8 colégios / 2 anos` |
| Prévia (6.5) | Heading, subline, 9 preview images, page labels — all updated |
| Preview lock button | `Baixar Completo` → `Ver Material Completo` (→ wiapy.com) |
| Preview caption | `100 páginas` → `1.149 questões reais dos 8 Colégios Militares` |
| Transition box (6.5) | Title, subtitle, CTA — updated to Missão Aprovação framing |
| Quiz (6.6) | Heading, subline, badge, counter, question, 4 alternatives — all replaced |
| Quiz CTA box | Updated with `1.148` framing and wiapy.com |
| Comparison (6.7) | Labels: `MÉTODO TRADICIONAL/RAFAVET` → `APOSTILA GENÉRICA/MISSÃO APROVAÇÃO`; prompt + CTA updated |
| Testimonials (6.8) | Heading, subline, 6 alt texts (3 with brief copy, 3 marked as TBD) |
| Bonuses (6.10) | Heading, subline, 3 cards renamed (Bonus 1 = Guia Rotina, Bonus 2 = Mapas Mentais) |
| Creator (6.12) | H2 and 3 paragraphs replaced with brief copy |
| Footer (6.14) | Brand: `RafaVet` → `Missão Aprovação`; tagline + copyright updated |
| WhatsApp link | URL query text updated from RafaVet to Missão Aprovação |

---

## Phase D — Checkout URL audit

All CTA buttons point to `https://wiapy.com` (6 occurrences):
1. Hero primary CTA (`<a>` tag)
2. Preview section lock button
3. Transition offer box CTA
4. Quiz section CTA
5. Comparison section CTA
6. Bonuses section main CTA

---

## TODOs left in code

| Location | TODO |
|---|---|
| Conteúdo Completo section (HTML comment) | `TODO: confirm question counts with producer — values below are approximate distributions totaling ~1.149` |
| `testimonial-4/5/6.svg` alt texts | "Depoimento a confirmar" — needs real WhatsApp screenshot images from producer |

---

## Structural decisions / edge cases

1. **Sections not in source clone**: The brief references sections 6.9 (comparison table with rows), 6.11 (price card + countdown), 6.13 (FAQ), and 6.14 PS section. None of these exist in the source clone HTML. Per Part 1 Rule 3, they were NOT added. Copy for these sections is not implemented.

2. **Testimonials count**: Brief specifies 3 testimonial texts; source has 6 image-based cards. Per Rule 3, all 6 cards are kept. Cards 1–3 use the provided testimonial copy in alt text. Cards 4–6 are marked as "a confirmar".

3. **Author section paragraphs**: Source has 3 `<p>` tags; brief provides 6 paragraphs. Mapped to 3 slots using paragraphs 1, 4 (highlighted), and combined 5+final from brief.

4. **Method comparison**: Source uses two static image panels (no slider drag). Brief (6.7) describes a "slider drag" — the source has no such mechanism. Labels and images were updated; slider logic untouched (it doesn't exist).

5. **Hero CTA tag change**: Original used `<button>`; changed to `<a href="https://wiapy.com">` to enable direct navigation. Class structure and visual appearance preserved.

6. **Original `button` tags for CTAs**: Several CTA buttons converted to `<a>` tags pointing to wiapy.com, preserving all classes and layout — only tag type and href changed.

7. **Footer icon**: `ph-paw-print` (veterinary) → `ph-medal` (military). Same icon library, same position.
