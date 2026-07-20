# Lure Encyclopedia Design System

Version 1.0

---

## Purpose

This design system defines the visual language for a custom Ghost theme for Lure Encyclopedia. It is intended to support long-form editorial content, encyclopedia-style reference pages, and a calm, trustworthy reading experience.

The system favors clarity over novelty. It should feel timeless, printed, and museum-like rather than trendy or app-like.

---

## Design Principles

The system is guided by the following principles:

- Editorial first
- Minimal and restrained
- Timeless rather than trendy
- Photography-led
- Accessible by default
- Fast and lightweight
- Consistent across pages and components

---

## Color Palette

### Design Tokens

- Paper: #F5F1E8
- Ink: #171614
- Body: #2D2B29
- Muted: #68635B
- Border: #D7CCB8
- Accent: #B08A42
- Hero: #0D0D0D

### Usage guidance

- Use Accent sparingly, primarily for links and selected states.
- Avoid heavy color blocking.
- Keep contrast strong enough for readability and accessibility.
- Do not use decorative gradients or bright highlights.

---

## Typography Scale

### Type families

- Headings: Cormorant Garamond
- Body: Source Sans 3
- Navigation: Source Sans 3, uppercase

### Scale

- H1: 64px
- H2: 48px
- H3: 36px
- H4: 28px
- Body: 20px
- Small: 16px

### Typographic behavior

- Establish hierarchy with size, weight, and spacing rather than color.
- Keep line lengths comfortable for reading.
- Use generous spacing around headings and paragraphs.
- Use uppercase only for navigation labels and short utility text.

---

## Spacing Scale

### Scale

- 8
- 16
- 24
- 40
- 64
- 96
- 128

### Guidance

- Use the spacing scale consistently across components.
- Favor generous whitespace around typography and imagery.
- Avoid cramped layouts, especially for long-form reading.

---

## Grid System

The layout should be simple, stable, and easy to read.

### Grid approach

- Mobile: single-column layout
- Tablet: two-column layout where helpful
- Desktop: wider editorial layout with generous margins

### Layout rules

- Keep content aligned to a strong vertical rhythm.
- Use clear content regions rather than dense multi-column layouts.
- Reserve multi-column layouts for supporting content only, not for long bodies of text.

### Recommended structure

- Page content should align within a central reading column.
- Supporting components such as sidebars or related content may use secondary columns.
- Maintain consistent gutters between major regions.

---

## Container Widths

Container widths should support both reading comfort and editorial presentation.

### Recommended widths

- Narrow reading container: suitable for long-form article content
- Standard content container: default for most page layouts
- Wide container: suitable for feature imagery and large editorial sections

### Guidance

- Keep article body content comfortably narrow for readability.
- Use wider containers only for sections that benefit from visual breadth.
- Avoid overly wide layouts that make reading feel disconnected.

---

## Buttons

Buttons should be understated and quiet, supporting the editorial tone.

### Button styles

- Primary: used for important calls to action
- Secondary: used for less prominent actions
- Text link: used for inline navigation and lightweight interaction

### Style guidance

- Use simple labels and clear intent.
- Keep button styling minimal and consistent.
- Avoid heavy fills, glossy effects, or sharp contrast.
- Maintain accessible contrast in all states.

### States

- Default
- Hover
- Focus
- Active
- Disabled

---

## Cards

Cards should feel like editorial tiles rather than product or app containers.

### Card purpose

Use cards for:

- Featured articles
- Entry summaries
- Topic highlights
- Related content

### Card characteristics

- Clean typography
- Clear hierarchy
- Minimal decoration
- Subtle border or separation
- Space around content for breathing room

### Content pattern

A card should generally include:

- Title
- Short summary
- Optional metadata
- Optional image

---

## Navigation

Navigation should feel calm, structured, and easy to scan.

### Header navigation

- Site title or brand name
- Primary navigation links
- Simple spacing and alignment
- Clear active state

