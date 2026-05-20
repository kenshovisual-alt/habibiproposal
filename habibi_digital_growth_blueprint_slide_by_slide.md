# HABIBI Marrakech - Website Conversion Document

Source reference: HABIBI Digital Growth Blueprint, 15-slide PDF.

Purpose of this document: convert the existing slide presentation into a clear, editable, slide-by-slide website brief for Codex in VS Code. The PDF remains the visual reference for layout, animations, icons, cards, illustrations, and overall style.

---

## Global Website Direction

### Goal

Create a dynamic, animated, premium website presentation for HABIBI Marrakech, based on the existing 15-slide blueprint.

The website should not feel like a flat PowerPoint converted to HTML. It should feel like a high-end digital growth proposal, with cinematic scroll sections, animated cards, clean transitions, and responsive layouts.

### Visual Style

IMPORTANT: The attached PDF is ONLY a structural and informational reference.

The original presentation design is visually weak and should NOT be recreated literally.

The rebuild must reinterpret the information completely with a far more premium, editorial, cinematic, architectural, and luxury hospitality-focused design language.

Use the PDF only for:

- Information hierarchy
- Messaging
- Strategic structure
- Section order
- Narrative flow

Do NOT copy:

- Original layouts
- Original card styling
- Original typography scale
- Original spacing system
- Original compositions
- Original visual balance
- Generic slide aesthetics

Typography:

- Use Cormorant Garamond for all major titles and editorial headings.
- Use Inter for body text, UI, labels, captions, pricing, and supporting content.
- Large elegant typography with intentional spacing.

Color Direction:

- White and off-white backgrounds.
- Deep black and charcoal inverted sections.
- Ocean turquoise accents.
- Burnt dark orange accents.
- Soft cinematic shadows.
- Minimal gradients only where useful.

Design Philosophy:

- Editorial luxury hospitality aesthetic.
- Architectural compositions.
- Strong negative space.
- Sophisticated typography hierarchy.
- Refined asymmetrical layouts.
- Minimal but visually powerful.
- Layered compositions instead of repetitive boxed cards.
- Premium keynote presentation feeling.
- Interactive investor-deck atmosphere.

Avoid:

- Generic SaaS aesthetics.
- Startup template feeling.
- Cheap PowerPoint-style layouts.
- Obvious AI-glow visuals.
- Repetitive generic card grids.

The final result should feel like a luxury hospitality growth presentation created by a top-tier creative studio, not a PDF converted into HTML.

### Suggested Tech

- HTML
- Tailwind CSS
- JavaScript
- GSAP for scroll animations
- Optional Lenis for smooth scrolling

### Presentation System & Animation Principles

IMPORTANT: This should NOT behave like a normal scrolling website.

The experience should feel like:

- A premium keynote presentation.
- A cinematic investor deck.
- An interactive luxury hospitality presentation.
- A guided digital story.

Presentation Navigation:

- Minimal bottom navigation arrows.
- Elegant progress indicator.
- Visible slide numbering like 04 / 15.
- Navigation dots for all slides.
- Smooth scene-to-scene transitions.
- Snap-style slide behavior.
- Optional keyboard arrow support.
- Optional mouse wheel progression.

The experience should NOT feel like:

- A long marketing website.
- A generic agency landing page.
- A SaaS template.
- A PowerPoint exported directly to HTML.

Animation Direction:

- Each section behaves like a presentation scene.
- Cinematic transitions between scenes.
- Layered motion and depth.
- Elegant fade, blur, masking, scaling, and parallax.
- Motion should feel expensive and controlled.
- No exaggerated startup animations.
- No flashy motion overload.

Specific Motion Ideas:

- Statistic cards can count upward.
- Timelines can progressively draw.
- Navigation indicators animate subtly.
- Radial systems animate organically.
- Certain transitions can slightly darken/lighten the screen between scenes.
- Content should reveal with intentional pacing.

Mobile Behavior:

- Keep the presentation feeling on mobile.
- Mobile can behave more like swipeable scenes.
- Keep navigation elegant and minimal.
- Avoid messy stacking and overflow.

### Important Website Rules

