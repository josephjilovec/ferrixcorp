# Crestline Metals

Corporate website for Crestline Metals, a Pennsylvania-based industrial manufacturing venture.

## Positioning

The site is intentionally written and designed in an institutional, private-equity-ready style: capability, disciplined operations, quality, reliability, safety, long-term partnership, and Pennsylvania industrial context without commodity-brand clichés.

## Stack

- Static HTML, CSS, and JavaScript
- No framework or build step required
- Responsive navigation and mobile layouts
- Scroll reveal, active navigation, progress indicator, and subtle hero parallax
- SEO title/description and Open Graph metadata
- Accessible skip link, focusable navigation, reduced-motion support, form labels, and semantic sections
- Vercel-ready configuration

## Current site architecture

The first release is a fast single-page corporate site with anchored sections for:

- Home
- About
- Capabilities
- Markets
- Quality & Sustainability
- Careers
- News & Insights
- Contact / Quote inquiries

This architecture can later be split into dedicated pages without changing the design system.

## Production facts that should be verified before publishing

Do not add or imply specific operational facts until they are confirmed by Crestline Metals management. In particular, verify before publication:

- Facility street addresses and legal headquarters
- Production capacity or annual tonnage
- Exact grades, gauges, dimensions, chemistries, and product ranges
- Equipment lists and process-route details
- Certifications, accreditations, audit standards, or laboratory credentials
- Customer names, contracts, delivery-performance metrics, or market-share claims
- Environmental performance numbers, emissions claims, recycled-content claims, or energy-source claims
- Leadership names and biographies
- Benefit plans and open job requisitions

## Contact form

The form UI and validation are complete, but outbound routing is intentionally not connected to an invented email address or third-party endpoint. Connect the form to Crestline Metals' approved email, CRM, FormSubmit/Web3Forms account, or a Vercel serverless endpoint before public launch.

## Photography

The initial design references free-to-use industrial photography hosted by Pexels for the hero, operations, and careers imagery. For a final institutional website, replace stock imagery with owned photography from actual Crestline Metals facilities as soon as it becomes available.

## Deploy on Vercel

Import this repository into Vercel. The repository requires no build command. Vercel can serve the root `index.html` directly.

## Primary file

`index.html` is self-contained: layout, responsive styles, visual system, and interaction logic are all inline for simple editing and portability.