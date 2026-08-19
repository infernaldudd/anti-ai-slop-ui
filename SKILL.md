---
name: anti-ai-slop
description: Anti-AI-Slop UI design — avoid generic AI frontend patterns, build product-derived visual systems. Use when designing or implementing websites, dashboards, desktop apps, landing pages, or other user interfaces.
---

# Anti-AI-Slop UI Design Skill

## Purpose

When designing or implementing websites, dashboards, desktop apps, landing pages, or other user interfaces, produce work that feels intentionally designed by a competent product designer rather than generated from common AI frontend patterns.

Do not blindly optimise for "modern", "clean", or "beautiful". Those words frequently produce the same generic AI aesthetic.

The interface should derive its visual language from the actual product, audience, content, and use case.

## Core Principle

Before writing UI code, determine:

1. What is this product?
2. Who actually uses it?
3. What actions matter most?
4. What information deserves visual priority?
5. What existing products, industries, physical objects, editorial styles, or interfaces could provide relevant visual inspiration?
6. What would make this interface recognisable if the logo were removed?

Build a visual system from those answers.

Do not start from a generic SaaS template and replace the text.

## Avoid Generic AI UI Patterns

Do not use these by default:

* Harsh or unnecessary gradients
* Purple/blue gradient backgrounds
* Purple-and-black "AI startup" palettes
* Neon glows
* Radial glowing orbs
* Decorative blurred blobs
* Dot-grid backgrounds
* Rainbow colouring
* Excessive pastel palettes
* Pure white everywhere without tonal hierarchy
* Excessive drop shadows
* Glassmorphism
* "Liquid glass" purely for decoration
* Excessively rounded cards
* Pills for every control
* Floating cards inside floating cards
* Bento grids simply because content exists
* Three identical feature cards in a row
* Formulaic three-tier pricing sections
* Huge hero text followed by three cards
* Decorative terminal windows
* Coloured strips on the left side of cards
* Sparkle icons
* Animated arrows
* Excessive hover animations
* Emojis used as product icons
* Checkmarks as the default bullet style
* Generic icon-heavy interfaces

Avoid Lucide icons as the automatic choice. Use an icon library only when icons genuinely improve comprehension. Prefer product-specific symbols, simple custom SVGs, text labels, or platform-native conventions where appropriate.

## Typography

Do not automatically use:

* Inter
* Geist
* Space Grotesk

Choose typography based on the product's character and readability requirements.

Establish deliberate hierarchy through:

* font family
* weight
* size
* line height
* tracking
* spacing
* contrast

Do not compensate for weak hierarchy by putting everything inside cards.

Large text is not automatically good typography.

## Layout

Prefer composition over component repetition.

Not every section needs: heading → subtitle → 3 cards

Not every piece of information needs its own rounded rectangle.

Use whitespace, alignment, typography, dividers, grouping, density, scale and hierarchy before introducing containers.

Vary layouts when the content warrants it.

Allow important elements to dominate.

Dense professional software can be dense. Consumer software can be simple. Creative software can be unconventional.

The product determines the layout.

## Copywriting

Avoid stereotypical AI marketing language.

Especially avoid constructions such as:

* "It's not X. It's Y."
* Excessive em dashes

Avoid vague phrases such as:

* "supercharge your workflow"
* "unlock your potential"
* "seamless experience"
* "revolutionise the way you…"
* "next-generation"
* "powerful yet simple"
* "built for the future"
* "everything you need"
* "work smarter, not harder"

Write specific copy describing what the product actually does.

Bad: "Transform the way you work with our powerful AI platform."

Better: "Review 600-page contracts and surface clauses that differ from your playbook."

Specificity is preferable to hype.

## Product Authenticity

Whenever possible, show the actual product.

For landing pages, prefer:

* real interface previews
* interactive demonstrations
* realistic data
* actual workflows
* meaningful screenshots
* before/after states
* concrete examples

Do not hide a weak product behind abstract marketing graphics.

