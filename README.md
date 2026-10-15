# Joana's Cleaning — website redesign

A responsive static marketing website for Joana's Cleaning in Hillside, New Jersey. Built with semantic HTML, custom CSS and vanilla JavaScript; no package manager or framework build is required.

## Files

- `index.html`: homepage, six service cards, photo story, customer reviews, FAQ accordion, estimate form, SEO metadata and rule-based virtual assistant.
- `privacy.html`: explains the email-draft quote flow and local-only guided chatbot.
- `favicon.svg`: custom brand mark.
- `robots.txt` and `sitemap.xml`: basic search-engine discovery files.

## Visual direction and UX

- Distinctive cobalt, papaya coral, butter-yellow and lilac palette. This is intentionally separate from the forest-green palette used on the Happy Cleaning demo.
- Expressive display typography, asymmetrical service cards, varied card corners, stronger contrasting section backgrounds and editorial photo treatment.
- Scroll progress, sticky-header polish, subtle hero parallax, staggered reveal animation, ticker motion and hover micro-interactions.
- A scroll-driven horizontal photo story on desktop; it becomes a normal stacked gallery on mobile to preserve natural touch scrolling.
- Reduced-motion support, keyboard focus styles, descriptive image alt text, expandable FAQ buttons, responsive navigation and fixed mobile call/estimate actions.
- Rule-based preset virtual assistant with question chips and keyword-matched typed questions. It is not presented as generative AI: there is no LLM API or backend.
- The estimate form prepares an email draft addressed to the public business email. It does not store leads or claim that an email was sent.

## Review research and attribution

The public website identifies the target business as Joana's Cleaning at 509 McMichael Pl, Hillside, NJ 07205, phone (862) 290-8386 and info@joanacleaning.com.

Search results for the Hillside listing surfaced a Thumbtack profile showing a 5.0 rating from 6 reviews and short reviews including “very professional and meticulous,” “Nice work,” and “Buena calidad.” Those excerpts are attributed to Thumbtack and link to that listing.

A matching Google Business Profile for the exact Hillside business could not be confirmed. Reviews from a similarly named business in Avondale, Arizona are not used on this site because they cannot be attributed to the Hillside business. Once the owner supplies the exact Google Business Profile URL, the review CTA can be updated and only verified reviews from that profile added.

## Run locally

Open `index.html` in a browser or serve the repository root with a static web server.

## Before production launch

1. Ask the owner to approve imagery, service descriptions, eco-product statements, service area, opening hours, and claims such as licensed/insured.
2. Replace stock images with real, owner-approved photos of the team and completed cleans.
3. Obtain the exact Google Business Profile link before adding Google review counts, ratings or quotes.
4. Test the quote form with a desktop and mobile email application; because it uses `mailto:`, behavior depends on the visitor having an email app configured.
5. Test the responsive layout on common phone widths and verify the horizontal gallery interaction on desktop.
6. Confirm the phone/email routes and have the owner test a real inquiry.
7. Confirm the Vercel deployment and production-domain configuration before replacing the existing website.

The photos are illustrative stock photography and are not claimed to document Joana's Cleaning's actual work.
