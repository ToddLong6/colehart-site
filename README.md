# ColeHart Enterprises — Main Site

`opticheck-site` is the public marketing website for **ColeHart Enterprises LLC** —
*Technology. Talent. Program Support.*

## What it is

A static, multi-page website built with:

- HTML — top-level pages (`index.html`, `services.html`, `government.html`,
  `commercial.html`, `about.html`, `contact.html`, `insights.html`,
  `privacy.html`, `terms.html`) plus the printable capability statement in
  `government/capability-print.html`
- Shared CSS (`css/style.css`)
- Static assets (`images/`, `robots.txt`, `sitemap.xml`, `CNAME`, and a
  downloadable PDF guide)

No build step, framework, or bundler.

## What it does

The site positions ColeHart as a veteran-owned technology and professional
services company serving three audiences — government agencies, prime
contractors, and commercial organizations — across three service areas:

1. **Technology Services** — IT infrastructure, systems, networks, data centers,
   Microsoft 365 / SharePoint, cloud, automation, and technical documentation
2. **Data & Program Services** — analytics, dashboards, reporting, business
   analysis, and project/program coordination
3. **Workforce Solutions** — qualified technical and professional personnel for
   project, contract, and subcontract requirements

It also presents three direct commercial solutions (Dashboard & Reporting Setup,
Technical Documentation Package, Contract Technical Resource) and a government /
prime-contractor capability page with business credentials (Veteran-Owned,
SAM.gov Registered & Active, UEI `QMEXHNTJYJR3`, CAGE `1CQK6`).

Contact and lead-capture use Formspree (`formspree.io/f/mgorykdv`) with an
EmailJS auto-reply.

## Internal tools

OptiCheck and OpticBid are internal tools ColeHart maintains for its own
operations and business development. They are referenced only in a small
"Internal Technology / Tools" note on the Services page and are not part of the
company's primary positioning.

## Deployment

Served by **GitHub Pages** from the repository root. `CNAME` points the site at
`colehartenterprises.com`. Pushing to `main` publishes.

## Local preview

Open `index.html` directly in a browser, or serve the folder statically:

```bash
npx serve .
```

Then open the local URL shown in your terminal.
