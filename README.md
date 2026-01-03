No Like, Go Home — UI/UX Enhancements

What's included:
- Added base design system with CSS variables, fonts, and spacing.
- Responsive sticky navigation with accessible toggle.
- Hero section with CTAs and responsive imagery.
- Card-based menu grid with product cards and 'Add' actions.
-- Polished chat UI: a floating chat toggle and accessible chat panel UI.
-- Mounted Flowise chatbot inside the custom chat panel (replaced the default floating widget).

Run locally:
1. From the 'testing/testing' folder run a simple server:

```powershell
cd "c:\Users\Paps Leroy\Desktop\testing\testing"
python -m http.server 8000
```

2. Open http://localhost:8000 in your browser.

Notes and next steps:
- Add real images and replace Unsplash placeholders.
- Integrate the Flowise embed into the chat panel if the library supports mounting to a given container.
- Replace stubbed add-to-cart with a simple cart state or server-backed order flow.
- Validate contrast and keyboard navigation using Lighthouse or accessibility tools.

Optional improvements:
- Add aria-live for chat updates and improved focus management (trap focus when chat opens).
- Add a cart summary floating in the bottom-right for faster checkout.
- Add lazy-loading of large images and implement srcset for responsive images.

Credits: This was updated as a lightweight, beginner-friendly UI/UX enhancement to the existing site.
