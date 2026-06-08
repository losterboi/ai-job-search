# Search Queries for Job Scraper — Robert Tuma (Munich)

<!-- German market focus: StepStone, Indeed.de, LinkedIn, Xing, company career pages -->
<!-- Note: The built-in CLI tools target Danish job portals and are not useful here. -->
<!-- Use /apply with direct job URLs or pasted job descriptions from German portals. -->

## Search Sites (German market)

Primary:
- **linkedin.com/jobs** — filter: München / Bavaria; Werkstudent
- **stepstone.de** — largest German job board; supports Werkstudent filter
- **indeed.de** — broad coverage; good for smaller companies
- **xing.com/jobs** — strong for German engineering/tech roles
- **arbeitsagentur.de/jobsuche** — Bundesagentur für Arbeit; comprehensive

Secondary (company career pages via Google):
- `site:careers.[company].com Werkstudent München`
- `"[company]" Werkstudent Produktentwicklung München site:linkedin.com`

Target company career pages to check directly:
- Airbus (airbus.com/en/careers)
- BMW Group (bmwgroup.com/careers)
- MAN Truck & Bus
- Lilium / Volocopter / Archer (urban air mobility)
- Isar Aerospace
- Celonis / Personio / Flixbus (Munich tech scale-ups)
- Siemens Healthineers / KUKA (industrial tech Munich)

## Query Categories

### Priority 1: Product Development / Konstruktion (Strongest fit)

These match SolidWorks CAD background and engineering coursework.

```
site:linkedin.com/jobs Werkstudent Produktentwicklung München
site:stepstone.de Werkstudent Konstruktion München Maschinenbau
site:indeed.de Werkstudent CAD SolidWorks München
Werkstudent "Produktentwicklung" "SolidWorks" München
Werkstudent Konstruktion Maschinenbau München Luft OR Automotive
```

### Priority 2: UX / Product Design (Figma expertise)

Matches ~13 months of real Figma / product design work.

```
site:linkedin.com/jobs Werkstudent UX Design München
site:stepstone.de Werkstudent "Product Design" OR "UX Design" München
Werkstudent Figma München Hardware OR Mobility OR Automotive
Werkstudent Produktdesign München startup
"Working Student" UX Design Munich Figma
```

### Priority 3: Systems Engineering / Aerospace (Deutsche Aircraft background)

Matches ARP 4754A/B, IBM DOORS, and aviation systems experience.

```
site:linkedin.com/jobs Werkstudent Systems Engineering München Luft
site:stepstone.de Werkstudent Systemtechnik Luftfahrt München
Werkstudent "Requirements Engineering" OR "IBM DOORS" München
Werkstudent Luft- und Raumfahrt München Ingenieur
"Working Student" Systems Engineering Munich Aviation
```

### Priority 4: Innovation / R&D / Adjacent roles (broader net)

```
site:linkedin.com/jobs Werkstudent Innovation München Maschinenbau
site:stepstone.de Werkstudent "R&D" OR "Forschung und Entwicklung" München
Werkstudent Digitalisierung Produktentwicklung München
Werkstudent "Technical Product Manager" OR "Technischer Produktmanager" München
Werkstudent Nachhaltigkeit Mobilität München Ingenieur
```

## Location Filter

Only roles in or near Munich are relevant. Define tiers:

- **Ideal:** München city; Garching; Oberpfaffenhofen; Unterschleißheim; Ottobrunn; Taufkirchen
- **Acceptable:** Freising; Dachau; Starnberg; Germering (~30–40 min by transit)
- **Borderline:** Augsburg; Ingolstadt (flag; discuss with user — typically too far for a Werkstudent role)
- **Too far:** Anywhere requiring >60 min one-way or relocation

## Date Filter

Only include jobs posted within the last 14 days, or with an application deadline that has not yet passed. If a posting date cannot be determined, include it but flag as "date unknown".

## Role Type Suggestions

Based on Robert's profile, also consider these roles he may not have searched for:

- **Werkstudent Technical Product Management** — bridges engineering and product; matches his dual engineering/design background
- **Werkstudent Usability Engineering / Human Factors** — relevant given "Human and Humanity Centered Design" coursework at TUM and Figma experience
- **Werkstudent Nachhaltige Mobilität / Sustainable Aviation** — direct alignment with SAF/D328eco exposure at Deutsche Aircraft
- **Werkstudent CAD-Konstruktion** at hardware startups — smaller companies building physical products often need hands-on SolidWorks support at student level

## Adapting Queries

If the user specifies a focus area, select queries from the matching category and generate 2–3 custom queries for that focus. For example:
- "/scrape aerospace" → Priority 3 queries + custom aviation-specific queries
- "/scrape ux" → Priority 2 queries + company-specific design team searches
