# Job Application Assistant for Robert Tuma

## Role
This repo is a job application workspace. Claude acts as a career advisor and application assistant for Robert Tuma, helping with:
1. **Job fit evaluation** - Assess job postings against his profile (skills, experience, behavioral traits)
2. **CV tailoring** - Adapt existing CV templates (LaTeX/moderncv) to target specific roles
3. **Cover letter writing** - Draft targeted cover letters using existing templates (LaTeX)
4. **Interview preparation** - Prepare answers, questions, and talking points for interviews
5. **Career strategy** - Advise on positioning and personal branding

## Candidate Profile

### Identity
- **Name:** Robert Tuma
- **Date of birth:** 4 June 2004
- **Location:** Munich, Bavaria, Germany (available for in-person/hybrid roles in Munich)
- **Languages:** German (native), English (fluent — professional working proficiency)
- **Status:** Final-year B.Sc. student (Maschinenwesen, TU Munich) — available as Werkstudent, preferred ~15–16 hours/week
- **LinkedIn headline:** "Mechanical Engineering Student @ TUM"

### Education
- **B.Sc. Maschinenwesen (Mechanical Engineering)** (2022 – expected Spring 2027) – Technische Universität München (TUM), Garching
  - Specialisation focus: Product development / Konstruktion, design
  - Completed modules: Höhere Mathematik 1–3, Technische Mechanik 1–3, Chemie, Experimentalphysik, Grundlagen CAD und Maschinenzeichnen, Grundlagen der modernen Informationstechnik, Grundlagen der Technischen Elektrizitätslehre, Einführung in die Produktionstechnik, Modellierung von Unsicherheiten und Daten, Grundlagen der Thermodynamik, Werkstoffe des Maschinenbaus 1–2, Maschinenelemente 1–2, Fluidmechanik 1, Regelungstechnik, Mathematische Tools, Cost Accounting, Messtechnik und medizinische Assistenzsysteme, Engineering Ethics, Humans in Space
  - Currently in progress: Human and Humanity Centered Design, Wärmetransportphänomene, Bioengineering, Automatisierungstechnik

### Professional Experience
- **Product Vision & Strategy** (Jan 2026 – May 2026) – **MOOSYC** (music tech startup, part-time, Munich)
  - UI/UX design across web and mobile in Figma; artist-facing tools and user journeys
  - Designed song pitch experience with typewriter/letter stamp/mailbox interaction concept
  - Creative merchandising concepts (apparel, brand assets); contributed to product positioning

- **Product Vision & Strategy — Stealth Startup** (May 2025 – Dec 2025) – music tech space (part-time, investor confidentiality — do NOT name MOOSYC in this entry)
  - UX concept development, Figma-based design, product vision contribution
  - Contributed to Y Combinator pitch preparation and supporting materials

- **Cabin and Systems Intern (Ingenieurspraktikum)** (Oct 2024 – Jan 2025) – **Deutsche Aircraft GmbH**, Oberpfaffenhofen
  - Systems Engineering: studied and compared ARP 4754A and ARP 4754B; documented gaps
  - Requirements Engineering: IBM DOORS module creation, DXL scripting (welcome screen, access control, workflow automation), comprehensive user guide
  - CAD/Production: converted 3D models to sheet metal parts in CATIA V5/3DX; 2D manufacturing drawings with tolerances
  - Data Management: BOM alignment between 3DX and SAP for D328eco using Excel
  - Software: independently designed and built Python (customTkinter) dashboard for hangar operations — live status toggles, file upload, live ticker, dual display modes
  - Sustainable aviation: researched SAF and Power-to-Liquid fuels; participated in UpLift-CLIMOART project briefings
  - Received official Zeugnis; Deutsche Aircraft subsequently offered an apprenticeship position

- **Department — Printing Office** (Nov 2022 – Sep 2024) – **Fachschaft Maschinenbau, TU München**, Garching (part-time)
  - Operated industrial printing equipment (Bourg Binding System 3002, Polar Mohr 66)

- **Tennis Instructor** (May 2020 – Jul 2022) – **oncourt Tennis & Sportschule GmbH**, Munich
  - Developed and implemented personalised training methods; coached students across skill levels

### Technical Skills
- **Primary:** Figma (UI/UX design, wireframing, prototyping, component design, user journey mapping); SolidWorks (CAD); Python (scripting, GUI development, data processing)
- **Secondary:** CATIA V5 / 3DExperience; IBM DOORS (requirements management, DXL scripting); Microsoft Excel (advanced); SAP (basic)
- **Domain:** Systems engineering; aviation standards (ARP 4754A/B, DO-326/ED-202); product development; requirements engineering; sustainable aviation (SAF, PtL)
- **Software:** Microsoft Office suite; customTkinter; SysML/OPM (basic understanding)

### Certifications
- **MIT Fundamentals of Systems Engineering** — completed during Deutsche Aircraft internship (Oct–Jan 2024/25)
- **DO-326/ED-202 Aviation Cybersecurity** (IUEI/cyber threats, ASISP framework) — completed during Deutsche Aircraft internship

### Behavioral Profile
- **Fast learner / high adaptability** — acquired deep specialist knowledge in new domains (aviation standards, IBM DOORS, CATIA, Python GUI) within weeks at Deutsche Aircraft; explicitly praised in reference
- **Self-directed ownership** — took initiative and fully owned deliverables without close supervision at both Deutsche Aircraft and MOOSYC
- **Creative + analytical balance** — unusual combination of engineering rigour and product/design intuition; equally comfortable in both modes
- **High reliability** — described as "extremely reliable," "diligent," and "responsible" in reference letters from both employers
- **Strengths:** translating abstract ideas into concrete artefacts; rapid domain onboarding; combining structured engineering thinking with design sensibility; working in high-ambiguity fast-moving environments; resilient consistency — shows up and delivers reliably regardless of motivation
- **Growth areas:** depth of software engineering beyond scripting/prototyping; still building breadth in specific engineering sub-disciplines (FEM, thermal systems)
- **Thrives in:** small teams with real ownership; environments valuing both technical rigour and creative thinking; ambitious companies building something new

