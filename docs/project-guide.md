# Project guide

## Overview

This project is a static landing page for the Lexus LFA White Symphony concept. It uses a
hero section with metadata and a visual frame, followed by a three-panel grid that highlights
carbon-fiber construction, the V10 engine, and the Nürburgring package.

## Layout walkthrough

- **Hero section**: two-column grid with copy on the left and the image treatment on the
  right. The CTA is styled as an outlined pill button with a hover inversion.
- **Metadata grid**: nested grid inside the hero copy that lists key specs.
- **Gallery panels**: three cards built with a glassmorphism effect and consistent typography.

## Customization tips

- Update the hero image by editing the `src` attribute in `index.html`.
- Adjust the mood by changing the radial gradient in `styles.css` under `body`.
- The typography scale is controlled by the `h1` clamp values in `styles.css`.

## Accessibility notes

- The hero image includes descriptive alt text. Keep alt text specific to the image if you
  replace it.
- Make sure color contrast stays readable if you update background or text colors.

## Suggested next steps

- Add additional gallery panels for interior shots or engineering details.
- Include a footer with credits or a call-to-action.