- Recreate all text as real HTML.
- Do not place text inside images.
- Do not use fixed PowerPoint slide dimensions.
- Make it fully responsive.
- Keep mobile version clean, stacked, and readable.
- Use the PDF mainly as visual and content reference.
- Do not invent new services, numbers, or claims unless clearly marked as placeholders.
- Keep all work scoped to this new HABIBI page.

---

# Working Folder Instructions for Codex

Current working folder: use the existing HABIBI test folder that was previously used for the scroll-motion website presentation experiment.

Important file/folder context:

- There is already a `CLAUDE.md` file in the project. Codex may not automatically follow it in the same way Claude does, so the key instructions must also be included directly in the Codex prompt.
- There is an `index.html` file.
- There is also an `index.html2` or `index2.html` style file/reference from the previous experiment.
- Codex must NOT treat the existing `index.html` or `index.html2` as the final design source.
- Codex should use the existing folder only as a working environment and reference point.
- The new presentation experience must be created as a separate slide-based page, not mixed into the previous scroll website.

Required structure:

```text
/habibi-test/
  index.html                  existing / old reference, do not overwrite unless explicitly requested
  index2.html                 previous scroll-motion website reference, use only as iframe/reference if needed
  CLAUDE.md                   may contain project guidance, but Codex must still receive full instructions directly

  /slide-illustration-reference/
    ...                       rough illustration style references for the new slides

  /habibi-presentation/
    index.html                NEW slide-based presentation page
    styles.css                scoped CSS for the new presentation
    script.js                 scoped JS for slide navigation and animations
```

If keeping everything in one HTML file is easier, Codex can create:

```text
/habibi-presentation.html
```

But preferred setup is a clean separated folder:

```text
/habibi-presentation/index.html
```

Iframe requirement:

The old scroll-motion website version can be shown inside the new slide presentation only as a reference/demo slide if useful. If used, embed it through an iframe pointing to `index2.html`.

Example:

```html
<iframe src="../index2.html" title="Previous website motion reference"></iframe>
```

Rules:

- Do not redesign the old scroll-motion website.
- Do not overwrite the old experiment.
- Do not copy the old page structure blindly.
- Use it only as motion/reference material or as an embedded preview where relevant.
- The new output must be a separate slide-based presentation.

Illustration reference folder:

There is a folder called `slide-illustration-reference` with rough visual/style references for the type of illustration and slide feel wanted.

Codex must:

- Review that folder before designing the slide visuals.
- Use it as style direction, not as literal layout copying.
- Build the new presentation using the same general feeling: premium, clean, editorial, contrast-led, with turquoise ocean and burnt orange accents.

---

# Revised Presentation Structure

The original PDF has 15 slides, but the new version should be expanded because the website, e-commerce phase, training app, and phase structure need clearer separation.

Recommended new structure: 18 slides.

Reason:

- The current PDF mixes strategy and website into one slide.
- It does not give the website its own full slide.
- It does not give the training app its own full slide.
- Website Phase 1 and Website Phase 2 need clearer separation.
- The investment section should become easier to understand.

New slide order:

1. Cover / Hero
2. Market Opportunity
3. Competitive Arena
4. The Digital Growth Engine
5. Strategic Foundation / Marketing Plan
6. Website Phase 1 - Digital Flagship
7. Website Phase 2 - E-Commerce & Gift Cards
8. Staff Training App
9. Visibility Layer - SEO, GEO, Google Business Profile
10. Reviews as Business Intelligence
11. Social Media & Community Cultivation
12. Reservation Channels - WhatsApp, Instagram DM, Outreach
13. Direct Message Automation Flow
14. Phase Roadmap - Phase 1 and Phase 2
15. Phase 1 Investment Architecture
16. Monthly Partnership Matrix
17. Why Kensho / Not an External Agency
18. Final Call to Action

---

# Slide-by-Slide Content and Website Structure

---

## Section 01 - Cover / Hero

### Original Slide

Page 1.

### Title

HABIBI Marrakech

### Subtitle

The Digital Infrastructure & Growth Blueprint - 2026

### Footer / Credit

Prepared by Kensho Hospitality

### Visual Direction

The slide shows a premium grey-toned map / terrain-style background with a floating white title card on the left. The overall style feels minimal, premium, architectural, and strategic.

### Website Adaptation

Create a full-height hero section.

Elements:

