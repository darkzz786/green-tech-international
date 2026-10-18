# GIC Landscape website

Complete responsive static HTML, CSS and JavaScript project. No npm install, build step, PHP or database required.

## Preview locally
Open index.html in your browser, or use VS Code Live Server.

## Deploy to Vercel
1. Extract this ZIP.
2. Create a GitHub repository and upload everything INSIDE gic-landscape-vercel, including index.html, style.css, app.js, vercel.json and assets.
3. In Vercel, add a new project and import that repository.
4. Select Framework Preset: Other. Root Directory: the folder containing index.html (repository root if uploaded as instructed).
5. Leave Build Command empty. Output Directory should be the project root (use . if an override is needed). No install command is needed.
6. Deploy. No environment variables are required for this version.

## Features
- Responsive navigation and forest-green/cream visual theme
- Original GIC logo and locally bundled original website photographs
- Service detail dialogs
- Filterable portfolio with image/detail dialogs
- Guided enquiry form with native required-field validation
- Reviewable enquiry text and WhatsApp/email handoff
- Click-to-call, maps, social and IndiaMART links
- Expandable FAQs and reduced-motion support

## Editing
index.html: page copy, contacts, form options and main sections.
style.css: colors, typography and responsive layouts.
app.js: service details, portfolio filters and enquiry message generation.
assets/: bundled logo and photos. Google Fonts uses an external stylesheet; system font fallbacks work offline.

## Enquiry behavior
The form prepares a message. It does not submit to a server or store leads. Visitors must choose WhatsApp or their email app and send the message themselves. Confirm WhatsApp is enabled on +91 8743063182 before client launch. Automatic email delivery, admin login, CRM and database persistence are not included.

## Content provenance and launch review
Content, contact details, logo, service lists and project category photographs were taken from https://www.giclandscape.com/ on 18 October 2026. Text has been rewritten for the new layout. No client testimonials, awards or performance statistics were invented. The original portfolio category images are retained without asserting individual project names. IndiaMART could not be accessed; its supplied link is included but no listing claims were imported.
Confirm business contacts, image rights and current service availability with the client before public launch. Replace the footer concept label if approved.

## Verification
JavaScript syntax and local asset references checked; all 14 bundled images decoded successfully. Browser/device visual and interaction testing could not be run in this environment. Test filters, mobile menu, dialogs and enquiry handoff before client presentation.

## Design revision 2
Editorial split hero, arch-shaped photograph, oversized typography, chartreuse accents, staggered service cards, asymmetric portfolio layout, rounded sections and reduced-motion-aware reveal animations. Existing enquiry and gallery functionality retained.

## Mobile and account revision 3
- Fixed five-tab mobile navigation: Home, Services, Projects, Saved, Account.
- Safe-area spacing, larger touch targets, single-column mobile form and swipeable portfolio filters.
- Save/remove project inspiration; browser-local shortlist persists when localStorage is available. Discuss shortlist fills the enquiry message.
- Login/sign-up interactive preview uses display name only and explicitly states no real authentication. Local welcome dashboard and exit demo action included. No password, email, real login, server session or booking is implemented.
- Code syntax, local references, unique IDs and section targets checked. Real browser/device interaction testing remains necessary before launch.
