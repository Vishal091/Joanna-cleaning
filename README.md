# Joana's Cleaning — website redesign

A responsive static marketing website for Joana's Cleaning in Hillside, New Jersey. Built with semantic HTML, custom CSS and vanilla JavaScript; no package manager or framework build is required.

## Files

- `index.html`: full homepage, six service cards, customer-review section, FAQ accordion, responsive estimate form, SEO metadata and a preset virtual assistant.
- `privacy.html`: explains the email-draft quote flow and local-only guided chatbot.
- `favicon.svg`: custom brand mark.
- `robots.txt` and `sitemap.xml`: basic search-engine discovery files.

## UX and technical features

- Editorial forest-green, cream and clay visual system with oversized type and layered interior photography.
- Responsive mobile nav, touch-friendly CTAs, fixed mobile call/estimate bar and no horizontal page scrolling by design.
- Scroll progress, sticky-header polish, subtle hero parallax, staggered reveal animation, ticker and card hover feedback.
- Reduced-motion support, keyboard focus states, semantic headings, descriptive image alt text, expandable accessible FAQs.
- Rule-based preset virtual assistant with question chips and keyword-matched typed questions. It is intentionally not represented as a generative AI service: there is no LLM API or backend.
- Estimate form prepares an email draft addressed to the public business email. This static website does not store leads or claim that an email was sent.

## Review research and attribution

The current public website identifies the target business as Joana's Cleaning at 509 McMichael Pl, Hillside, NJ 07205, phone (862) 290-8386 and info@joanacleaning.com.

Search results for the exact Hillside listing surfaced a Thumbtack profile showing a 5.0 rating from 6 reviews and short reviews including “very professional and meticulous,” “Nice work,” and “Buena calidad.” Those excerpts are attributed to Thumbtack and link to that listing.

A confirmed Google Business Profile for the exact Hillside business could not be established from the accessible search results. Search also returned a different Joana's Cleaning Services LLC in Avondale, Arizona with Google reviews; those reviews are **not** used on this site because they cannot be attributed to the Hillside business. Once the owner supplies the exact Google Business Profile URL, update the review CTA and add only verified reviews from that profile with proper attribution and approved excerpting.

## Run locally

Open `index.html` in a browser or serve the repository root with a static web server.

## Before production launch

1. Ask the owner to approve the imagery, service descriptions, eco-product statements, service area, opening hours and claims such as licensed/insured.
2. Replace stock images with real, owner-approved photos of the team and completed cleans.
3. Get the exact Google Business Profile link before showing Google review counts, star ratings or quotes.
4. Test the quote form with a desktop and mobile email application; because the form uses `mailto:`, behavior depends on the visitor having an email app configured.
5. Test the responsive layout on common phone widths and use browser/device testing to catch issues not visible in static source inspection.
6. Confirm the phone/email routes are current and have the business owner test a real inquiry.
7. Connect or verify Vercel to this repository's `main` branch and confirm the deployment before switching the production domain. This repository commit alone does not prove the site has been published.

The photos are illustrative stock photography and are not claimed to document Joana's Cleaning's actual work.