- Large title card on the left.
- Abstract topographic / terrain-style background on the right.
- Soft shadows.
- Subtle parallax movement on the terrain background.
- Small credit line near bottom left.

### Animation

- Background fades in slowly.
- Title card slides in from left with soft blur.
- Subtitle appears after title.
- Credit line fades in last.

---

## Section 02 - The Market: A Premier Global Destination

### Original Slide

Page 2.

### Heading

The Market: A Premier Global Destination

### Metric Cards

#### Card 1

17.4M Morocco Visitors 2024. +20% YoY, generating \$11B in revenue

#### Card 2

4M Marrakech Arrivals Nearly 12 million overnight stays

#### Card 3

72% Average Hotel Occupancy Across the city

#### Card 4

\#6 Global Destination Airbnb Travel Trends, 2024

### Bottom Statement

The government's 2026 strategic target was reached two years early. At 500-1,000+ MAD per cover nightly, the demand for premium dinner show experiences is at an all-time high.

### Visual Direction

Four white stat cards with terracotta icons and big numbers. Bottom statement inside a horizontal white card with a terracotta top border.

### Website Adaptation

Create a stats section with 4 animated metric cards.

### Animation

- Cards count up numerically where possible.
- Cards reveal one by one.
- Bottom statement slides up after cards.

### Note

YoY means Year over Year, compared to the previous year.

---

## Section 03 - The Competitive Arena

### Original Slide

Page 3.

### Heading

The Competitive Arena

### Left Column

The Establishment

#### Competitor 1

Dar Soukkar: The Benchmark. 16th-century palace on Route de l'Ourika. Over 2,700 TripAdvisor reviews. The venue concierges recommend first.

#### Competitor 2

Palais Jad Mahal: 14 Years Established. Premium Hivernage palace. Positioned near La Mamounia and Royal Mansour.

#### Competitor 3

Bo Zin: 20 Years Iconic. Route de l'Ourika. 500 capacity. Exotic garden.

### Right Column

The Challenger - HABIBI August 2026

Bullet points:

- Rooftop with Atlas views.
- 250 covers.
- 20+ artists & live shows.
- Kat as artistic director.
- International positioning.
- Exceptional concept.

### Bottom Statement

Competitors have decades of established digital presence. To compete, HABIBI must enter the market at the exact same level of digital authority from Day One.

### Visual Direction

Two-column comparison. Left side grey cards. Right side highlighted white card with terracotta accent border.

### Website Adaptation

Create a competitive comparison section.

### Animation

- Left competitor cards stack in one by one.
- HABIBI challenger card enters with stronger emphasis.
- Bottom statement appears as a closing insight.

---

## Section 04 - The 5-Pillar Digital Engine

### Original Slide

Page 4.

### Heading

The 5-Pillar Digital Engine

### Intro Text

An integrated digital ecosystem built to scale and automate a modern hospitality brand.

### Pillars

#### Planning

The terrain & strategy.

#### Development

Websites & internal apps.

#### Visibility

SEO, AI search & Google reputation.

#### Growth

Social & community management.

#### Comm & Sales

Automated booking & outreach.

### Bottom Statement

Five components that build a hospitality brand online, working together so the HABIBI team can focus purely on the guest experience.

### Visual Direction

Central circular engine diagram with five surrounding icon nodes. Terracotta rings and soft shadows.

### Website Adaptation

Create an animated circular pillar system.

### Animation

- Central engine fades in.
- Circular rings draw in.
- Pillar nodes appear one by one around the circle.
- On hover, each pillar highlights and shows its short description.

---

## Section 05 - Strategic Foundation / Marketing Plan

### Original Source

Based on page 5, but split into its own dedicated slide.

### Heading

Strategic Foundation

### Subheading

The Marketing Plan before production begins.

### Purpose

This slide must make clear that the Marketing Plan is the strategic base before designing or coding anything.

### Content

Strategic Foundation (The Marketing Plan)

Bullet points:

- Comprehensive market analysis and competitor benchmarking.
- Defining brand positioning, unique selling propositions (USPs), and target audience personas.
- Developing a multi-channel marketing strategy (digital, PR, partnerships).
- Setting clear KPIs and a roadmap for launch and post-launch phases.

### Website Adaptation

Create a clean editorial slide, not a generic card layout.

