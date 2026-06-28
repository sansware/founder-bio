# Jordan Gilbert — Technical Founder of UK Web Marketing

Engineer turned builder, then operator. I am a Loughborough-trained architectural engineer and HarvardX (GSD1x) alum who has been building websites for over 20 years, since 2006. Today I serve as **Technical Co-Founder & Interim CTO at TicketWave HQ Ltd** and as **founder of UK Web Marketing**, a delivery studio shipping production websites and digital infrastructure for UK small businesses.

**Canonical home:** https://ukwebmarketing.com/jordan — the source of truth for this bio. Anything here is a mirror.

## Why this repo exists

This repository is a public mirror of the credentials block from my canonical bio. It exists so that anyone who lands on the `sansware` GitHub handle — recruiters, founders, journalists, or collaborators — has somewhere substantive to read, with the underlying source files alongside the claims.

Open-by-default. Verifiable. No third-party lookup required to confirm what I went to university for, what I have certified, or what I currently operate.

## Verified credentials

- **BSc Architectural Engineering & Design Management** — Loughborough University. Focus on architectural design development, computational and parametric modelling workflows, integrated engineering and construction management, interdisciplinary collaboration, and BIM-driven common data environments.
- **HarvardX GSD1x: The Architectural Imagination** — Harvard University, via the Harvard Graduate School of Design. Instructor: K. Michael Hays. Verifiable certificate: https://courses.edx.org/certificates/614c26ddea004818a73d50ad8b264855

See [`harvardx-cert/README.md`](./harvardx-cert/README.md) for full certificate metadata and verification instructions.

## What I operate

- **TicketWave HQ Ltd** — UK-registered platform company (Companies House no. **17143167**) building booking, ordering, and ticketing infrastructure for small businesses.
- **UK Web Marketing** — delivery studio building production websites and integrating those systems for UK SMEs, supported by a small bench of trusted collaborators.

## TicketWave product lines

TicketWave HQ Ltd ships two product lines off a shared infrastructure spine:

- **Commerce** — booking, ordering, and ticketing infrastructure for hospitality, events, and small-business operators. Stripe-native checkout, multi-tenant venues, payouts, and the operator surface that runs day-to-day trading.
- **Witness** — physical-security sensing. Edge devices and signal pipelines for venues, sites, and operators who need verifiable physical-world telemetry alongside their commerce stack.

Both product lines share the same identity, billing, and observability primitives; Witness extends the platform into the physical-security domain rather than living as a separate company.

## Stack choices (why this repo is plain Markdown)

The canonical `/jordan` page itself is built in **Astro** with content-collection-driven JSON-LD and zero client-side framework runtime. The reasons match the bio's "How this informs my work" section:

- **Systems-first design logic** — every build is a system, not a surface. Astro lets the page ship as static HTML with structured-data baked in at build time.
- **Performance-led engineering execution** — sub-second loads, near-perfect Core Web Vitals, and predictable behaviour at scale. No SPA hydration tax for a page that is mostly prose.
- **Structurally minimal digital architecture** — fewer moving parts, fewer dependencies, less to break.

This repo (`founder-bio`) is intentionally even simpler: plain Markdown plus the mirrored Astro source. No build step, no framework, no analytics. The whole point is that the credentials are inspectable in their rawest form.

The full Astro source for the live page is at [`sources/jordan.astro`](./sources/jordan.astro).

## Find me

- **Web:** https://ukwebmarketing.com/jordan
- **LinkedIn:** https://www.linkedin.com/in/eu-jordangilbert/
- **GitHub:** [@sansware](https://github.com/sansware)
- **Email:** jordan@sansware.tech

## Find me elsewhere

- **TicketWave HQ:** [@TicketWaveHQ](https://github.com/TicketWaveHQ)
- **UK Web Marketing:** [@Ukwebmarketing](https://github.com/Ukwebmarketing)
- **Orenva Health:** [@Orenva-Health](https://github.com/Orenva-Health)

## License

The text content of this repository is released under the **Creative Commons Attribution 4.0 International License** ([CC BY 4.0](./LICENSE)). You are free to share and adapt the bio and credential information, including for commercial use, provided you give appropriate credit. See [`NOTICE`](./NOTICE) for the human-readable summary.

Last verified: 2026-06-28

```json
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "Jordan Gilbert",
  "givenName": "Jordan",
  "familyName": "Gilbert",
  "jobTitle": "Technical Founder of UK Web Marketing",
  "url": "https://ukwebmarketing.com/jordan",
  "email": "mailto:jordan@sansware.tech",
  "sameAs": [
    "https://github.com/sansware",
    "https://www.linkedin.com/in/eu-jordangilbert/",
    "https://ukwebmarketing.com/jordan"
  ],
  "alumniOf": [
    {
      "@type": "CollegeOrUniversity",
      "name": "Loughborough University"
    },
    {
      "@type": "EducationalOrganization",
      "name": "HarvardX",
      "parentOrganization": "Harvard University"
    }
  ],
  "worksFor": [
    {
      "@type": "Organization",
      "name": "TicketWave HQ Ltd",
      "identifier": "17143167",
      "url": "https://github.com/TicketWaveHQ"
    },
    {
      "@type": "Organization",
      "name": "UK Web Marketing",
      "url": "https://ukwebmarketing.com"
    },
    {
      "@type": "Organization",
      "name": "Orenva Health",
      "url": "https://github.com/Orenva-Health"
    }
  ]
}
```