### What Excites You
- Product development at the intersection of engineering and design
- Working on physical or digitally-enabled products with tangible real-world impact
- Early-stage or innovation-focused environments where scope isn't fully defined
- Sustainable technology (aviation, mobility)
- Tools and systems that make complex things easier to understand or use

### Target Roles (Werkstudent)
- Werkstudent Produktentwicklung / Product Development
- Werkstudent Konstruktion / Mechanical Design
- Werkstudent UX/Product Design (especially at tech-adjacent hardware or mobility companies)
- Werkstudent Systems Engineering (aerospace, automotive, mobility)
- Werkstudent Innovation / R&D

### Target Sectors
- Aerospace / aviation (strong prior exposure, clear interest)
- Automotive / urban mobility
- Hardware-focused startups or scaleups
- Industrial / production technology
- Consumer tech with physical product component

### Deal-breakers
- Fully remote (strong preference for in-person/hybrid, not an absolute deal-breaker)
- Very traditional, slow-moving culture — preference for forward-looking, innovative environments
- Pure sales or back-office roles with no engineering or design component
- Companies with no engineering product or physical artefact

## Repo Structure
- `cv/` - LaTeX CV variants (moderncv template, banking style)
- `cover_letters/` - LaTeX cover letters (custom cover.cls template)
- `.claude/skills/` - AI skill definitions for the application workflow
- `.agents/skills/` - Job search CLI tools (note: built for Danish market — use `/apply` with direct URLs or pasted job descriptions for German market)

## Workflow for New Job Applications
1. User provides a job posting (URL or text)
2. **Always evaluate fit first**: skills match, experience match, behavioral/culture match. Present this assessment before proceeding.
3. If good fit: create targeted CV (`cv/main_<company>.tex`) and cover letter (`cover_letters/cover_<company>_<role>.tex`)
4. **Verify both documents** (see Verification Checklist below)
5. Prepare interview talking points based on the role requirements and Robert's strengths

**Language rule:** Write CV and cover letter in the language of the job posting. German posting → German documents. English posting → English documents. Mixed or unclear → default to German for Munich-based companies, English for international.

**Important:** When mentioning agentic coding or AI tooling in CVs/cover letters, explicitly reference **Claude Code** by name.

## Verification Checklist
After creating or updating a CV or cover letter, re-read the generated file and verify **all** of the following before presenting to the user. Report the results as a pass/fail checklist.

### Factual accuracy
- [ ] All claims match actual profile (CLAUDE.md) — no fabricated skills, experience, or achievements
- [ ] Job titles, dates, company names, and locations are correct
- [ ] The Stealth Startup entry (May–Dec 2025) does not name MOOSYC (investor confidentiality); the Jan–May 2026 MOOSYC entry may name the company
- [ ] Contact details are correct
- [ ] All company-specific claims verified via WebFetch/WebSearch

### Targeting
- [ ] Profile statement / opening paragraph is tailored to the specific role (not generic)
- [ ] Skills and experience bullets are reframed to match the job requirements
- [ ] Key job requirements are addressed (gaps acknowledged where relevant)
- [ ] Nice-to-have requirements highlighted where there is a match

### Consistency
- [ ] CV follows standard 2-page moderncv/banking format
- [ ] Cover letter uses cover.cls template and established structure
- [ ] Tone is consistent across CV and cover letter
- [ ] No contradictions between CV and cover letter content

### Quality
- [ ] No LaTeX syntax errors (balanced braces, correct commands)
- [ ] No spelling or grammar errors
- [ ] Cover letter is addressed to the correct person (or "Sehr geehrte Damen und Herren" / "Dear Hiring Manager" if unknown)
- [ ] Cover letter fits approximately one page

### Compiled PDF verification (MANDATORY - never skip)
Both documents MUST be compiled and visually inspected via the Read tool on the PDF output. "Looks fine in the .tex" is not acceptable - LaTeX page-break decisions are unpredictable. Iterate until these all pass:
- [ ] CV compiled with **lualatex** (pdflatex often fails on modern MiKTeX with fontawesome5 font-expansion errors). Cover letter compiled with **xelatex** (cover.cls requires fontspec).
- [ ] **CV is exactly 2 pages** - not 1, not 3
- [ ] **No orphaned `\cventry` titles** - a job/education title must never sit at the bottom of a page with its bullets spilling to the next page. Use `\needspace{5\baselineskip}` before each `\cventry` to prevent this, and `\enlargethispage{2-3\baselineskip}` to rescue a trailing section that just barely spills
- [ ] **Cover letter is exactly 1 page** - signature block must fit with the body, never overflow
- [ ] **Cover letter bullet font matches body font** - `\lettercontent{}` must not wrap `\begin{itemize}...\end{itemize}` (the command's trailing `\\` errors on `\end{itemize}`, and moving itemize outside loses the Raleway font). Standard pattern: close `\lettercontent{}`, then wrap the list in `{\raggedright\fontspec[Path = OpenFonts/fonts/raleway/]{Raleway-Medium}\fontsize{11pt}{13pt}\selectfont \begin{itemize}...\end{itemize}\par}`
