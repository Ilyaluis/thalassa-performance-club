# THALASSA Performance & Wellness Club

## Overview

THALASSA is a polished, single-page portfolio concept for a premium fitness, recovery and coastal-living club imagined for Limassol, Cyprus. It is built as a dependency-free static website that can be opened directly or served with Live Server.

> **Fictional-business disclaimer:** THALASSA is entirely fictional. The club, team, address, telephone number, email, prices, schedules, memberships, testimonials, events and forms are all demonstration content. No form data is sent anywhere.

## Design concept

The art direction is warm, spacious and Mediterranean rather than a conventional dark gym aesthetic. Warm ivory, limestone, muted sea-glass and Mediterranean blue frame editorial serif typography, generous whitespace, coastal photography and quiet utility.

The geographic concept is Limassol's coastal district, intended for international residents, professionals, entrepreneurs, active couples and long-term visitors.

## Technologies

- Semantic HTML5
- Modern CSS3 with custom properties and responsive media queries
- Vanilla JavaScript
- Google Fonts (Playfair Display and DM Sans)
- Remote Unsplash editorial photography, easy to replace with local files in `images/`

## Implemented features

- Sticky, scroll-aware header and responsive mobile navigation
- Current-section navigation state and smooth anchor scrolling
- Editorial club-space, recovery, coaching and lifestyle sections
- Keyboard-accessible programme tabs
- Interactive class schedule with day, type, intensity and setting filters
- Membership concepts and visitor-access information
- Keyboard-accessible testimonial controls
- Accessible event and journal preview dialog with focus restoration
- Fully validated demonstration club-tour form with inline live feedback
- Back-to-top control, Escape-key handling and reduced-motion support
- Clear fictional-project disclosures throughout the experience

## Accessibility

The page includes one logical `h1`, landmark elements, labelled form controls, descriptive image alt text, visible focus styles, keyboard-accessible controls, mobile-menu state announcements, an accessible dialog, `aria-live` form feedback and a reduced-motion media query.

## Responsive behaviour

The layout adapts for 320 px mobile screens through wide desktop displays. Card collections collapse appropriately; the club-spaces rail becomes horizontally scrollable on smaller screens; filters and form controls remain touch-friendly.

## Project structure

```text
.
├── index.html      # Content and semantic structure
├── style.css       # Art direction and responsive layout
├── script.js       # Interactions, filtering and validation
├── favicon.svg
├── images/         # Reserved for replaceable local photography
└── icons/          # Reserved for future local icon assets
```

## Local launch

1. Open `index.html` directly in a modern browser; or
2. Open this folder in VS Code and use the Live Server extension.

No packages, installation, compilation or server-side configuration are required.

## Image licensing and attribution

Photography is loaded from Unsplash URLs for this static portfolio demonstration. Review the individual image licence and creator details before publishing a production website. Download approved files into `images/` and update `index.html` with local paths when preparing a deployed version.

| Local filename / reference | Website section | Source page | Photographer |
|---|---|---|---|
| Remote `photo-1571019613454-1cb2f99b2d8b` | Hero | https://unsplash.com/photos/1571019613454-1cb2f99b2d8b | Unsplash contributor (verify before production) |
| Remote `photo-1517836357463-d25dfeac3438` | The Club | https://unsplash.com/photos/1517836357463-d25dfeac3438 | Unsplash contributor (verify before production) |
| Remote `photo-1581009146145-b5ef050c2e1e` | Club Spaces | https://unsplash.com/photos/1581009146145-b5ef050c2e1e | Unsplash contributor (verify before production) |
| Remote `photo-1500534623283-312aade485b7` | Coastal Training | https://unsplash.com/photos/1500534623283-312aade485b7 | Unsplash contributor (verify before production) |
| Remote `photo-1544161515-4ab6ce6db874` | Recovery & Wellness | https://unsplash.com/photos/1544161515-4ab6ce6db874 | Unsplash contributor (verify before production) |
| Remote `photo-1498837167922-ddd27525d352` | Nutrition | https://unsplash.com/photos/1498837167922-ddd27525d352 | Unsplash contributor (verify before production) |
| Remote `photo-1466637574441-749b8f19452f` | Journal | https://unsplash.com/photos/1466637574441-749b8f19452f | Unsplash contributor (verify before production) |

## Links and screenshots

- Live demo URL: _to be added_
- GitHub repository URL: _to be added_
- Screenshots: _to be added_

## Known limitations and future improvements

- The tour form intentionally does not transmit data.
- Schedules and availability are static fictional data.
- Production publishing should replace remote photography with licensed local assets and verified attributions.
- A production version could add a privacy policy, CMS-backed journal, membership API and optional multilingual content.