Possible composition:

- Large Cormorant Garamond title on left.
- Strategic checklist or layered planning map on right.
- Use subtle turquoise and burnt orange accents.

### Animation

- Title appears first.
- Strategic layers reveal in sequence.
- Final KPI/roadmap line appears last.

---

## Section 06 - Website Phase 1 - The Digital Flagship

### Original Source

Based on page 5, but expanded into its own dedicated slide.

### Heading

Website Phase 1

### Subheading

The Digital Flagship for launch.

### Purpose

This slide must focus only on the main website build for launch.

### Content

The website is the central digital asset for HABIBI: the place where guests, concierges, agencies, and partners understand the concept, see the venue, trust the brand, and move toward booking.

Key points:

- Immersive premium design.
- Mobile-first experience.
- Venue and show presentation.
- Booking journey integration.
- SEO foundation from day one.
- English and French included.
- Built to be expandable into Phase 2.

### Website Adaptation

Create a full dedicated website slide.

Possible composition:

- Large editorial heading.
- Website mockup or browser frame.
- Sections of the website shown as layered panels: Home, Concept, Shows, Menu, Booking, Private Events, Contact.
- Optional iframe preview of the old `index2.html` only if useful as a motion/reference demo.

### Animation

- Browser mockup slides in.
- Website sections layer in.
- Booking flow line animates from interest to reservation.

---

## Section 07 - E-Commerce & Gift Cards

### Original Slide

Page 6.

### Heading

E-Commerce & Gift Cards (Website Phase 2)

### Card Title

E-Commerce & Gift Cards (Website Phase 2)

### Description

Guests buy experiences as gifts, generating revenue while the team is hosting, not computing.

### Bullet Points

- Automated email delivery
- Branded merchandise
- Signature spices
- Secure payment

### Bottom Note

A guest who buys a gift card introduces two more people to HABIBI.

### Visual Direction

Minimal section with one white card on the left and generous empty space. Card has shopping bag icon and terracotta bottom accent.

### Website Adaptation

Create a focused feature section with one main card and optional supporting visual on the right.

### Animation

- Card slides in from left.
- Empty right side can show subtle animated gift card mockup or e-commerce flow.

---

## Section 08 - Staff Training App

### Original Source

Mentioned as an optional capability on page 12, but missing as a full slide.

### Heading

Staff Training App

### Subheading

Internal knowledge, onboarding, and service consistency.

### Purpose

This slide must explain the value of the training app as an internal tool, not just a line item in the pricing table.

### Content

A private internal training app can help HABIBI maintain service quality as the team grows.

Possible modules:

- Brand standards.
- Guest experience rules.
- Show schedule and operational updates.
- Menu and allergy information.
- Reservation handling rules.
- Concierge and upselling scripts.
- Staff onboarding materials.
- Internal FAQs.
- Multilingual support if needed.

Business value:

- Faster onboarding.
- More consistent service.
- Less dependency on verbal training.
- Better alignment between management, floor team, reservations, and guest communication.
- Easier updates before and after launch.

### Website Adaptation

Create a dedicated internal systems slide.

Possible composition:

- App interface mockup.
- Staff roles as small connected nodes.
- Knowledge modules as cards.
- Clean black or off-white background with turquoise system accents.

### Animation

- App mockup appears first.
- Modules animate around it.
- Final line emphasizes consistency and training speed.

---

## Section 09 - Visibility: Dominating the Search Layer

### Original Slide

Page 7.

### Heading

Visibility

### Subheading

Dominating the Search Layer

### Supporting Line

If guests can't find you, they choose someone else.

### Layer 1

Local Search (Google Business Profile)

Description: The ultimate trust signal for concierges. Fully optimized profile, continually updated photos, and active Q&A management.

### Layer 2

GEO (Generative Engine Optimisation)

Description: Structured data ensuring HABIBI is the venue recommended by ChatGPT, Gemini, and Perplexity. A massive new channel most venues ignore.

### Layer 3

SEO (Search Engine Optimisation)

Description: Built into the page structure from day one. Keywords optimized around “premium dinner shows Marrakech”.

### Visual Direction

Stacked 3D cards on the left, explanatory text on the right.

### Website Adaptation

Create a layered search stack section.

### Animation