### Footer navigation

- Secondary links
- Copyright or publication details
- Minimal visual weight

### Guidance

- Keep navigation simple and predictable.
- Avoid overly complex dropdown or mega-menu patterns.
- Maintain strong contrast and clear focus states.

---

## Hero Sections

Hero areas should introduce the publication with confidence and clarity.

### Hero content

A hero may include:

- A strong title
- Short supporting description
- Optional featured image
- Primary call to action when appropriate

### Visual approach

- Large whitespace around the hero
- Strong type hierarchy
- Photography that feels editorial and intentional
- Minimal decorative elements

### Guidance

- Hero sections should feel welcoming but not promotional.
- The focus should remain on the publication and the content it offers.

---

## Forms

Forms should be simple, legible, and unobtrusive.

### Form elements

- Labels
- Input fields
- Textareas
- Selects
- Buttons
- Helper text and error states

### Style guidance

- Use clear labels with generous spacing.
- Keep borders subtle and consistent.
- Ensure form elements remain accessible to keyboard and assistive technology users.
- Maintain strong contrast in both normal and error states.

---

## Tables

Tables should support structured information without becoming visually heavy.

### Style guidance

- Keep table borders minimal.
- Use clear column headings.
- Align text consistently.
- Allow sufficient padding for scanability.
- Avoid unnecessary color or decoration.

### Use cases

- Reference data
- Timeline content
- Comparison lists
- Structured editorial information

---

## Lists

Lists should support scanning and reading rather than visual clutter.

### List types

- Unordered lists for related items
- Ordered lists for sequential information
- Definition lists for terms and explanations

### Guidance

- Keep list spacing generous.
- Use simple bullets or numbers.
- Ensure nested lists remain easy to read.

---

## Image Treatment

Photography is a core part of the experience and should feel museum-quality.

### Image principles

- Use photography as a primary visual element.
- Prefer high-quality, well-lit imagery.
- Maintain consistent tone and color handling.
- Use generous negative space around images.
- Avoid excessive cropping or visual noise.

### Caption and presentation

- Pair images with concise captions when useful.
- Use images to support content rather than overwhelm it.
- Consider full-width or large-format presentation for feature imagery.

---

## Borders

Borders should be quiet and architectural.

### Border principles

- Use thin hairline borders rather than bold framing.
- Keep borders consistent across cards, panels, and sections.
- Use borders to create separation, not visual drama.
- Avoid heavy outlines or decorative corners.

---

## Icons

Icons should be simple, restrained, and functional.

### Usage guidance

- Prefer minimal line icons over elaborate pictograms.
- Use icons only when they add clarity.
- Keep icon style consistent across the interface.
- Avoid decorative or playful iconography.

---

## Motion

Motion should be subtle, purposeful, and unobtrusive.

### Motion principles

- Use transitions only to communicate interaction.
- Avoid decorative animation.
- Keep motion brief and low-impact.
- Respect reduced-motion preferences.

### Guidance

- Prefer instant feedback over animated effects.
- Motion should never distract from reading or content comprehension.

---

## Accessibility Requirements

Accessibility is a core requirement, not a later refinement.

### Required standards

- Use semantic HTML for structure and meaning.
- Ensure strong color contrast for text and interactive elements.
- Support keyboard navigation for all interactive components.
- Provide meaningful focus states.
- Provide alt text for informative images.
- Use clear heading hierarchy.
- Ensure forms, tables, and navigation are understandable and operable.
- Respect reduced-motion preferences.

### Content accessibility

- Write concise, clear, scannable content.
- Avoid relying on color alone to convey meaning.
- Ensure links and controls have descriptive labels.

---

## Component Vocabulary

The following reusable component categories should form the foundation of the theme:

- Navigation
- Hero
- Editorial card
- Archive list
- Image caption
- Pull quote
- Citation
- Timeline entry
- Article body section

These components should be assembled into pages rather than designed as one-off layouts.
