---
name: Clinical Clarity
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#3e4947'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#6e7977'
  outline-variant: '#bdc9c6'
  surface-tint: '#006a63'
  primary: '#005c55'
  on-primary: '#ffffff'
  primary-container: '#0f766e'
  on-primary-container: '#a3faef'
  inverse-primary: '#80d5cb'
  secondary: '#515f74'
  on-secondary: '#ffffff'
  secondary-container: '#d5e3fc'
  on-secondary-container: '#57657a'
  tertiary: '#005e3f'
  on-tertiary: '#ffffff'
  tertiary-container: '#007952'
  on-tertiary-container: '#99ffcd'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#9cf2e8'
  primary-fixed-dim: '#80d5cb'
  on-primary-fixed: '#00201d'
  on-primary-fixed-variant: '#00504a'
  secondary-fixed: '#d5e3fc'
  secondary-fixed-dim: '#b9c7df'
  on-secondary-fixed: '#0d1c2e'
  on-secondary-fixed-variant: '#3a485b'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
  title-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system establishes an authoritative, calm, and hyper-legible mobile interface for home medicine cabinet intelligence. Operating at the intersection of clinical precision and domestic utility, the interface prioritizes immediate comprehension under duress (e.g., late-night medication searches, caregiver handoffs, or urgent shelf-life checks).

### Design Philosophy
- **Clinical Calm:** Reassuring, sanitary, and composed. Avoid loud consumerist cues, gamification, or commercial clutter. The system feels like an institutional medical tool adapted for home reliability.
- **Urgent Readability:** Critical drug nomenclature, active chemical compounds ("salts"), and safety statuses are emphasized through distinct typographic contrast and dedicated container tags.
- **Strictly Non-Transactional:** Eliminate all e-commerce affordances (no carts, buy buttons, or numeric retail inventory counters). Focus exclusively on status awareness, safe storage, duplicate active ingredient prevention, and expiry intelligence.

### Design Movement
**Modern Material You (M3) Medical Variant:** Utilizing tonal elevation containers, pill-shaped tactile chips, structural floating surfaces, and standardized Material 3 ergonomics tailored for high-accessibility touch interactions on a 412x915dp Android viewport.

## Colors

The palette leverages deep medical teal as the primary anchor, balanced with clinical slate neutrals and a strict high-contrast traffic-light status architecture for immediate triage.

### Core Roles
- **Primary (`#0F766E`):** Deep Medical Teal. Represents authority, precision, and vital interactions. Used for primary FABs, prominent action buttons, active tab indicators, and key structural landmarks.
- **Primary Container (`#CCFBF1`):** Soft Mint Teal. Surface container backing for active states, highlighted drug categories, and focused states.
- **On-Primary (`#FFFFFF`):** High-contrast pure white text/icons placed over primary teal.
- **Secondary (`#475569`):** Slate. Applied to secondary metadata, auxiliary tools, and contextual salt explanations.
- **Background (`#F8FAFC`):** Clinical off-white canvas providing soft contrast behind elevated cards.
- **Surface (`#FFFFFF`):** Pure white for distinct cards, elevated dialogs, and bottom sheets.
- **Outline / Border (`#E2E8F0`):** Subtle slate edge definition separating white surface cards from the off-white canvas.

### Clinical Status System (Traffic-Light Triage)
Status indicators strictly pair color with a dedicated semantic container and icon to ensure complete accessibility:
- **Safe / In Stock:** 
  - Status Color: Emerald Green (`#10B981`)
  - Container Background: Soft Emerald (`#ECFDF5`)
  - Icon: Solid Circle Checkmark (`check_circle`)
  - Meaning: Valid, safe, active in home stock.
- **Attention / Expiring Soon / Duplicate Salt:**
  - Status Color: Warm Amber (`#F59E0B`)
  - Container Background: Soft Amber (`#FFFBEB`)
  - Icon: Warning Triangle (`warning`)
  - Meaning: Expiring within 30 days, duplicate active salt detected across multiple brands, or review required.
- **Critical / Expired:**
  - Status Color: Crimson Red (`#EF4444`)
  - Container Background: Soft Crimson (`#FEF2F2`)
  - Icon: Alert Octagon (`report` / `error`)
  - Meaning: Expired or unsafe for consumption; prompt disposal protocol.

## Typography

The typographic system utilizes **Plus Jakarta Sans** across all roles to combine clinical legibility with warm, modern clarity. 

### Late-Night Emergency Hierarchy
- **Primary Brand / Commercial Name:** Set in `title-lg` or `headline-sm` with bold weight (`600` or `700`) in Slate-900. It must be readable from an arm's length under low light.
- **Active Chemical Compound ("Salt"):** Displayed immediately beneath the brand name using `label-md` or `body-md` in Secondary Slate (`#475569`) with uppercase tracking or container styling (e.g., `PARACETAMOL 500mg`). This prevents accidental double-dosing across varied trade names.
- **Dosage & Form Factor:** Uses `label-sm` chips or monospace secondary labels to indicate delivery type (Tablet, Suspension, Inhaler) unambiguously.

## Layout & Spacing

Designed specifically around the **Android 412x915dp viewport** with an 8dp baseline grid and touch targets optimized for single-handed mobile reachability.

