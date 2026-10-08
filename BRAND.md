# Alisops brand reference

The working reference for how Alisops looks, sounds and presents itself. When the site and this file disagree, fix one of them. Don't leave them drifting.

Last reviewed: October 2026

---

## Name

**Alisops** = *Ali* (ally) + *Ops* (operations). Your operations ally.

Write it as one word with a capital A: **Alisops**. Never "AlisOps", "ALISOPS" or "Ali's Ops".

## Positioning

> Alisops builds the data systems that keep businesses running: automated dashboards, trackers and tools that replace manual work with clarity.

Invoice Flow is the live proof of this. The statement no longer says "small businesses". The service range now runs from self-serve templates to enterprise data operations, so the positioning has to cover both ends.

## Tagline

**Systems that run your business, not the other way around.**

This is the adopted tagline and the homepage headline. Candidates we dropped:

| Option | Why it was dropped |
|---|---|
| "Your operations, finally at ease." | The previous hero line. It was soft and was never one of the agreed options. |
| "Operations, automated." | The "X, automated." pattern is everywhere in startup copy. |

## Visual identity

### Type

| Role | Typeface | Notes |
|---|---|---|
| Display / headlines | **Instrument Serif** (regular + italic) | Use italic for emphasis, never bold. |
| Body / UI | **IBM Plex Sans** 400 / 500 / 600 | |
| Figures, labels, small data | **IBM Plex Mono** 400 / 500 | Use for numbers, step markers and status labels. It's what gives the "ledger" feel. |

We used these instead of the originally planned Sora / Space Grotesk / Inter because they're more distinctive and avoid the generic tech-sans look.

### Colour

| Token | Hex | Use |
|---|---|---|
| Ink | `#1C2A22` | Primary dark, text on paper, dark sections |
| Paper | `#D9D4C6` | Primary background |
| Paper (light) | `#E6E2D6` | Raised surfaces on paper |
| Clay | `#A9677D` | Accent marks, rules, strike-throughs on paper (decorative only) |
| Clay (text) | `#7E4256` | Clay for *text* on paper: labels, italic emphasis. Base clay is only 2.9:1 on paper, too low to read; this shade passes WCAG AA |
| Ochre | `#BE8A3B` | Highlight, accents on ink, the one "signal" colour |
| Paper text | `#201D17` | Body text on paper |
| Ink text | `#EDE8DA` | Body text on ink |

We dropped the original plan (charcoal/navy + teal or amber) because teal/navy is an overused AI and SaaS pattern. The earthy palette is more memorable.

Rules:
- Use one accent per surface: clay on paper, ochre on ink.
- No gradients, glows or glassmorphism.
- Corners stay nearly square (2–3px radius at most).
- Use hairline rules (1px, low opacity) to separate content instead of shadows and cards.

### Logo

Use the italic Instrument Serif wordmark with no icon. The type treatment is distinctive enough on its own, and a generic interlocking-arrows or infinity mark would weaken it. Don't add one.

## Voice

Confident, plain-spoken, benefit-first.

**Do**
- Lead with what the client gets, not what we are.
- Use the client's words: spreadsheets, reports, Monday morning, month-end.
- Write short sentences and concrete nouns.
- Address the client as "you". Use "we" for Alisops.

**Avoid**
- Jargon and hype words like *seamless, leverage, unlock, empower, elevate, cutting-edge, revolutionise, game-changer, in today's fast-paced world*.
- The "It's not X. It's Y." construction. It reads as machine-written.
- Lists of three as a reflex.
- Em dashes as general punctuation. Use a full stop or a comma.
- Self-focused framing ("Alisops is built by…", "Behind it"). Present the person through what they mean for the client: "You'll work directly with…".

## Services

| # | Service | Who it's for | Format |
|---|---|---|---|
| 1 | **Templates** | Solopreneurs, very small businesses | Self-serve, install and go |
| 2 | **Custom automation** | Small–medium businesses with one specific manual process | Fixed-scope build |
| 3 | **CRM & workflow setup** | Teams whose CRM or project tool is messy, new, or disconnected from reporting | Fixed-scope project |
| 4 | **Systems audit & redesign** | Growing businesses whose sheets and tools have outgrown their design | Audit, then rebuild |
| 5 | **Data governance & compliance audit** | Any business holding customer or staff data that isn't sure who can access it | Audit and fix plan |
| 6 | **Data operations consulting** | Medium–large, multi-department reporting | Scoped engagement |
| 7 | **Fractional ops support** | Need ongoing help but can't justify a full hire | Monthly retainer |

On the site, templates are presented as *products* and the rest as *services*. They are different buying decisions.

## What we build

