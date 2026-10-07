---
name: ETAM v6 Platform Design System
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#434655'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#4b41e1'
  on-secondary: '#ffffff'
  secondary-container: '#645efb'
  on-secondary-container: '#fffbff'
  tertiary: '#006242'
  on-tertiary: '#ffffff'
  tertiary-container: '#007d55'
  on-tertiary-container: '#bdffdb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#e2dfff'
  secondary-fixed-dim: '#c3c0ff'
  on-secondary-fixed: '#0f0069'
  on-secondary-fixed-variant: '#3323cc'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
  status-warning: '#F59E0B'
  status-danger: '#F43F5E'
  role-pembina: '#10B981'
  role-ketua: '#8B5CF6'
  role-wakil: '#3B82F6'
  role-sekretaris: '#EAB308'
  role-bendahara: '#EC4899'
  role-dokumentasi: '#F97316'
  role-anggota: '#64748B'
  surface-page: '#F8FAFC'
  surface-card: '#FFFFFF'
  surface-subtle: '#F1F5F9'
  border-subtle: '#E2E8F0'
  border-strong: '#CBD5E1'
typography:
  display-code:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: 4px
  display-code-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: 3px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
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
    letterSpacing: 0.2px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.4px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.5px
  caption-stamp:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 15px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-md: 1.5rem
  gutter-lg: 2rem
  margin: 1rem
  margin-md: 1.5rem
  margin-lg: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style

This design system defines the digital interface for extracurricular management at SMP Negeri 10 Samarinda. Built for Indonesian educational workflows, it balances official institutional decorum (*bahasa santun*, structural clarity, and administrative reliability) with the high-energy, collaborative spirit of student leadership and school clubs (pramuka, seni, olahraga, sains, and paskibra).

The design style combines **Corporate / Modern** structure with **Tactile Educational Utility**:
- **Clarity over ornamentation:** Crisp visual boundaries, dense data layouts, and high legibility suitable for outdoor smartphone presensi, classroom projectors, and formal printed export reports (Kop Surat).
- **Institutional Dignity:** Rooted in deep royal blues and maritime slate tones honoring the Mahakam riverside heritage and school identity, balanced with vibrant role badges that make student council and club structures intuitive at a glance.
- **Mobile-First Realism:** Optimized for touch ergonomics, instant visual validation for geotagged watermarked attendance, and clear role distinctions within student organizations.

## Colors

The palette establishes a high-contrast, accessible environment calibrated for both indoor administrative oversight and field operations under daylight.

### Functional Roles
- **Primary (`#2563EB`)**: Royal Blue anchors standard interactive triggers, navigation bars, primary buttons, and institutional branding headers.
- **Secondary (`#4F46E5`)**: Indigo supplies depth for elevated navigation, active tab pill indicators, and analytical charts.
- **Tertiary (`#10B981`)**: Emerald represents verified attendance (*Hadir*), signed credentials, and positive verification states.
- **Neutral (`#0F172A`)**: Deep Slate drives base body typography and solid dark chrome, avoiding muddy pure blacks.

### Organizational Structure (Bagan Pengurus)
To map directly to the traditional Indonesian school committee tree (*Bagan Struktur Organisasi*), specific named accents govern role tags, card borders, and hierarchical markers:
- **Pembina / Pelatih**: Emerald Green (`#10B981`)
- **Ketua Ekskul**: Royal Violet (`#8B5CF6`)
- **Wakil Ketua**: Sky Blue (`#3B82F6`)
- **Sekretaris**: Golden Yellow (`#EAB308`)
- **Bendahara**: Rose Pink (`#EC4899`)
- **Dokumentasi & Humas**: Solar Orange (`#F97316`)
- **Anggota Biasa**: Muted Slate (`#64748B`)

## Typography

Typography relies on **Plus Jakarta Sans**, providing modern, approachable geometry with open counters and distinct terminals that preserve legibility on low-cost school tablets and smartphones.

### Specialty Tokens
- **`display-code`**: Dedicated token for 6-character alphanumeric session pins (*Kode Sesi*), rendered with wide tracking so students can reliably transcribe it from physical whiteboards or projector screens across the room.
- **`caption-stamp`**: Hardened high-density metadata style specifically designed for embedded photo stamps (GPS coordinates, WITA timestamps, radius tolerance, and verification cryptographic hash `ETAM-******`).
- **`label-sm`**: High-contrast, all-caps or title-case pill text used inside organizational tree nodes and status chips.

## Layout & Spacing

The layout model is driven by a mobile-first fluid container transitioning to a rigid administrative grid on larger screens.

### Grid Breakpoints
- **Mobile (`< 640px`)**: Single column layout with `margin: 1rem` (16px). All navigation persists in an ergonomic bottom dock or full-width sheet. Organizational charts flow vertically as stacked parent-child cards.
- **Tablet (`640px - 1023px`)**: 2-column grid layout with `gutter: 1.5rem`. Organizational trees split into dual-column cards with connecting stem lines.
- **Desktop (`≥ 1024px`)**: 12-column administrative grid capped at a maximum width of `1280px` centered canvas, utilizing `gutter: 2rem` and `margin: 2.5rem`. Organizational leadership rosters render in a balanced 3-column executive hierarchy.