- Three stacked cards animate into place from bottom to top.
- Right-side descriptions appear linked to each layer.
- On hover, each layer can expand or highlight its matching description.

---

## Section 08 - Reviews as Business Intelligence

### Original Slide

Page 8.

### Heading

Reviews as Business Intelligence

### Process Cards

#### 1. Monitor

Continuous tracking of all Google Business Profile reviews.

#### 2. Respond

100% of reviews answered in a bespoke HABIBI voice, never templated.

#### 3. Alert

Any 1 or 2-star review triggers an instant automated email alert to the HABIBI manager for immediate damage control.

#### 4. Analyze

Monthly intelligence reports flag staff mentions, detect recurring themes, and benchmark against competitors.

### Bottom Statement

The insights go directly to management, so decisions on training and service are driven by real guest data.

### Visual Direction

Four vertical cards connected by terracotta arrows. Return arrow loops underneath.

### Website Adaptation

Create a horizontal process flow on desktop and stacked process on mobile.

### Animation

- Cards appear in order.
- Arrows draw from card to card.
- Bottom loop arrow animates last.

---

## Section 09 - Social Media & Community Cultivation

### Original Slide

Page 9.

### Heading

Social Media & Community Cultivation

### Left Checklist Card

All items have ON indicators.

Items:

- Strategy, content planning, and calendar management
- High-end copywriting and storytelling
- Graphic design for Posts, Stories, and Carousels
- End-to-end community management (TikTok & Instagram)

### Why It Matters

An inconsistent social presence signals to guests that nobody is minding the brand.

Weekly, high-quality activity builds trust before the booking.

### Right Visual

Instagram profile mockup with feed grid.

### Bottom Quote

“A guest who discovers HABIBI on social media feels an immediate and overwhelming desire to experience it in person.”

### Visual Direction

Checklist card on left, explanation in center, Instagram mockup on right, quote card at bottom.

### Website Adaptation

Create a three-part social section.

### Animation

- ON toggles switch on one by one.
- Instagram mockup slides in from right.
- Quote appears at bottom with soft emphasis.

---

## Section 10 - Three Channels That Convert Interest into Reservations

### Original Slide

Page 10.

### Heading

Three Channels That Convert Interest into Reservations

### Card 1

01 - WhatsApp Concierge

Text: Instant replies in English, French, Spanish, and Arabic. 24/7 coverage. Upsells champagne, private dining, and extras. Human-supervised at all times.

### Card 2

02 - Social Automation

Text: Keyword-triggered conversation flows inside Instagram DMs. Runs 24/7 without staff involvement. Routes inquiries directly to the booking flow.

### Card 3

03 - Outreach & Partnerships

Text: Handled via [communication@habibi-marrakech.com](mailto\:communication@habibi-marrakech.com). Direct pitching to hotel concierges, travel agencies, and tour operators. End-to-end influencer management (identification, negotiation, tracking).

### Visual Direction

Three tall white cards with terracotta icons.

### Website Adaptation

Create three service cards.

### Animation

- Cards reveal one by one.
- Icons can animate subtly on hover.

---

## Section 11 - Every Direct Message is an Open Door

### Original Slide

Page 11.

### Heading

Every Direct Message is an Open Door

### Initial Message Card

Guest messages HABIBI  asking for a table.

### Without Automation Path

A1: Message waits in inbox. A2: No reply for hours. A3: Guest books elsewhere. Revenue Lost.

### With Kensho Automation Path

B1: Instant AI qualification. B2: System replies in guest's language. B3: Links directly to booking flow. B4: Reservation Confirmed at 9:01 PM. Revenue Captured.

### Bottom Statement

The system is trained in sales. No inquiry is ever left waiting.

### Visual Direction

Flowchart with two paths. Grey/red negative path at top. Terracotta/green positive path at bottom.

### Website Adaptation

Create an animated split-flow section.

### Animation

- Initial message appears first.
- Without Automation path animates slowly and ends with red lost card.
- With Kensho Automation path animates faster and ends with green confirmation card.
- Bottom statement appears last.

---

## Section 14 - Phase Roadmap - Phase 1 and Phase 2

### Original Source

Derived from pages 5, 6, 12, and 15.

### Heading

Phase Roadmap

### Subheading