Use realistic content rather than endless placeholders such as John Doe, Acme Inc., Project Alpha, example@email.com.

Create believable domain-specific data.

## Interaction Design

Interactions should explain state and consequence.

Implement where appropriate:

* loading states
* skeleton states
* empty states
* error states
* disabled states
* success feedback
* keyboard focus
* responsive behaviour
* overflow handling
* long-content handling

Animations must communicate something.

Do not animate elements merely to make the interface appear expensive.

Micro-interactions should be restrained and fast.

## Visual Identity

Before implementation, establish a small design direction.

Define:

* visual character
* typography
* colour logic
* spacing system
* border treatment
* corner treatment
* icon strategy
* motion strategy
* information density

Make at least one deliberate visual decision that distinguishes the product from a generic SaaS template.

Examples might include:

* unusually strong typography
* editorial composition
* technical/instrument-panel density
* physical-product-inspired controls
* monochromatic restraint
* strong grid system
* unusual navigation
* domain-specific visualisation
* bespoke illustration
* intentionally square geometry
* platform-native styling

Do not combine all of these. Pick a coherent direction.

## Colour

Colour should have a reason.

Use it to communicate: hierarchy, state, category, action, brand identity.

Do not use colour simply because an empty area looks boring.

Avoid defaulting to purple.

Ensure adequate contrast and accessibility.

## Components

Create components because behaviour or structure repeats, not merely because componentisation is possible.

Avoid turning every 20-line visual fragment into an abstraction.

Shared components should preserve a coherent design language without making every section visually identical.

## Real Application Requirements

For production-oriented applications, account for:

* responsive layouts
* accessibility
* keyboard navigation
* semantic HTML
* loading behaviour
* failure behaviour
* realistic content lengths
* touch targets
* reduced-motion preferences
* dark/light environments where appropriate
* performance
* mobile behaviour

For public websites, include appropriate legal/navigation surfaces such as Privacy Policy and Terms where relevant.

Do not create fake testimonials or fabricated customer logos.

## Design Process

When asked to build a substantial interface:

1. **Understand** — Identify the product, users and primary workflow.
2. **Choose a Direction** — Privately establish a coherent visual direction before coding. Do not dump a lengthy design essay on the user unless requested.
3. **Build the Hierarchy** — Establish page structure and information hierarchy before decoration.
4. **Implement** — Create the actual functional interface.
5. **Inspect** — Look at the rendered result whenever tooling permits. Do not assume valid code means good design.
6. **Critique** — Ask:
   * Does this look like a template?
   * Is every section a rounded card?
   * Did I default to familiar AI-design clichés?
   * Is the hierarchy obvious without colour?
   * Is there unnecessary decoration?
   * Does the design make sense for this specific product?
   * Would another AI likely generate almost the same page from a vague prompt?
   * Is the product itself visible?
   * Are important states implemented?
   * Does it work at realistic content lengths?
7. **Revise** — If the result looks generic, redesign it rather than merely changing colours.

## Existing Projects

When modifying an existing application, respect its established design language.

Do not unnecessarily replace a coherent existing UI with this skill's preferences.

First inspect: existing components, spacing, typography, colours, navigation, interaction conventions.

Improve inconsistencies while preserving intentional design decisions.

## User References

If the user supplies screenshots, mock-ups, Figma references, existing websites, sketches, or brand guidelines, treat them as higher-priority visual evidence.

Analyse their composition rather than superficially copying colours.

Pay attention to: density, proportions, hierarchy, typography, alignment, borders, navigation, control sizing, whitespace, interaction model.

## Final Rule

Never ask: "How can I make this look modern?"

Ask: "What should this particular product look and feel like, and why?"

A restrained, functional, distinctive interface is preferable to an impressive-looking collection of current design trends.

If the first result looks "AI generated", iterate before considering the design finished.

---

*Skill text authored with ChatGPT GPT-5.6 Sol High and DeepSeek V4 Flash (OpenCode).*