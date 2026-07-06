# Quantum Coast Capital — Brand Guide

A design system for the QCC investor presentation deck. Tone: Apple × Citadel Investments — clean, precise, sophisticated, data-driven.

---

## Logo Assets

| Asset | URL | Use |
|-------|-----|-----|
| Logo ( light bg ) | `https://r2.quantumcoastcapital.com/QCC%20Logo.svg` | White/light backgrounds |
| Logo ( dark bg ) | `https://r2.quantumcoastcapital.com/QCC%20Logo%20White.svg` | Navy/dark backgrounds |
| Icon | `https://r2.quantumcoastcapital.com/QCC%20Icon%20Black.svg` | Favicon, app icon |

---

## Typography

**Primary Typeface:** Lato

> Lato is a humanist sans-serif typeface designed for clarity and warmth. Its semi-rounded details give letters a friendly feel while maintaining a professional, geometric structure.

### Weights

| Weight | Use Case |
|--------|----------|
| **Thin** (100) | headlines, hero text |
| **Light** (300) | body copy, descriptions |
| **Bold** (700) | emphasis, data labels, key metrics |

### CSS Fallback

```css
font-family: "Lato", sans-serif;
```

---

## Secondary / Display Typeface: Unna

> Unna is a refined serif with elegant contrast. Paired with Lato, it adds
> editorial gravity and institutional warmth — a deliberate blend that keeps the
> brand from reading as coldly technical.

Use **Unna** for display headlines and marketing / editorial content — page
titles, section headings, pull-quotes, and news article headlines — where a
warmer, more institutional voice is called for. Keep body copy, UI, data, and
labels in **Lato**.

### Weights

| Weight | Use Case |
|--------|----------|
| **Regular** (400) | headlines, section titles, pull-quotes |
| **Bold** (700) | occasional emphasis in editorial headings |
| *Italic* (400/700) | pull-quotes and editorial emphasis |

### CSS Fallback

```css
font-family: "Unna", Georgia, serif;
```

### Pairing the two

- **Lato (sans)** — primary. Body copy, navigation, UI, data, labels, and any
  technical or interface context.
- **Unna (serif)** — secondary display. Headlines and marketing / editorial
  content, used to add institutional warmth.

The intentional blend — clean sans for structure, warm serif for voice — reads
institutional without feeling overly technical.

---

## Color Palette

### Primary

| Name | HEX | RGB | Use |
|------|-----|-----|-----|
| Royal | `#002F6C` | 0, 47, 108 | Primary brand, headers, key elements |
| Electric Blue | `#00A9CE` | 0, 169, 206 | Accents, links, highlights |
| White | `#FFFFFF` | 255, 255, 255 | Backgrounds, negative space |

### Secondary

| Name | HEX | RGB | Use |
|------|-----|-----|-----|
| Navy | `#161729` | 22, 23, 40 | Dark backgrounds, contrast |
| Electric Arc | `#00C1D5` | 0, 193, 213 | Secondary accents, charts |
| Slate | `#D9D9D6` | 217, 217, 214 | Borders, grids, subtle dividers |

### Tertiary (Charts & Accents)

| Name | HEX | Name | HEX |
|------|-----|------|-----|
| Sun | `#F2CD00` | Celadon | `#85B09A` |
| Ticker | `#6CC24A` | Circuit | `#006341` |
| Bronze | `#B0AA7E` | Gold | `#F0B323` |
| Platinum | `#A2AAAD` | Amber | `#E56A54` |
| Titanium | `#00558C` | Purple | `#7D55C7` |
| Arctic | `#99D6EA` | Burgundy | `#672146` |

### Graphs Only

| Name | HEX | Use |
|------|-----|-----|
| Flag | `#9A3324` | Negative values, losses, alerts |

---

## Layout

- **Aspect ratio:** 16:9
- **Padding:** Consistent padding around content; auto-scale to viewport
- **Grid:** Modular, grid-like organization for charts and content
- **Whitespace:** Generous; clarity over density

---

## Data Visualization

- **Line charts:** Royal + Electric Blue / Electric Arc
- **Positive values:** Blues (Royal, Titanium, Electric Blue)
- **Negative values:** Flag (`#9A3324`)
- **Donut/Pie:** Primary + tertiary palette for distinct segments
- **Bar charts:** Shades of blue with light gray grid lines
- **Grid lines:** Slate (`#D9D9D6`) or `rgba(0,0,0,0.08)`

---

## Design Principles

1. **Minimal** — Remove everything nonessential
2. **Functional** — Every element serves content
3. **Data-first** — Charts are primary; type supports them
4. **Professional** — Trustworthy, precise, institutional
5. **Consistent** — Same palette, weights, and spacing throughout
