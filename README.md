# Resideline — Prepared-for landing page

A single-page, static site written for Resideline ahead of eMerge Americas 2026 (Booth SMB21). The page opens on the three-strategy AVM orchestration thesis from the fit analysis, then walks through the 60 / 30 / 10 stack read, the Simple Lyfe Stays case, the published Interpretable Context Methodology work, and a direct calendar ask. Brand tokens come straight from the Resideline brand pack (teal primary, Inter, tight vertical rhythm, light-mode first). Eduba branding only appears in the footer, per the shared-chrome rules.

Intended URL path: `/for/resideline`

## Files

- `index.html` — page markup
- `styles.css` — all visual styles, mobile-first, no JS
- `og-image.png` — reference asset copied from the brand pack (no clean Resideline logo mark was available from the public React SPA; a clean, abstract home-glyph wordmark is rendered inline in the header)

## Notes

- CTA points directly at `https://calendly.com/thecro-eduba/30min`, with Matt Creamer named.
- No pricing or revenue terms surfaced. No dollar figures for prior engagements.
- All external URLs are real anchors with `target="_blank" rel="noopener"`.
- NLP Logix mention includes the mandatory credibility line ("in machine learning since 2011," "over 150 data scientists"). Ethics Engine mention includes the mandatory one-sentence bio and links to the arXiv paper and the AuditEngine repo. KPMG is framed as "KPMG UK (Big Four)." The 1,500+ figure is used verbatim.
- No em dashes. No antithesis pattern as a rhetorical device. No performed questions. Prospect voice throughout the body copy.
- Mobile-tested at 375px. Minimum tap target 44px. `prefers-reduced-motion` respected.
