# Carhub Detailing

English responsive website demonstration for Carhub Detailing in Ballincollig, Cork.

## Run locally

Requires Node.js. Run `npm start`, then open http://127.0.0.1:4173.
The entire deployable website is in `dist/`. No build step is required. Fonts, images and GSAP scripts are served locally.

## Included

- Responsive editorial design, cinematic automotive hero, Outfit typography and blue accents.
- Four expandable service descriptions with quote selection.
- An illustrative AI-generated hero and two real Porsche photographs supplied by the user.
- GSAP image scaling and scrubbed text, with reduced-motion alternatives.
- Native FAQ disclosures, mobile navigation, telephone and Google Maps links.
- Client-side quote builder with required-field validation, copy action and WhatsApp message link.
- Privacy dialog explaining the demonstration and its data handling.

## Contact behaviour

The quote builder prepares a message locally. It does not submit information to a server, send messages, or confirm a booking. A visitor can copy the message or open a supported messaging application and decide to send it. WhatsApp links use the business number +353 85 820 6301 as requested by the user; no test message was sent. No appointment system, mail delivery, analytics or marketing cookies are configured.

## Before a public business launch

The results gallery uses the two business photos supplied by the user. The hero remains illustrative. Confirm branding, services, opening hours, contact details and copy with the owner. Choose and connect the preferred enquiry channel if automatic delivery is wanted. Replace the demonstration privacy text with the final site's actual processing information, and remove `noindex` only when the business approves public indexing. Add canonical and social sharing URLs for the approved business domain.

The current Site is a private design demonstration. It is not the company's approved official website. No reviews, certifications, fixed prices, coating warranties or service outcomes were fabricated.

## Sources and design assets

Business details were supplied in the brief and cross-checked on 19 November 2026 against https://locufy.com/ie/companies/carhub-detailing-professional-detailing-and-valets and https://locallyirish.ie/car-valeting. Listings may change; review counts are deliberately not hard-coded.

Images were generated using the built-in image generation tool. Prompts and local asset paths are documented in `IMAGE-PROMPTS.md`. The generated logo is a simple editable vector concept, not a supplied official mark. Outfit is distributed under the SIL Open Font License; GSAP retains its distributed licence notices.

## Verification

Checked in the Codex browser at desktop and 390px mobile widths: image loading, horizontal overflow, service-to-form selection, generated quote text, FAQ expansion and privacy modal. JavaScript syntax checked with Node. Telephone, SMS and Maps destinations are linked; no live enquiry was sent to the business.

## November 19 update

Changed the full green palette to blue; added WhatsApp icon links and generated quote messages; replaced the results gallery with the user-supplied Porsche exterior and interior photos. Added three brief, attributed five-star Google review excerpts, verified live on Google Maps on 19 November 2026: S LS (லி), Slavyan Sabinov and Cian O’Sullivan. Source: https://www.google.com/maps/search/?api=1&query=Carhub+Detailing+Ballincollig+Cork
