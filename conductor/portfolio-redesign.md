# Implementation Plan: Dark Night City Portfolio Redesign (kiro.city)

## Objective
Execute a complete visual overhaul of `Portfolio.html` transitioning from the Brutalist-Manga style to a premium, authoritative "Dark Night City" aesthetic (Black and Gold tones, evoking a high-end bank or elite technical institution). The layout will be reordered, custom animations added, and specific assets integrated.

## Key Files & Context
*   **Target File:** `Portfolio.html` (Complete rewrite of styling and structural adjustments).
*   **Assets:**
    *   Hero Image: `uploads/View recent photos.png`.
    *   Cursor Image: `../paper_airplane.png` (mapped for the custom cursor).
*   **Framework:** Tailwind CSS (via CDN) with extensive custom CSS for theme and scroll animations.

## Aesthetic Direction: "Dark Night City"
*   **Background:** Deep blacks (`#050505` to `#0A0A0A`) representing the night sky/city shadows.
*   **Accents:** Premium Gold/Amber (`#D4AF37`, `#F3E5AB`, or a glowing neon gold) representing city lights and luxury.
*   **Typography:** Moving away from heavy brutalism. Retaining Bebas Neue for impact but pairing it with sleek, elegant sans-serifs (like Inter with wider tracking) to feel authoritative and precise.
*   **Vibe:** High-end, technical, "like a bank" but built for a founder/architect.

## Implementation Steps

1.  **Global Setup & Custom Cursor:**
    *   Set the `body` and globally interactive elements to use the `../paper_airplane.png` as a custom cursor.
    *   Apply the deep black background and gold text/border accents.

2.  **Hero Section (Landing Page):**
    *   **Layout:** Maintain the 3-element whiteboard structure (Text, Image, Credentials box).
    *   **Text Disintegration Animation:** Implement a scroll-linked animation on the "Hi, I'm Kiro" text. As the user scrolls down, use CSS (e.g., varying opacity, `filter: blur()`, and `transform: translateY()`) to make the text appear to disintegrate or dissolve into the city night.
    *   **Credentials Box:** Replace the text list ("MIT, QB, EGYPT...") with logo placeholder grids (e.g., sleek gold-outlined circles or boxes) to hold future SVGs.
    *   **City Glow Element:** Add a subtle, blurred radial gradient behind the hero section to mimic distant city lights.

3.  **Section Reordering:**
    *   **1st:** Hero Landing Page.
    *   **2nd:** Active Operations (Projects) - Moving this *before* the timeline.
    *   **3rd:** Journey Timeline - Keeping the scroll-progress line but restyling it to fit the black/gold theme (e.g., gold progress line).
    *   **4th:** Dossier Profile (About & Tech Stack) - Dark theme styling.
    *   **5th:** Final Chapter (Footer).

4.  **Styling the "Active Operations" & Timeline:**
    *   Convert the brutalist borders into sleek, glowing gold borders or subtle dark-grey cards with gold hover states.
    *   Timeline dots will pulse with a gold accent rather than white/blue.

## Verification & Testing
*   Verify the custom cursor applies correctly.
*   Test the scroll-disintegration effect on the Hero text.
*   Ensure the section order is Hero -> Projects -> Timeline.
*   Confirm the black and gold "bank-like" aesthetic is consistent across all viewports.

<!-- easymd:log -->
## 🧾 Activity
- agent replaced the document (3222 chars)
- agent replaced the document (3322 chars)
- agent replaced the document (3365 chars)
<!-- /easymd:log -->