Build what is needed first. Expand once the foundation is live.

### Purpose

This slide must clearly separate Phase 1 and Phase 2 so the client understands what is immediate, what is optional, and what comes later.

### Phase 1 - Launch Foundation

Includes:

- Marketing Plan.
- Website Phase 1.
- Booking journey integration.
- SEO foundation.
- Google Business Profile setup / optimization.
- Review monitoring system.
- Core social and communication structure.

Goal: Prepare HABIBI to launch with digital authority, clarity, and conversion infrastructure.

### Phase 2 - Expansion Layer

Includes:

- E-commerce and gift cards.
- Branded merchandise.
- Signature spices.
- Private event inquiry flows.
- Staff Training App.
- More advanced automation and reporting.

Goal: Turn the digital infrastructure into a revenue and operations system.

### Website Adaptation

Create a clean two-phase roadmap.

Possible composition:

- Split screen: Phase 1 left, Phase 2 right.
- Timeline line through both phases.
- Phase 1 more immediate and grounded.
- Phase 2 more expandable and future-facing.

### Animation

- Phase 1 reveals first.
- Connector line moves to Phase 2.
- Phase 2 reveals as expansion.

---

## Section 15 - Phase 1 Investment Architecture

### Original Slide

Page 12.

### Heading

Phase 1 Investment Architecture

### Subtitle

One-time strategic and developmental setups.

### Core Deliverables

#### Marketing Plan

Competitor, market, and SEO analysis. Recommended first step. Price: 290€

#### Website Phase 1

Full custom build, English & French included. Mobile-first booking engine. Price: 2,300€

#### Hosting & Maintenance

Billed annually. Includes 1TB bandwidth and backups. Price: 45€/month

### Optional Capabilities

#### Website Phase 2

E-Commerce Price: from 500€

#### Staff Training App

Price: from 900€

#### Launch Communication Plan

Price: from 450€

### Visual Direction

Large pricing table card. Clean rows with prices aligned right.

### Website Adaptation

Create a pricing architecture table.

### Animation

- Table fades in.
- Rows appear one by one.
- Core deliverables and optional capabilities visually separated.

---

## Section 16 - Monthly Partnership Matrix

### Original Slide

Page 13.

### Heading

Monthly Partnership Matrix

### Subtitle

Your dedicated marketing team for less than the cost of one employee.

### Plan 1

Visibility 417€/month Setup fee 250€

Includes:

- SEO, GEO, Google Business Profile
- System for reporting and monitoring
- Responses to every review

### Plan 2

Growth Plan 770€/month

Includes:

- Everything in the Visibility Plan, plus:
- Social media strategy
- Content planning
- Graphic design
- Community management

### Plan 3

Growth + Comm & Sales Recommended 1,200€/month Setup from 650€

Includes:

- Everything in the Growth Plan, plus:
- WhatsApp Concierge (24/7 instant replies)
- Social Automation (Instagram DM flows)
- B2B Email Outreach (Hotels, agencies)
- Influencer search & collaboration management
- Human-supervised multilingual communications

### Visual Direction

Three pricing cards. Third card is larger/highlighted with terracotta border and recommended badge.

### Website Adaptation

Create pricing cards section.

### Animation

- Cards reveal left to right.
- Recommended card scales slightly or glows softly.
- Price text should be clear and premium.

### Note

The plan name “Growth + Comm & Sales” could be improved to “Growth + Communication & Sales” or “Growth + Communication & Sales System”.

---

## Section 17 - Not an External Agency. Your Marketing Team.

### Original Slide

Page 14.

### Heading

Not an External Agency. Your Marketing Team.

### Proof Cards

#### Hospitality Native

Graduated from Les Roches University, Switzerland (One of the top global hospitality schools).

#### Operations Tested

Years of on-the-ground, 5-star hotel operational experience across Europe and the United States.

#### Digital Masters

Strategy years specialized exclusively in digital marketing for the luxury hospitality sector.

#### Tech Certified

Masters in AI and Automation. Multiple Google Certifications.

### Bottom Statement

We understand exactly what a concierge needs to recommend a venue, and what a guest expects before booking. We speak hospitality.

### Visual Direction

Four proof cards in a 2x2 grid. Terracotta headings and icons. Bottom terracotta statement bar.