### Layout System
- **Canvas Margins:** 16dp (`1rem`) lateral margins ensure cards and list groups avoid bezel clip while maximizing readable surface area.
- **Column Grid:** 4-column fluid layout with 16dp gutters (`1rem`) for dense, legible mobile organization.
- **Vertical Rhythm:** 
  - Standard card spacing: 12dp to 16dp vertical margin.
  - Section headers: 24dp top margin, 8dp bottom margin to related groups.
- **Thumb Zone Ergonomics:** Core controls (Scanner FAB, Bottom Navigation, and Quick Filters) reside strictly within the lower 40% of the screen. Non-destructive contextual filters use horizontal scrolling chips above the content list.

## Elevation & Depth

In alignment with modern Material Design 3 and a sanitary medical aesthetic, visual elevation avoids heavy muddy drop shadows, relying instead on surface contrast and micro-borders.

### Surface Tiers
- **Canvas Level 0 (`#F8FAFC`):** Background layer.
- **Surface Level 1 (`#FFFFFF`):** Medicine list cards, search bars, and inventory tiles. Enforced with a 1px crisp outline (`#E2E8F0`) and a diffused ambient shadow: `0px 1px 3px rgba(15, 23, 42, 0.04), 0px 1px 2px rgba(15, 23, 42, 0.02)`.
- **Surface Level 2 (`#FFFFFF`):** Floating Action Button (FAB) and Quick Action trays. Ambient elevation: `0px 4px 12px rgba(15, 118, 110, 0.15)`.
- **Surface Level 3 (`#FFFFFF`):** Modal Bottom Sheets and Drug Interaction Drawers. Rendered over a dimmed scrim (`rgba(15, 23, 42, 0.45)`) with an ambient top-diffusion: `0px -4px 20px rgba(15, 23, 42, 0.08)`.

### Border Integrity
Every white card on the off-white canvas must use the subtle slate outline (`1px solid #E2E8F0`) to ensure absolute edge definition on low-brightness mobile screens.

## Shapes

The shape hierarchy establishes a friendly yet structured handheld environment with unified corner geometries.

- **Cards & Surface Panels:** 16dp corner radius (`rounded-lg`), providing a clean, contained silhouette for medicine grouping.
- **Status Pills & Active Salt Chips:** Full capsule / pill radius (`9999px`) to visually reinforce the physical medicine/capsule metaphor.
- **Buttons & Input Fields:** 12dp to 16dp corner radius for comfortable touch ergonomics.
- **Floating Action Button (FAB):** Material 3 standard 16dp rounded box or extended pill for tactile certainty.
- **Modal Bottom Sheets:** 24dp rounded top edges (`rounded-t-2xl`) with flat bottom anchoring.

## Components

### 1. Medicine Inventory Cards
- **Structure:** Pure white surface (`#FFFFFF`), 1px `#E2E8F0` border, 16dp rounded corners, 16dp internal padding.
- **Header:** Large Trade Brand Name (`title-md` / `title-lg`), trailing with the Traffic-Light Status Pill.
- **Sub-header:** Prominent Active Chemical Compound / Salt container in secondary slate text with light gray fill (`#F1F5F9`) to immediately expose compound equivalencies.
- **Expiry Row:** Distinct expiry indicator using status color tokens (e.g., Crimson text `Expired: Oct 2023` or Amber text `Expires in 14 days`).
- **Strict Rule:** Never show stock quantities as retail items (e.g., "12 in stock" or "$14.99"). Instead use qualitative status badges: `In Safe Stock`, `Check Salt Duplicate`, or `Disposal Recommended`.

### 2. Traffic-Light Status Chips (Pills)
- **Safe State:** `#10B981` text & `check_circle` icon over `#ECFDF5` container.
- **Warning State:** `#F59E0B` text & `warning` icon over `#FFFBEB` container.
- **Critical State:** `#EF4444` text & `report` icon over `#FEF2F2` container.
- Height: 28dp; Padding: 4dp vertical, 10dp horizontal; Shape: Pill (`9999px`).

### 3. Floating Action Button (FAB)
- **Primary Function:** AI Medicine Box Scanner / Barcode / Prescription Lens.
- **Specs:** 56x56dp (or Extended 56dp height), colored in Primary Deep Teal (`#0F766E`) with pure white icon (`#FFFFFF`), anchored 16dp above the bottom navigation bar on the right.
- Ambient teal shadow gives physical prominence without visual harshness.

### 4. Bottom Navigation Bar
- Height: 80dp; Background: `#FFFFFF` with 1px `#E2E8F0` top border.
- 3 to 4 core navigation destinations: `Cabinet` (Inventory), `Salt Checker` (Interaction & Duplicate engine), `History`, and `Safety Guide`.
- Active item uses Primary Container pill (`#CCFBF1`) around primary teal icon (`#0F766E`).

### 5. Modal Bottom Sheets (Drug Details & Warnings)
- Drag handle: 32x4dp pill in Slate-300 (`#CBD5E1`).
- Contains high-density information: Active Salt contraindications, duplicate medicine alerts (e.g., *"You have 2 other medications containing Paracetamol"*), storage condition recommendations, and disposal guidelines.

### 6. Search & Quick Filters
- Clean input field: `#FFFFFF` fill, 1px `#E2E8F0` border, 48dp height with leading search icon and voice/camera quick-triggers.
- Category horizontal filter pills: `All Items`, `Pain Relief`, `Antibiotics`, `Expiring First`, `Pediatric Safe`.