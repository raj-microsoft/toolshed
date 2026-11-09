# The Toolshed

An interactive pegboard of the 15 entries from **15 Free Google AI Tools**, credited by the [AI Web Design Library](https://raj-microsoft.github.io/ai-web-design-library/) to Amir Afridi + 2 more. [Original table](https://forested-beet-e72.notion.site/List-of-Free-Google-AI-Tools-3a8a26434b34802e9ea6c4a2c714ef71?pvs=73).

**Live:** https://raj-microsoft.github.io/toolshed/

Describe a job, filter the shelf, and follow an official link. Matching is transparent client-side keyword matching, not an AI API. No analytics, cookies, keys, remote fonts or runtime dependencies.

## Run

Serve `docs` using any static server, for example `python -m http.server 8833 --directory docs`. GitHub Pages serves `/docs` on `main`.

## Accuracy

This preserves all 15 guide records without repeating the guide title as a current free-tier guarantee. Official pages checked 9 November 2026: Mixboard's experiment ended; Gemini CLI and Gemini Code Assist consumer access changed; Google Labs now calls NotebookLM Gemini Notebook. These entries carry source notes, and the three changed-access records are excluded from recommendations. Links, descriptions and dates are in `docs/tools.js` and the page footer. Editorial groups and keywords are not Google's taxonomy.

## Verification

`test.cjs` uses the host's installed Playwright Core and Edge. Adjust its library/executable paths on other machines. Checks 15 cards, example ranking, filters, empty results, clear, safe HTML-like input, HTTPS official links, 390px overflow, reduced motion and JS errors. Impeccable detector: zero findings after increasing small text. Desktop/mobile screenshots manually inspected. Design review and tokens: `DESIGN.md`.

Original SVG geometry; AI-generated pegboard, paper and hook imagery made with ChatGPT image generation (9 November 2026). Responsive quality-78 WebP assets; 960/1536px board, 480/960px hook, shared paper and board/wood crops. Gentle 4.5-second daylight shift runs locally in CSS; no Veo or video. Reduced motion keeps the materials still. Barlow Condensed by Jeremy Tribby (SIL OFL included). Independent project, not affiliated with Google. No Google logos or product imagery.

## Photoreal pass

The wooden frame and perforated board replace the drawn board, and fine paper fibers replace flat card surfaces. The original symbols remain deliberately geometric for fast recognition, not provider branding. All card text is HTML; `docs/tools.js` and `docs/app.js` are unchanged. Source provenance and payload details: `docs/assets/PROVENANCE.md`.