### Website Adaptation

Create a trust / credentials section.

### Animation

- Heading appears first.
- Cards reveal in grid sequence.
- Bottom statement bar slides in from bottom.

### Note

Check exact claim wording before publishing. “Masters in AI and Automation” should only be used if it is accurate and defendable.

---

## Section 18 - Final Call to Action

### Original Slide

Page 15.

### Heading

August 2026 is closer than it looks.

### Subtitle

Every week without a digital presence is a week the competition gains ground.

### Three Steps

#### Step 1

Confirm scope & language priorities (Spanish/Arabic additions, Training app decision).

#### Step 2

Execute the Marketing Plan (290€). This provides both teams the same strategic picture before any code is written.

#### Step 3

Production, digital real estate setup, and implementation begin immediately.

### CTA Button

hospitality.kenshovisual.com

### Visual Direction

Horizontal 3-step timeline with large numbered circles and terracotta connecting line. CTA button at bottom.

### Website Adaptation

Create a closing CTA section with animated timeline.

### Animation

- Heading fades in.
- Timeline line draws from left to right.
- Numbered circles appear in sequence.
- CTA button appears last.

---

# Main Corrections Before Website Build

## Text Corrections

1. Slide 10 heading currently repeats “into Reservations”. Correct to: Three Channels That Convert Interest into Reservations

2. Use consistent naming: Growth + Communication & Sales or Growth + Communication & Sales System

3. Avoid writing “AI” too visibly if the client-facing strategy is to keep the proposal focused on systems, communication, sales, and guest experience.

4. Check whether “Masters in AI and Automation” is factually correct before publishing.

5. Consider changing “not computing” on Slide 6 to “not processing admin tasks” or “not handling manual admin” because “computing” sounds slightly unnatural.

---

# Codex Prompt for VS Code

Use this prompt with Codex in VS Code together with the PDF and exported slide images.

