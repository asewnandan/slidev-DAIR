# DAIR Presentatie - Overzicht

## Structuur (compleet! ✅)

### 1. Introductie (5 slides)
- `01-cover.md` - Titel + presentatoren
- `02-data-trends.md` - Belang van data
- `03-1cijferho.md` - Wat is 1CijferHO
- `04-problem-teaser.md` - Probleem intro
- `05-takeaways.md` - Wat neem je mee

### 2. Problem (7 slides)
- `01-transitie.md` - Waarom gebruikt niet iedereen het?
- `02-zip-structuur.md` - 3 bestandstypes
- `03-zip-lijst.md` - Bestandslijst voorbeeld
- `04-main-chaos.md` - ASCII chaos
- `05-beschrijving-chaos.md` - PDF chaos
- `06-oude-workflow.md` - Weken werk timeline
- `07-poll.md` - Herkenbaar? hands up

### 3. Solution (10 slides)
- `01-transitie.md` - Van weken naar seconden
- `02-high-level.md` - 4 stappen (Parse, Extract, Load, Validate)
- `03-voor-na.md` - Voor/na vergelijking
- `04-tech-parse.md` - Technisch: Parse
- `05-tech-extract.md` - Technisch: Extract
- `06-tech-load.md` - Technisch: Load
- `07-tech-validate.md` - Technisch: Validate
- `08-ui-code.md` - UI + Programmeerbaar
- `09-privacy.md` - Privacy & lokaal
- `10-demo-intro.md` - Demo intro

### 4. Demo (2 slides)
- `01-demo-start.md` - Live demo
- `02-demo-recap.md` - Wat je zag

### 5. Future (5 slides)
- `01-roadmap.md` - Wat komt er
- `02-get-started.md` - Hoe te gebruiken
- `03-recap.md` - Samenvatting
- `04-qa.md` - Vragen?
- `05-thank-you.md` - Bedankt + links

## Totaal: 29 slides

## Design
- Apple-style: simpel, clean, veel witruimte
- Grote fonts (text-5xl, text-6xl)
- Emoji's in plaats van icon libraries
- Grid layouts voor structuur
- v-clicks voor animaties

## Screenshots nodig
Voeg toe in `public/screenshots/`:
1. `zip-lijst.png` - (optioneel, hebben placeholder)
2. `beschrijving-chaos.png` - (optioneel, hebben placeholder)

## Run presentatie
```bash
pnpm install
pnpm dev
```
