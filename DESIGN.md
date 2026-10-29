---
name: Executive Engineering Folio
colors:
  surface: '#f8f9ff'
  surface-dim: '#d0dbed'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dee9fc'
  surface-container-highest: '#d9e3f6'
  on-surface: '#121c2a'
  on-surface-variant: '#45464d'
  inverse-surface: '#27313f'
  inverse-on-surface: '#eaf1ff'
  outline: '#75777e'
  outline-variant: '#c5c6ce'
  surface-tint: '#525e7d'
  primary: '#000a24'
  on-primary: '#ffffff'
  primary-container: '#14213d'
  on-primary-container: '#7c89aa'
  inverse-primary: '#b9c6ea'
  secondary: '#0051d5'
  on-secondary: '#ffffff'
  secondary-container: '#316bf3'
  on-secondary-container: '#fefcff'
  tertiary: '#000e0b'
  on-tertiary: '#ffffff'
  tertiary-container: '#002721'
  on-tertiary-container: '#049a87'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d9e2ff'
  primary-fixed-dim: '#b9c6ea'
  on-primary-fixed: '#0d1b36'
  on-primary-fixed-variant: '#3a4664'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#83f6e0'
  tertiary-fixed-dim: '#65dac4'
  on-tertiary-fixed: '#00201b'
  on-tertiary-fixed-variant: '#005046'
  background: '#f8f9ff'
  on-background: '#121c2a'
  surface-variant: '#d9e3f6'
typography:
  display:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.025em
  display-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system establishes a high-signal, recruiter-optimized portfolio and interactive curriculum vitae for Noraze Khan. The aesthetic combines clean corporate minimalism with modern engineering clarity. The visual language conveys competence, precision, and architectural discipline—qualities vital for software engineering internships.

The experience is distraction-free, scannable, and rapid to digest for technical recruiters and hiring managers reviewing profiles in 30 seconds or less. Structural hierarchy relies on intentional typographic scale and restrained color placement rather than ornamental graphics.

## Colors
The color palette prioritizes high-contrast legibility, accessible content grouping, and professional warmth against an off-white canvas:

- **Deep Navy Blue (`#14213D`)**: Serves as the primary anchor for dominant structural headings, brand identity, navigation titles, and key anchors.
- **Professional Blue (`#2563EB`)**: Applied strictly to primary actions, interactive states, active navigation pills, and verified links.
- **Teal Accent (`#0F9D8A`)**: Reserved for technical badges, status indicators (e.g., "Available for Summer 2025"), key achievements, and metric callouts.
- **Dark Slate (`#1F2937`)**: The standard text color for body paragraphs, bullet points, and secondary metadata, avoiding harsh true blacks.
- **Light Gray Canvas (`#F5F7FA`)**: The base background wash that provides subtle separation against container elements.
- **Pure White (`#FFFFFF`)**: Card surfaces, sidebars, and elevated modular sheets.
- **Subtle Border Rule (`#E5E7EB`)**: Structural hairpins and container dividers.

## Typography
The system employs `Inter` universally to balance mechanical rigor with optical legibility. 

Tight negative tracking is enforced on large headlines (`-0.025em` down to `-0.01em`) to create dense, impactful title locks. Body copy uses standard tracking and generous line heights (`1.5` to `1.6`) to prevent eye fatigue when reading lengthy technical project summaries or course catalogs. Uppercase variants are reserved exclusively for `label-sm` technical badges, section eyebrow tags, and metadata captions.

## Layout & Spacing
The layout follows a centered max-width model (max 1200px) structured on an 8pt spatial grid:

- **Desktop (1024px+)**: 12-column layout with 24px gutters and 32px margins. Employs a persistent 4-column profile and executive meta sidebar alongside an 8-column main timeline for work experience, engineering projects, and research.
- **Tablet (768px - 1023px)**: 8-column grid with 20px gutters and 24px margins. Sidebar shifts to a top summary card.
- **Mobile (< 768px)**: Single-column linear layout with 16px horizontal margins. Multi-column metric blocks stack vertically to maintain full readability.

## Elevation & Depth
Depth is created using crisp border contours paired with diffuse, low-opacity ambient shadows:

- **Flat / Canvas (Level 0)**: Background tone (`#F5F7FA`) with no elevation.
- **Resting Card (Level 1)**: White background (`#FFFFFF`), solid border `1px solid #E5E7EB`, ambient shadow `0 1px 3px 0 rgba(20, 33, 61, 0.04), 0 1px 2px -1px rgba(20, 33, 61, 0.04)`.
- **Interactive Hover (Level 2)**: Applied to project cards and clickable list items. Border shifts to `rgba(37, 99, 235, 0.3)`, translateY `-2px`, shadow `0 8px 16px -4px rgba(20, 33, 61, 0.08), 0 4px 6px -2px rgba(20, 33, 61, 0.04)`.
- **Overlays & Modals (Level 3)**: Resume previewers and code snippet drawers. Shadow `0 20px 25px -5px rgba(20, 33, 61, 0.12), 0 8px 10px -6px rgba(20, 33, 61, 0.06)`.

## Shapes
The design system uses a subtle, restrained radius approach (`roundedness: 1`). Containers, buttons, cards, and input fields use an initial radius of `0.25rem` (4px), while larger card containers step up to `0.5rem` (8px). 

This sharp, slightly softened aesthetic preserves the disciplined geometry expected in software documentation and enterprise tooling, avoiding informal bulbous curves while removing harsh geometric points. Full pill rounding (`9999px`) is permitted exclusively for skill chips and availability status tags.

## Components

### Buttons
- **Primary Action (e.g., Download Resume, Contact)**: Background `#2563EB`, text `#FFFFFF`, border-radius `0.375rem`, font-weight `600`, height `40px`, padding `0 16px`. Hover state: background `#1D4ED8`, elevation Level 2.
- **Secondary / Ghost (e.g., View Code, Live Demo)**: Background transparent, border `1px solid #E5E7EB`, text `#14213D`. Hover: border-color `#14213D`, background `#F8FAFC`.

### Chips & Badges
- **Technical Skills (Languages, Frameworks)**: Background `#F1F5F9`, border `1px solid #E2E8F0`, text `#1F2937`, size `label-sm`, padding `4px 10px`, border-radius `9999px`.
- **Status / Accent Tag**: Background `rgba(15, 157, 138, 0.1)`, border `1px solid rgba(15, 157, 138, 0.3)`, text `#0F9D8A`, font-weight `600`.

### Cards (Project & Experience)
- Surface `#FFFFFF`, border `1px solid #E5E7EB`, border-radius `0.5rem`, padding `24px`. Internal layouts follow structured zones: header (role/title + date badge), description body, and bottom tag array for the tech stack used.

### Timeline List
- Left vertical rule `2px solid #E5E7EB`. Timeline node markers are `10px` circles with `2px solid #FFFFFF` and fill `#2563EB`. Content margin-left `24px` from axis.

### Form Inputs & Contact Fields
- Base background `#FFFFFF`, border `1px solid #D1D5DB`, border-radius `0.375rem`, padding `10px 14px`, text `#1F2937`. Focus: border-color `#2563EB`, ring `3px rgba(37, 99, 235, 0.15)`.

### Code / Repo Metrics Callout
- Minimal inline monospace block with background `#F8FAFC`, border `1px solid #E2E8F0`, text `#14213D`, font family `monospace`, padding `2px 6px`, border-radius `3px`.