```text
You are building a premium interactive presentation experience for HABIBI Marrakech based on the attached PDF presentation and slide screenshots.

IMPORTANT:
The attached PDF is ONLY a structural and informational reference.
The original presentation design is visually weak and should NOT be recreated literally.

You must reinterpret the presentation completely with a far more premium, editorial, cinematic, luxury hospitality design direction.

The final result should feel like:
- A luxury keynote presentation.
- An interactive investor deck.
- A cinematic digital story.
- A high-end hospitality growth presentation.

NOT like:
- A normal scrolling website.
- A SaaS landing page.
- A PowerPoint exported to HTML.
- A generic agency template.

Presentation System:
- Slides/scenes should transition elegantly.
- Use minimal navigation arrows fixed at the bottom.
- Add slide progress indicators.
- Add current slide numbering like 04 / 15.
- Add navigation dots.
- Presentation should feel guided and intentional.
- Smooth cinematic transitions between sections.

Typography:
- Use Cormorant Garamond for all major titles and editorial headings.
- Use Inter for all body text and UI.

Color Palette:
- White and off-white sections.
- Black and charcoal inverted sections.
- Ocean turquoise accents.
- Burnt dark orange accents.

Visual Style:
- Editorial luxury hospitality aesthetic.
- Architectural compositions.
- Strong negative space.
- Sophisticated typography.
- Cinematic layering.
- Refined asymmetrical layouts.
- Minimal but visually powerful.
- No generic boxed template feeling.
- No startup SaaS aesthetics.
- No excessive glowing AI visuals.

The PDF should only guide:
- Information hierarchy
- Messaging
- Narrative structure
- Content blocks

Do NOT copy:
- Original layouts
- Original card styling
- Original spacing
- Original typography balance
- Original visual composition

Use the PDF and screenshots as visual and content reference only. Do not create a literal slide deck in HTML. Convert each slide into a premium animated website section.

Tech stack:
- HTML
- Tailwind CSS
- JavaScript
- GSAP ScrollTrigger for animations
- Optional Lenis smooth scroll if already available in the project

Build one new page only. Keep all CSS and JS scoped to this page to avoid affecting the rest of the site.

Website direction:
- Premium hospitality consulting style
- Light grey / off-white backgrounds
- Dark charcoal text
- Terracotta / burnt orange accent color
- Rounded white cards
- Soft shadows
- Subtle depth
- Smooth scroll animations
- Real HTML text, not text inside images
- Fully responsive desktop and mobile

Content structure:
1. Hero: HABIBI Marrakech, The Digital Infrastructure & Growth Blueprint - 2026, Prepared by Kensho Hospitality.
2. Market stats: 17.4M Morocco Visitors, 4M Marrakech Arrivals, 72% Average Hotel Occupancy, #6 Global Destination, plus bottom strategic statement.
3. Competitive Arena: The Establishment vs The Challenger - HABIBI August 2026.
4. The 5-Pillar Digital Engine: Planning, Development, Visibility, Growth, Comm & Sales.
5. Strategy & Website: Strategic Foundation and Website Digital Flagship cards.
6. E-Commerce & Gift Cards: Website Phase 2 feature card.
7. Visibility: Local Search, GEO, SEO layered section.
8. Reviews as Business Intelligence: Monitor, Respond, Alert, Analyze process flow.
9. Social Media & Community Cultivation: ON checklist, why it matters, Instagram mockup, quote.
10. Three Channels That Convert Interest into Reservations: WhatsApp Concierge, Social Automation, Outreach & Partnerships.
11. Every Direct Message is an Open Door: split flow without automation vs with Kensho Automation.
12. Phase 1 Investment Architecture: pricing table with core deliverables and optional capabilities.
13. Monthly Partnership Matrix: Visibility, Growth Plan, Growth + Communication & Sales pricing cards.
14. Not an External Agency. Your Marketing Team: proof cards and bottom statement.
15. Final CTA: August 2026 is closer than it looks, 3-step timeline, CTA button hospitality.kenshovisual.com.

Important corrections:
- Correct the repeated heading from “Three Channels That Convert Interest into Reservations into Reservations” to “Three Channels That Convert Interest into Reservations”.
- Use “Growth + Communication & Sales” instead of “Growth + Comm & Sales” unless space is very limited.
- Keep the tone focused on hospitality, business growth, communication, sales, reputation, and digital infrastructure.
- Do not overuse the word AI visually.
- Do not invent new prices, claims, services, or numbers.

Animation requirements:
- Hero card slides in softly with blur.
- Metric cards reveal one by one and numbers can count up.
- Competitor cards stack in sequence.
- 5-pillar engine should have a central circular/radial animated layout on desktop and a stacked version on mobile.
- Review process arrows should animate in sequence.
- Social media toggles should turn ON one by one.
- DM automation section should animate two paths: slow negative path without automation, fast positive path with automation.
- Pricing cards should reveal left to right, with the recommended card slightly emphasized.
- Final CTA timeline line should draw from left to right.

Responsive rules:
- Desktop can use grids, radial diagrams, and horizontal flows.
- Mobile must stack cleanly with readable text and no horizontal overflow.
- Avoid fixed slide dimensions.
- Avoid tiny text.
- Do not crop important content.

Deliver clean, readable code. Keep class names understandable. Do not change unrelated project files.
```

---

# Suggested Asset Preparation

Export the PDF pages as individual images and place them here:

```text
/assets/habibi-reference/slide-01.png
/assets/habibi-reference/slide-02.png
/assets/habibi-reference/slide-03.png
/assets/habibi-reference/slide-04.png
/assets/habibi-reference/slide-05.png
/assets/habibi-reference/slide-06.png
/assets/habibi-reference/slide-07.png
/assets/habibi-reference/slide-08.png
/assets/habibi-reference/slide-09.png
/assets/habibi-reference/slide-10.png
/assets/habibi-reference/slide-11.png
/assets/habibi-reference/slide-12.png
/assets/habibi-reference/slide-13.png
/assets/habibi-reference/slide-14.png
/assets/habibi-reference/slide-15.png
```

Use the slide images only as references while rebuilding the website in real HTML.

---

# Final Positioning Summary

HABIBI is entering a competitive Marrakech hospitality market where established venues already have strong digital authority. The proposal positions Kensho Hospitality not as an external agency, but as HABIBI's digital growth team, responsible for strategy, website infrastructure, visibility, social media, review intelligence, guest communication, reservation conversion, and launch support.

The website version should make this feel stronger than a PDF: clearer, more premium, more animated, more persuasive, and easier for the client to understand.

