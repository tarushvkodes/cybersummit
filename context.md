# Context for cybersummit.cc

Use this file as the project prompt/context for building the Cyber Summit website.

## Project

Build a public-facing website for **Cyber Summit 2026** at **cybersummit.cc**.

This should be a polished event site for a high school cybersecurity summit in Loudoun County. The site needs to feel bold, intentional, and memorable—not like generic startup SaaS UI. It should convert visitors into attendees, mentors, and sponsors, while also making the event feel real, high-energy, and technically credible.

## Core Purpose

The site should do three jobs well:

1. **Convince students to attend**
2. **Help parents/teachers understand legitimacy and logistics**
3. **Give sponsors a clean path to learn more and support the event**

## Primary Audiences

- High school students interested in cybersecurity, AI, hacking, hardware, and tech
- Beginners who are curious but not yet experienced
- Parents and teachers who want clear logistics and credibility
- Potential sponsors and partners

## Canonical Event Facts

- **Event:** Cyber Summit 2026
- **Date:** Saturday, May 30, 2026
- **Time:** 9:00 AM–4:00 PM
- **Location:** Briar Woods High School
- **Address:** 22525 Belmont Ridge Rd, Ashburn, VA 20148

## Public CTAs

- **Register:** https://docs.google.com/forms/d/e/1FAIpQLSdL29bfStBrlT5844vwBeCmYZgYLa5X3FTxZk3CVsZaRTKPzA/viewform?usp=header
- **More information doc:** https://docs.google.com/document/d/13qeNF1N5Q5MzDDSE0J5koW1K1PNoTSltkLn6fwH0VCI/edit?usp=sharing
- **Optional sponsor payment link:** https://lcps.schoolcashonline.com/Fee/Details/62916/371/False/True

Only expose the sponsor payment link if organizers explicitly want it public.

## Recommended Information Architecture

### 1. Home
Main landing page with:
- Hero section
- Event overview
- Workshop highlights
- Who should attend
- Why it matters
- Schedule preview
- Register CTA
- Sponsor CTA

### 2. Schedule
Dedicated schedule page or section using the provided schedule content.

### 3. Sponsors
Sponsor tiers, why sponsorship matters, optional downloadable sponsor packet, and CTA to contact/support.

### 4. FAQ / Logistics
Can be its own page or a strong section on the homepage:
- what to bring
- experience level
- food
- location
- basic expectations

## Content to Use on the Public Site

Base public copy primarily on these extracted files:

- [Event guide](./content/event-guide.md)
- [Schedule](./content/schedule.md)
- [Sponsorship summary](./content/sponsorship.md)

Use these visual assets:

- [Logo](./public-assets/cybersummit-logo.png)
- [Hero banner](./public-assets/cybersummit-hero-banner.png)
- [Event poster](./public-assets/cybersummit-event-poster.png)

## Files That Should Stay Off the Public Site

These are planning/internal/support docs and should **not** be surfaced as public website content:

- `Team responsibilites_.docx`
- `Cyber Summit budget.xlsx`
- `Panelist info/Guest Speaker Panel Questions.docx`
- `Panelist info/Email to panelist.docx`
- `Panelist info/Panel Questions.docx`
- `Workshops/Workshop ideas.docx`
- `Workshops/RvB.docx`
- `Images/Untitled document.docx` (appears to be an attendee/roster-style table)
- `Payment link + email.docx` should not be published as-is because it contains outreach copy and sponsor-tracking notes

## Important Source Inconsistencies to Flag

Before publishing, verify these with organizers:

1. **Sponsorship deadline conflict**
   - one doc says **April 30, 2026**
   - another says **May 8, 2026**

2. **Sponsor payment link exposure**
   - one doc suggests the online payment link can be public
   - another version says it should be provided upon request

Do not silently choose one if the final site copy is meant to be official.

## Tone + Brand Direction

The existing materials already lean into a **neon cyber / retro-futurist / high-energy technical** aesthetic. Keep that spirit, but elevate it.

The design should feel:
- cinematic
- sharp
- immersive
- credible
- youth-oriented without looking childish
- futuristic without falling into generic AI gradient sludge

It should feel closer to a polished cyber event poster + premium launch microsite hybrid.

## Visual Guidance

Take cues from the uploaded assets:
- electric cyan / magenta / deep navy / black
- luminous circuitry motifs
- shield / security symbolism
- high contrast
- dramatic glow used intentionally, not everywhere
- layered depth, glass, scanlines, grid energy, controlled motion

Avoid making the site feel like:
- a generic tech startup
- a template
- a hackathon clone
- default Tailwind blocks pasted together
- “AI made this” slop

## Messaging Priorities

The homepage should quickly communicate:

- this is a **real** event
- it is **hands-on**
- students do **actual cybersecurity activities**
- beginners are welcome
- there is a strong AI + hardware + security angle
- it has legitimate structure, schedule, and leadership
- there is a direct way to register now

## Workshop Highlights to Surface

Use these as hero/supporting content blocks:

- **Cyber Escape Room** — puzzles, digital clues, forensics, teamwork
- **AI Capture The Flag** — AI model attacks/defense, adversarial concepts, prompt injection
- **AI Hardware Lab** — emotion recognition + Arduino/microcontroller interaction
- **IoT Penetration Testing Lab** — smart devices, vulnerabilities, beginner pentesting concepts

## Logistics to Surface

- no prior cybersecurity experience is required for most activities
- laptop recommended but not required for all activities
- bring charger
- lunch and light refreshments provided
- if severe food allergies, bring a packed lunch

## Implementation Preferences

- production-grade frontend
- clean component structure
- accessible contrast and navigation
- responsive across desktop/mobile
- tasteful motion
- visually distinctive typography
- sections should feel authored, not auto-generated
- use the provided assets rather than inventing random unrelated visuals

## Suggested Page Memory Moments

The site should have at least one or two unforgettable touches, for example:
- a striking hero reveal using the logo/shield mark
- schedule cards that feel like a mission briefing
- workshop sections that behave like classified dossier entries
- sponsor tier UI that feels premium rather than administrative

## Integrated Frontend Prompt

---
name: frontend-design
description: Create distinctive, production-grade frontend interfaces with high design quality. Use this skill when the user asks to build web components, pages, artifacts, posters, or applications (examples include websites, landing pages, dashboards, React components, HTML/CSS layouts, or when styling/beautifying any web UI). Generates creative, polished code and UI design that avoids generic AI aesthetics.
license: Complete terms in LICENSE.txt
---

This skill guides creation of distinctive, production-grade frontend interfaces that avoid generic "AI slop" aesthetics. Implement real working code with exceptional attention to aesthetic details and creative choices.

The user provides frontend requirements: a component, page, application, or interface to build. They may include context about the purpose, audience, or technical constraints.

## Design Thinking

Before coding, understand the context and commit to a BOLD aesthetic direction:
- **Purpose**: What problem does this interface solve? Who uses it?
- **Tone**: Pick an extreme: brutally minimal, maximalist chaos, retro-futuristic, organic/natural, luxury/refined, playful/toy-like, editorial/magazine, brutalist/raw, art deco/geometric, soft/pastel, industrial/utilitarian, etc. There are so many flavors to choose from. Use these for inspiration but design one that is true to the aesthetic direction.
- **Constraints**: Technical requirements (framework, performance, accessibility).
- **Differentiation**: What makes this UNFORGETTABLE? What's the one thing someone will remember?

**CRITICAL**: Choose a clear conceptual direction and execute it with precision. Bold maximalism and refined minimalism both work - the key is intentionality, not intensity.

Then implement working code (HTML/CSS/JS, React, Vue, etc.) that is:
- Production-grade and functional
- Visually striking and memorable
- Cohesive with a clear aesthetic point-of-view
- Meticulously refined in every detail

## Frontend Aesthetics Guidelines

Focus on:
- **Typography**: Choose fonts that are beautiful, unique, and interesting. Avoid generic fonts like Arial and Inter; opt instead for distinctive choices that elevate the frontend's aesthetics; unexpected, characterful font choices. Pair a distinctive display font with a refined body font.
- **Color & Theme**: Commit to a cohesive aesthetic. Use CSS variables for consistency. Dominant colors with sharp accents outperform timid, evenly-distributed palettes.
- **Motion**: Use animations for effects and micro-interactions. Prioritize CSS-only solutions for HTML. Use Motion library for React when available. Focus on high-impact moments: one well-orchestrated page load with staggered reveals (animation-delay) creates more delight than scattered micro-interactions. Use scroll-triggering and hover states that surprise.
- **Spatial Composition**: Unexpected layouts. Asymmetry. Overlap. Diagonal flow. Grid-breaking elements. Generous negative space OR controlled density.
- **Backgrounds & Visual Details**: Create atmosphere and depth rather than defaulting to solid colors. Add contextual effects and textures that match the overall aesthetic. Apply creative forms like gradient meshes, noise textures, geometric patterns, layered transparencies, dramatic shadows, decorative borders, custom cursors, and grain overlays.

NEVER use generic AI-generated aesthetics like overused font families (Inter, Roboto, Arial, system fonts), cliched color schemes (particularly purple gradients on white backgrounds), predictable layouts and component patterns, and cookie-cutter design that lacks context-specific character.

Interpret creatively and make unexpected choices that feel genuinely designed for the context. No design should be the same. Vary between light and dark themes, different fonts, different aesthetics. NEVER converge on common choices (Space Grotesk, for example) across generations.

**IMPORTANT**: Match implementation complexity to the aesthetic vision. Maximalist designs need elaborate code with extensive animations and effects. Minimalist or refined designs need restraint, precision, and careful attention to spacing, typography, and subtle details. Elegance comes from executing the vision well.

Remember: Claude is capable of extraordinary creative work. Don't hold back, show what can truly be created when thinking outside the box and committing fully to a distinctive vision.

