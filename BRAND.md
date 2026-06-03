# Rentheria — Brand Guide

**Manuel Alejandro Hernández Rentería**
Senior Frontend & Fullstack Engineer · Frontend Technical Lead
Guadalajara, Mexico · [rentheria.com](https://rentheria.com)

*Version 1.0 — the single source of truth. Everything (portfolio, GitHub, CV, LinkedIn, social) inherits from this document.*

---

## 1. Brand essence

**Who I am in one line:**
A senior engineer who builds tools that help people — clean, secure, production software, made with a collector's eye for detail.

**The idea behind the brand:**
A premium *curiosity cabinet*. I'm a builder and a collector — of dinosaurs, sci-fi, fossils, good coffee and good beer, and well-crafted code. The brand treats engineering the way a natural-history museum treats a specimen: serious, structured, premium, and quietly full of personality. The low-poly T-Rex is the embodiment — a creature *engineered* from clean geometric planes.

**Why this, not the old site:**
The previous portfolio led with a generic stack list ("Senior Angular Engineer") and neon gradients that any dev could own. This brand leads with the *human* and lets the engineering be the proof — distinctive, personal, and impossible to mistake for anyone else.

**Personality:**
Precise but playful. Serious about craft, nerdy about what I love. Premium without being cold. Generous — I build things that help.

---

## 2. Logo

### The mark
A low-poly papercraft Tyrannosaurus Rex head, faceted, in wine-red with bone-white highlights and aged-brass accents on a near-black ground.

### Variants (finalized)
| Variant | File | When to use |
|---|---|---|
| **Calm / front-view (primary)** | `calm-logo.png` | Avatar, site header, hero, anywhere the brand "faces" the viewer. The default and the richest version. |
| **Flat icon** | `flat-logo.png` | Small sizes, favicon (≤32px), app icon. Bold simplified facets, sharp eye — reads clean when tiny. |
| **Monochrome line** | `monocromatic-logo.png` | Single wine-red outline. Stamps, watermarks, embossing, one-color print, subtle backgrounds. |
| **Roaring / three-quarter** *(optional)* | — | Energetic contexts — banners, cover art, merch. Generate later if needed for impact moments. |

### Logo rules
- **Clear space:** keep padding around the mark equal to at least the height of one eye. Don't crowd it.
- **Backgrounds:** always on a dark ground (Obsidian/Cellar) or a clean neutral. Never on a busy photo or a clashing color.
- **Don't:** stretch, recolor outside the palette, add drop shadows/glows, rotate, or place the full-color mark on a light cluttered background.
- **Master files:** keep the original max-resolution renders. Suggested names: `logo-calm.png`, `logo-roar.png`, `logo-icon.png`, `logo-mono.svg`.
- **Favicon test:** the calm front-view silhouette must still read as a T-Rex at 32px. If a future variant fails this, use the simplified flat icon instead.

### Wordmark
"Rentheria" set in a serif (display), with the **e** accented in brass. Pairs beside or beneath the mark.

> **Renth**​*e*​**ria** — serif, the *e* in brass (#C8962E)

Tagline (optional): *Software, craft & curiosity.*

---

## 3. Color palette

### Core
| Role | Name | Hex | Use |
|---|---|---|---|
| Base | Obsidian | `#140D0D` | Primary background |
| Surface | Cellar | `#1F1414` | Cards, panels, raised surfaces |
| **Primary** | **Wine** | **`#501313`** | Signature color — headings accents, key UI, the mark |
| Primary light | Wine light | `#7E2230` | Hover states, secondary fills, gradients within wine |
| Text | Bone | `#F0E6E0` | Body and heading text on dark |

### Accents — use sparingly
| Name | Hex | Use |
|---|---|---|
| Brass | `#C8962E` | The one warm spark — the *e*, links, small highlights, the logo's edges |
| Fossil teal | `#1D6E56` | Rare secondary accent — success states, occasional contrast |
| Ash | `#8A7373` | Muted text, captions, borders, metadata |

### Usage ratio (rough)
~70% obsidian/cellar base · ~20% bone text · ~8% wine · ~2% brass. Wine is the hero *because* it's not everywhere — restraint is what makes it premium. Brass is a seasoning, never a main course.

---

## 4. Typography

| Role | Typeface | Notes |
|---|---|---|
| Display / headings | **Source Serif 4** | Neutral, trustworthy, grounded. The brand's voice — headings and wordmark. Free on Google Fonts. |
| Body / UI | **Outfit** | Geometric, modern sans. Pairs naturally with the faceted logo. Free on Google Fonts. |
| Code / accents | **Geist Mono** | Minimal, clean. Code blocks and small technical labels only. Free on Google Fonts. |

Google Fonts import:
`https://fonts.googleapis.com/css2?family=Source+Serif+4:opsz,wght@8..60,400;500;600&family=Outfit:wght@400;500&family=Geist+Mono:wght@400&display=swap`

**Rules:**
- Two weights of the body sans is plenty (regular + medium). Avoid heavy/black weights — they read cheap against the refined serif.
- Sentence case for almost everything. Reserve the serif for size and elegance, not ALL CAPS.
- Mono is a *spice*: a one-line `const craft = obsession.refined();` flourish, code blocks, tags. Don't set paragraphs in it.

---

## 5. Voice & tone

**How I sound:**
- **Clear over clever.** Plain language, short sentences, no buzzword soup. The opposite of "synergistic scalable solutions."
- **Confident, not boastful.** "I build X" not "I'm passionate about leveraging X."
- **Warm and human.** A little personality and dry humor is welcome. The dinosaurs, the coffee, the collector — let them show.
- **Specific.** Concrete projects, real outcomes, actual decisions. Specificity *is* credibility.

**Bilingual:** Spanish for conversation and personal voice; English for code, commits, and technical writing. The brand works in both — keep the tone consistent across languages.

**Do:** "I help product teams ship maintainable apps faster." · "Built a race-safe stock system for a B2B pottery API."
**Don't:** "Passionate, results-driven engineer leveraging cutting-edge synergies."

---

## 6. Imagery & graphic language

- **Faceted / low-poly** geometry echoes the logo — use angular, planar shapes as decorative elements, dividers, section breaks.
- **Museum / specimen framing:** present projects like catalogued exhibits — a label, a number, a clean card on a dark ground.
- **Photography:** warm, moody, low-key lighting (matches the cellar/wine mood). Your real workspace and collection are on-brand — they tell the story.
- **Avoid:** stock "techy" imagery (glowing circuit boards, blue binary rain, generic code screenshots), rainbow neon gradients, clip-art icons.

---

## 7. Application checklist

When building anything (site, GitHub profile, CV, social), it's on-brand if:

- [ ] Background is obsidian/cellar dark, not generic dark-blue or pure black
- [ ] Wine is the signature accent; brass appears once or twice as a spark
- [ ] Headings are serif; body is clean sans; mono only for code
- [ ] The T-Rex mark is present and has clear space around it
- [ ] Copy leads with the human and the specific, not a stack list
- [ ] Nothing uses the old neon rainbow gradient
- [ ] It would be hard to mistake this for any other developer's brand

---

*Next deliverables in build order: GitHub profile → portfolio site → LinkedIn & social. Each inherits directly from this guide.*
