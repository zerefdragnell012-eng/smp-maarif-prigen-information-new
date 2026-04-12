# The Design System: Editorial Excellence for SMP Ma'arif Prigen

## 1. Overview & Creative North Star: "The Sacred Contemporary"
The Creative North Star for this system is **"The Sacred Contemporary."** 

We are moving away from the "template" look of traditional school websites. Instead of a rigid grid of boxes, we treat the landing page as a high-end editorial publication. This system balances the weight of Islamic tradition (The Sacred) with the lightness of modern academic excellence (The Contemporary). We achieve this through:
- **Intentional Asymmetry:** Breaking the vertical axis with overlapping images and offset text.
- **Tonal Depth:** Using layered greens and gold accents rather than flat color blocks.
- **Breathing Room:** Utilizing aggressive whitespace to signal prestige and calm.

---

## 2. Colors: Depth & Soul
Our palette transitions from the deep, scholarly `primary_container` (#06402B) to the vibrant, growth-oriented `secondary` (#236A53).

### The "No-Line" Rule
**Explicit Instruction:** Do not use 1px solid borders to define sections. In this system, boundaries are "felt, not seen." 
- Define sections through background shifts (e.g., moving from `surface` to `surface_container_low`).
- Use the **Signature Gradient** (`primary` to `primary_container`) for large hero areas or deep-section backgrounds to add "visual soul."

### Surface Hierarchy & Nesting
Treat the UI as physical layers of "Frosted Emerald" and "Fine Vellum."
- **Level 1 (Base):** `surface` (#F8F9FF).
- **Level 2 (In-page Containers):** `surface_container_low` for subtle grouping.
- **Level 3 (Interactive Cards):** `surface_container_lowest` (#FFFFFF) to create a soft, natural lift.

### Glassmorphism & Gold
- **Glass Effect:** Use `surface_variant` at 40-60% opacity with a `backdrop-filter: blur(20px)`. Add a 1px white inner shadow (top-left) to mimic the edge of glass.
- **Gold Accents:** Use `tertiary_fixed_dim` (#E9C176) sparingly for "moments of excellence"—QR code frames, merit badges, or the handwritten slogan.

---

## 3. Typography: The Intellectual Voice
We pair the geometric precision of **Plus Jakarta Sans** with the approachable clarity of **Inter**, accented by a custom script for the school’s soul.

- **Display (Plus Jakarta Sans):** Large, bold, and authoritative. Use `display-lg` for the hero statement. The wide tracking and generous leading signal a modern, premium institution.
- **The Slogan (Handwritten/Script):** The slogan *'Yo Sekolah, Yo Ngaji!'* must be treated as a visual mark, not just text. It should overlap images or "float" near the hero headline in `tertiary_fixed_dim`.
- **Body (Inter):** High legibility. Use `body-lg` for introductory paragraphs to maintain an editorial feel.
- **Labels (Inter):** Uppercase with 0.05em letter spacing for small technical details or "National Curriculum" tags.

---

## 4. Elevation & Depth: Tonal Layering
Traditional shadows are too heavy for this "Clean & Modern" style. We use **Tonal Layering.**

- **The Layering Principle:** Instead of a shadow, place a `surface_container_highest` element onto a `surface` background. The color delta provides enough contrast to imply elevation.
- **Ambient Shadows:** Only for floating elements (like the QR Code modal). Use a blur of 40px and a 6% opacity shadow tinted with `primary` (#002819) to ensure the shadow feels like a natural part of the green environment.
- **The "Ghost Border":** If a border is required for a form field, use `outline_variant` at 20% opacity. Never use 100% opaque black or grey borders.

---

## 5. Components: The Building Blocks

### Buttons
- **Primary:** `primary_container` background with a subtle gradient to `primary`. Large corner radius (`xl`: 3rem/48px) for a "pill" look that feels friendly yet professional.
- **Secondary (The Gold Standard):** `surface_container_lowest` with a `tertiary_fixed_dim` (Gold) text color. Use this for high-conversion CTAs.

### Cards & Lists
- **The "No-Divider" Rule:** Forbid the use of 1px horizontal lines. Separate list items using 16px or 24px of vertical whitespace (from the spacing scale).
- **Glass Cards:** Use for "Latest News" or "School Features." Apply the 20px (`md`) corner radius and the white inner shadow for the glass effect.

### Input Fields
- Use `surface_container_low` as the background. On focus, transition the background to `surface_container_lowest` and apply a thin `primary` "Ghost Border" at 40% opacity.

### QR Code Frame
- This is a prestige element. Frame the QR code with a 2px `tertiary_fixed_dim` (Gold) border and a large `lg` (2rem) corner radius. Surround it with a Glassmorphism container.

---

## 6. Do’s and Don’ts

### Do:
- **Do** overlap images with text. Have a student's shoulder "break" the container of the text box to create 3D depth.
- **Do** use the `tertiary` (Gold) tones strictly for highlights. It should represent the "Islamic Value" and "Excellence" portion of the design.
- **Do** use the `20px` radius as your default for all containers to maintain the "Modern & Clean" friendliness.

### Don’t:
- **Don’t** use pure black (#000000). Use `on_surface` or `primary` for text to maintain the sophisticated green-tinted depth.
- **Don’t** use standard "Material Design" blue for links. Every interactive element must stay within the Green/Gold/White spectrum.
- **Don’t** overcrowd. If a section feels "busy," increase the vertical padding by 2x. Prestige lives in the space between elements.