Services describe *how* a client hires us. "What we build" describes *what they end up with*. The homepage leads with this, because buyers recognise their own report before they recognise a service tier.

| Use case | Example output shown on the site |
|---|---|
| Weekly business reviews (WBRs) | Monday 07:00, in every lead's inbox |
| Daily reports | Daily email or Teams post, 06:30 |
| KPI dashboards | Live dashboard in Power BI, Looker Studio or Sheets |
| Performance management | A weekly scorecard for each team lead |
| Quality audits | Quality score and trend by person, team and process |
| SLA warnings & alerts | Alert to the owner at 80% of the SLA window |

Industries listed: customer support & contact centres, retail & e-commerce, logistics & delivery, financial services, healthcare, professional services, hospitality, manufacturing. These describe where the patterns apply, not a client list.

**Conflict-of-interest boundary:** performance management, quality audits and SLA alerting overlap with the founder's current day job. Keep them as generic capability descriptions only. Never use an employer's system names, screenshots, field names, thresholds, client names or results, even anonymised. Any example or demo must be built from scratch with made-up data.

## Tools we work in

The site groups tools so a visitor finds theirs quickly. Only list tools the founder can confidently deliver in, and take out anything you wouldn't want to be quizzed on during a sales call.

| Group | Tools |
|---|---|
| Spreadsheets & office | Microsoft Excel, Power Query, Microsoft 365, SharePoint, Google Sheets, Apps Script, Google Workspace |
| CRM & work management | Zoho CRM, monday.com, ClickUp, HubSpot, Salesforce, Pipedrive, Airtable, Notion |
| Reporting & BI | Power BI, Looker Studio, Tableau |
| Automation | Power Automate, Zapier, Make |
| Data & cloud | SQL, Python, BigQuery, Google Cloud, AWS |

Rules:
- Write product names as plain text. Never use their logos, which can look like a partnership.
- Keep the footer line: "Product names on this site belong to their owners. Alisops is independent and not affiliated with any of them."
- Never say "partner", "certified for" or "official" about a vendor unless that's formally true.

## Security & data governance

Data security is part of every engagement, from the first call to after handover. This is what the site promises, so it's what every project has to do.

| Stage | Practice |
|---|---|
| Before access | NDA signed, plus a data processing agreement where personal data is involved. What we'll access, and why, is agreed in writing. |
| During the build | Work happens inside the client's accounts with named logins and MFA. Client data isn't downloaded to our machines. Test on masked or sample data wherever possible. |
| At handover | Remove our access, rotate shared passwords and API keys, and give the client a written access record (who can see what). |
| After | Access rules, logs and backups are documented so the client can review them, or we review them under fractional support. |

Every system is built with:
- least-privilege access
- only the personal data the job needs
- role-based views
- version history and logging
- a backup before any restructure
- credentials shared only through a password manager, never by email or chat

### Compliance wording

- Say we **help clients align with** GDPR and the Nigeria Data Protection Act (NDPA) 2023, and **document** how their data is handled.
- Never claim Alisops is "certified", "GDPR compliant" or "ISO/SOC 2 compliant". Those are formal attestations we don't hold.
- We don't give legal advice. Where a legal opinion is needed, "we work alongside your legal adviser".

## Presenting the founder

The credibility section is framed around the client ("Who you'll work with"), not the founder ("Behind it").

### Conflict-of-interest rules

The founder is currently employed elsewhere. Keep the site clean of employer-specific material:

- **OK to show:** name, role type, years of experience, certifications, platforms and tools (GCP, AWS, Microsoft 365, Google Workspace, CRMs), general scope ("reporting for large, distributed operations teams"), LinkedIn, GitHub, Credly.
- **Never show:** the current employer's name, its clients, internal system or project names, or metrics tied to client work (accuracy rates, SLA figures, headcounts, cost savings).
- **Portfolio:** only Alisops work (e.g. Invoice Flow) or work built independently. Capability descriptions stay generic.
- Check the employer's outside-work policy. The LinkedIn profile is public either way.

## Ownership checklist

The creative side is settled. Ownership and legal are the open risk now that the brand is public.

- [ ] Register **alisops.com** (site is on `praisino.github.io/Alisops`)
- [ ] Set up a business email on the domain and use it as the site's contact address
- [ ] Secure social handles (LinkedIn page, X, Instagram)
- [ ] Trademark search on "Alisops" (urgent: a public site and a distributed template already use the name)
- [ ] Register the business entity
- [ ] Prepare a standard NDA and data processing agreement template, since the site says one is signed before access
- [ ] Set up a password manager for sharing credentials with clients (e.g. Bitwarden or 1Password)