### Spacing Principles
- Density adheres strictly to a 4px/8px modular rhythm.
- Visual proximity indicates administrative hierarchy: group headers lock directly to tables using `space-xs`, while independent operational modules maintain `space-xl` separation.

## Elevation & Depth

Visual hierarchy uses a refined hybrid of **low-contrast architectural outlines** and **subtle ambient shadows** to keep the platform performant on low-spec hardware without losing clarity.

- **Level 0 (Base Canvas)**: Background canvas (`#F8FAFC`), entirely flat.
- **Level 1 (Card & Bagan Nodes)**: White background (`#FFFFFF`) with a 1px border (`#E2E8F0`) and an ambient shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.05), 0 1px 2px -1px rgba(15, 23, 42, 0.05)`.
- **Level 2 (Interactive Cards & Popovers)**: Hover states, active dropdowns, and status pills: `0 4px 6px -1px rgba(15, 23, 42, 0.07), 0 2px 4px -2px rgba(15, 23, 42, 0.05)`.
- **Level 3 (Bottom Sheets & Dialogs)**: Modal dialogs, session drawers, and mobile bottom navigation: `0 20px 25px -5px rgba(15, 23, 42, 0.12), 0 8px 10px -6px rgba(15, 23, 42, 0.08)`.
- **Role Elevation**: Bagan cards (Pembina, Ketua, Wakil) inherit an active left accent border (`3px solid [role-color]`) to establish visual priority without relying on heavy dropshadows.

## Shapes

The design system implements balanced roundedness (`roundedness: 2`, base `0.5rem` / 8px) to project a contemporary yet disciplined institutional personality.

- **Standard Elements (8px / `rounded-md`)**: Input fields, buttons, table containers, alerts, and organizational tree cards.
- **Surface Panels (16px / `rounded-lg`)**: Metric summary cards, hero attendance banners, and bottom sheets.
- **Modal Dialogs (24px / `rounded-xl`)**: Session confirmation dialogs and standalone watermark review containers.
- **Avatars**: Always circular (`rounded-full` / 50% radius) for students, mentors, and club administrators.
- **Club Emblems (Logo Ekskul)**: Contained inside rounded squares (`rounded-lg` / 12px) to respect varied geometric crests without clipping school insignia.

## Components

### Buttons
- **Primary**: Solid `#2563EB` fill, `#FFFFFF` text, `rounded-md`, 40px height (`space-md` horizontal padding). Active state darkens to `#1D4ED8`. Focus state displays an outer ring: `3px solid rgba(37, 99, 235, 0.25)`.
- **Secondary / Subtle**: `#F1F5F9` background with `#0F172A` text and `#E2E8F0` border.
- **Destructive**: Solid `#F43F5E` fill with `#FFFFFF` text for actions like *Tolak Perizinan* or *Hapus Sesi*.
- **Floating Action Button (Mobile FAB)**: Circular 56px trigger anchored bottom-right, used for *Buka Sesi Baru* or *Presensi Cepat*.

### Role & Status Chips
- **Status Chips**:
  - *Hadir*: Background `#ECFDF5`, text `#065F46`, dot indicator `#10B981`.
  - *Izin / Sakit (Pending)*: Background `#FFFBEB`, text `#92400E`, dot indicator `#F59E0B`.
  - *Alpa*: Background `#FFF1F2`, text `#9F1239`, dot indicator `#F43F5E`.
- **Role Badges (Bagan Tag)**: Compact pills using semantic role tokens (e.g., *Pembina* in `#ECFDF5` / text `#047857`, *Ketua* in `#F5F3FF` / text `#6D28D9`).

### Bagan Struktur Cards (Organizational Nodes)
- Container: White card with 1px `#E2E8F0` border and a dedicated 4px role-tinted left indicator.
- Content Layout: Flex arrangement with 44px round student avatar on the left, full name and NISN centered, and the assigned role pill pinned top-right.

### Input Fields
- Height 42px, background `#FFFFFF`, border 1px solid `#CBD5E1`, text `body-md` (`#0F172A`).
- Focus state switches border to `#2563EB` with a `0 0 0 3px rgba(37, 99, 235, 0.15)` halo.
- Form helper text adheres to `body-sm` in `#64748B`.

### Attendance Watermark Stamp Overlay
- Dark translucent banner (`rgba(15, 23, 42, 0.85)`) embedded directly at the bottom base of captured attendance photos.
- Displays multi-line metadata in high-contrast white `caption-stamp`:
  - Line 1: `📍 Lat: -0.50218, Long: 117.15372 (±8m)`
  - Line 2: `🕒 07 Okt 2026 · 14:23:45 WITA · ETAM-a7f3e9`
  - Line 3: `🏫 SMP Negeri 10 Samarinda — [Nama Ekskul]`

### Bottom Navigation & Modal Sheets
- **Bottom Bar**: Fixed height 64px, surface `#FFFFFF`, top border 1px `#E2E8F0`, displaying 4 to 5 key actions (*Beranda, Ekskul, Presensi, Rekap, Profil*) with high-contrast active icons in `#2563EB`.
- **Bottom Sheet**: Draggable rounded drawer (`rounded-xl` top corners) used for student attendance confirmation and session token verification.