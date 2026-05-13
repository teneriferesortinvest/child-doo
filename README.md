# child-doo

> Trusted childcare in Tenerife — niñeras, babysitters and canguros, vetted to the standard you'd use for your own kids.

**Live site:** https://teneriferesortinvest.github.io/child-doo/

---

## The story

child-doo started with one person's obsession — doing childcare properly.

**Melania Díaz** spent years working as a nanny with families in England, learning hands-on how to keep kids genuinely entertained as well as safe. Back home in Tenerife she trained formally as an *Auxiliar de Educación Infantil* and worked in kindergartens, putting the professional qualifications behind everything she'd picked up in living rooms and at playgroups.

Then she added the piece most agencies skip. She specialised in **Child Coaching and Emotional Intelligence**, so the carers in the child-doo network are briefed not just on logistics and safety, but on how to support a child's emotional development during every hour they're together.

She founded child-doo because the service she wanted for her own family didn't exist on the island yet. So she built it — and she vets every carer to the standard she'd use for her own kids.

> *"I firmly believe that nurturing languages from an early age brings real value to a child's development and education."*
> — Melania Díaz, founder

**Credentials:** Auxiliar de Educación Infantil · Kindergarten teacher · Child Coaching & Emotional Intelligence specialist · Years of family nanny experience in England.

---

## What's on the site

- **Our services** — 8 care types: live-in nannies, hourly babysitters, emergency cover, tutor + nanny, event childcare, bilingual carers, care + errands, outdoor experiences.
- **Why parents choose us** — disponibilidad, experiencia, tranquilidad y seguridad, servicio personalizado, proceso de selección minucioso, comunicación transparente.
- **How it works** — three steps: tell us what you need → we match the right carer → book your day and breathe.
- **Our story** — Melania's CV and the philosophy behind child-doo.
- **Contact** — quick form, replies handled by Melania directly.

## Three pillars

| Spanish     | English      |
|-------------|--------------|
| Confianza   | Trust        |
| Fiabilidad  | Reliability  |
| Seguridad   | Safety       |

---

## Tech

Single static page. No build step. Drop the folder anywhere that serves static HTML.

- `index.html` — everything inline (styles + scripts)
- `logo.png` — Melania's hand-drawn rainbow logo (used in the SVG draw animation)
- `baby.jpg` — Baby Biggie hero photo
- `rainbow.png` — crayon rainbow used in the contact section
- `BRIEF.md` — the SEO + content brief from Melania, source of truth for copy
- `reviews/` — internal QA / UX audit reports

### Animations
- Logo letter-by-letter draw on page load (SVG clip-path wipes per letter)
- Baby Biggie bobs idle, spins on hover
- Section headings auto-colored letter-by-letter via the brand palette
- Contact rainbow draws arc-by-arc on scroll into view
- Story types itself out like a typewriter, character-by-character
- All animations respect `prefers-reduced-motion`

### SEO
- `<title>` + meta description target *niñeras Tenerife*
- Schema.org `LocalBusiness` block with founder, area served, multilingual service list
- OG tags for share previews

---

## Status

Beta. Open items tracked in `BRIEF.md` §5 — domain, real form recipient, testimonials, pricing anchors.

Built by Claude Code + Tino for Melania Díaz.
