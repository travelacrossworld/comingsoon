# Travel Across World — Coming Soon

The official **Coming Soon** landing page for [Travel Across World](https://travelacrossworld.com), a global travel platform being developed to connect the full journey—from the first travel dream to the memories brought home.

**Tagline:** Explore Without Limits.

## Project status

This repository contains **Phase 0 only**: the public Coming Soon page.

It is a visual and informational landing page, not the final booking platform. The complete Travel Across World website will be planned and developed separately with secure server-side processing, customer inquiries, database storage, authenticated email delivery, administration tools, supplier and travel APIs, monitoring, backups, testing, privacy controls and future booking workflows.

## Current page highlights

- Clean white-background travel theme
- Responsive desktop, tablet and mobile layouts
- Accessible keyboard focus and reduced-motion support
- Travel-specific sections for:
  - Flights
  - Hotels and stays
  - Holidays and escapes
  - Taxis and airport transfers
  - Visas and travel readiness
  - Travel protection
  - Activities and local experiences
- Emotional brand positioning focused on memories, not only transactions
- Direct contact link to `adventure@travelacrossworld.com`
- No frameworks, external libraries or paid dependencies
- No customer data collection or backend processing

## Design direction

The approved design foundation is:

1. Modern and trustworthy first
2. Premium second
3. Friendly and family-focused third

The main page uses a white canvas with controlled travel- and nature-inspired accents, including Deep Ocean, Horizon Blue, Lagoon Teal, Forest Trail, Warm Sand and limited Sunset Coral.

The experience is intended to feel like a modern international airport, premium airline lounge, refined travel agency or welcoming hotel reception—not a generic software dashboard.

## Repository structure

```text
comingsoon/
├── index.html   # Complete Coming Soon page with HTML, CSS and JavaScript
└── README.md    # Project information and deployment guidance
```

## Run locally

No installation is required.

1. Download or clone this repository.
2. Open `index.html` in Chrome, Edge, Firefox or Safari.
3. Review the page at desktop and mobile screen sizes.

Because the page is self-contained, no development server, package manager or build command is required.

## Production deployment

The approved production hosting provider is **Hostinger**, with the public web root:

```text
public_html
```

The deployed structure must be:

```text
public_html/
└── index.html
```

### Hostinger upload steps

1. Sign in to Hostinger hPanel.
2. Open **Websites → Manage → File Manager**.
3. Open the `public_html` folder.
4. Back up the existing production file before replacing it.
5. Upload this repository's `index.html` directly into `public_html`.
6. Confirm the filename is exactly `index.html`.
7. Confirm the file permission is normally `644`.
8. Open the website in a private or incognito browser window and test it.

A filename such as `travelacrossworld.comindex.html` will not be recognized as the default homepage and can result in a **403 Forbidden** response.

## Deployment checks

After publishing, confirm:

- `https://travelacrossworld.com` opens correctly
- HTTPS works without browser warnings
- The white layout matches the approved design
- Navigation buttons scroll to the correct sections
- The contact email opens the visitor's email application
- The page works on desktop and mobile
- There is no horizontal overflow
- Keyboard focus is visible

## Contact

**Travel Across World**  
Email: [adventure@travelacrossworld.com](mailto:adventure@travelacrossworld.com)  
Website: [travelacrossworld.com](https://travelacrossworld.com)

## Security and privacy

This static page does not store inquiries, collect payment information, connect to a database or contain private API credentials.

Never commit or upload passwords, SMTP credentials, database credentials, API keys, access tokens, `.env` files, backups, customer records or private business documents to this public repository or to Hostinger's `public_html` folder.

Future forms and integrations must use secure server-side processing. Browser-only JavaScript and `mailto:` links are not suitable as the final production inquiry system.

## Ownership and permitted use

Copyright © Travel Across World. All rights reserved.

No open-source license has been granted for this repository. The code, copy, visual system and brand materials may not be reused, redistributed or represented as another business's work without written permission from Travel Across World.
