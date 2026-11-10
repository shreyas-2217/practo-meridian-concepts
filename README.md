# Practo for Animals + Meridian AI — Product Concepts

Founder-facing product exploration for an animal-care discovery platform alongside an AI education and content ecosystem.

---

## What this is

Three high-fidelity, responsive browser prototypes developed as concepts for the founder's product portfolio:

1. **Practo for Animals** — A search-first discovery platform for veterinary clinics, hospitals, diagnostics, ambulances, boarding and NGOs.
2. **Meridian AI Academy** — A conversion-focused landing page for practical AI and digital-skills programmes.
3. **AI Content Engine** — A repeatable, AI-assisted workflow for producing Instagram and LinkedIn carousels without a designer, plus a generated sample.

---

## How to view

Open `index.html` directly in a browser, or run a local server:

```bash
cd deliverables
python -m http.server 8000
```

Then visit `http://localhost:8000`.

---

## 1. Practo for Animals

### User problem
Pet owners, farmers and rescuers in India often rely on WhatsApp groups, Google Maps and word of mouth to find animal care. The result is slow, fragmented and stressful — especially during emergencies.

### Concept highlights
- **Search-first hero** with service + location inputs.
- **Map-inspired visual** showing nearby verified providers and open status.
- **Urgency strip** with ambulance request and 24/7 filter.
- **Category chips** for one-tap filtering: Vet, 24/7 Hospital, Diagnostics, Ambulance, Boarding, NGO.
- **Provider cards** with ratings, distance, fee band, wait time, open status and language support.
- **Dual CTAs** per card: primary booking/request and secondary call.
- **Provider listing and correction CTAs** to keep the ecosystem accurate.

### Market context
- India pet care is a fast-growing consumer market, estimated to approach ~$1B by 2025.
- Mobile-first discovery is the dominant behaviour for Indian pet owners searching vets.
- Emergency animal care remains hard to find quickly outside a few metro hubs.
- Bangalore is used as the pilot city because of high pet density and fragmented clinic discovery.

---

## 2. Meridian AI Academy

### User problem
Students and young professionals want practical AI skills, but most courses are too theoretical, too expensive, or assume a CS background.

### Concept highlights
- **Outcome-focused hero**: "Learn AI skills that actually get you hired."
- **Track switcher**: AI Fundamentals, AI Creator Stack, Automation & No-Code.
- **Curriculum cards** with week-by-week modules tied to the selected track.
- **Social proof + market numbers** for credibility.
- **Transparent 5-step lead-capture journey** to build trust.
- **Short registration form** with instant success feedback and a testimonial.

### Market context
- India online education reaches tens of millions of learners annually.
- AI job postings have seen strong year-over-year growth.
- Entry-level AI-skilled roles command a salary premium over general graduate hires.

### Automation concept
Form → Airtable/Notion → Make/n8n → confirmation email + calendar link → WhatsApp/email nurture → payment/enrolment.

---

## 3. AI Content Engine

### User problem
A founder-led brand needs consistent social content but cannot hire an in-house graphic designer.

### The 6-step workflow

1. **Capture** — Founder submits topic/angle in Notion/Airtable/Typeform.
2. **Research & structure** — ChatGPT/Claude/Perplexity propose a slide outline.
3. **Generate copy** — Headlines, body copy, captions, hashtags.
4. **Visual direction** — AI generates icons/imagery aligned to brand palette.
5. **Produce carousel** — Canva Bulk Create or Canva API fills templates.
6. **Review & publish** — Founder edits, exports, optionally schedules.

### Tools recommended
Notion · Airtable · Typeform · ChatGPT/Claude · Perplexity · Make/n8n · Canva · Midjourney/DALL·E · Buffer/Later.

### Impact framing
- Drafting + design time drops from 2–3 hours to ~10 minutes.
- Avoids recurring designer cost per carousel.
- Founder review stays under one hour before publishing.

---

## Design systems

- **Practo for Animals + Content Engine + hub**: warm editorial palette (paper, cream, forest green, clay), custom SVG accents, offset shadows, Fraunces serif display + Inter body + IBM Plex Mono for data.
- **Meridian AI**: deep ink UI with mint-to-violet accents, bento grid, modular curriculum, Fraunces display + Inter body.

---

## Technical notes

- Built with hand-written HTML, CSS and vanilla JavaScript.
- Fully responsive; no build step required.
- Google Fonts loaded via CDN.
- Sample carousel is a custom SVG using the Practo brand palette.

---

## Suggested next steps

1. Convert prototypes into a Figma component library for handoff.
2. Connect Practo provider search to a live CMS or API.
3. Build the carousel automation in Make/n8n with a Notion trigger.
4. Run mobile usability tests on the Practo booking flow.
