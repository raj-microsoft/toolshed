# The Toolshed design system

## Built direction
User-pinned physical pegboard expressed through pale sage perforation, dimensional hanging cards, original geometric icons and a single hook-swing response. Standard search and category buttons keep the working interface familiar.

## Tokens
Deep green #183f36; deeper ink #113329; warm white #f6f7ee; sage board #c6d4bb; holes #9ba98f; yellow action #f4d964. Barlow Condensed SemiBold self-hosted for headings; Segoe UI/Arial for body. Labels >=12px, descriptions 14px. Cards use 12px corners, soft offset shadows and no border. Board uses its own structural 8px frame.

## Layout
1440px: horizontal introduction and task field, filters above a five-column board. At 1150px three columns; at 760px stacked controls and two columns; at 480px one column. Mobile task entry, examples and filter order remain identical. No content is hidden for small screens.

## Behavior
Matching is local, debounced keyword matching, also submit-triggered. Active recommendations sort first, turn pale yellow and swing once; unavailable/changed consumer entries never earn a recommendation. Match reasons explain the rule. Group selection is aria-pressed; results are aria-live. Empty results preserve browsing and give concrete recovery suggestions. Inputs render no user-supplied HTML. Reduced motion removes animation/transitions. Keyboard focus, caret, selection, and scrollbars use the palette.

## Finish review
In-thread review because this assigned researcher workflow prohibits further delegation. Inspected Edge desktop and mobile captures. Verdict: passes the pinned concept and practical picker task. Fixed detector's tiny-text finding, then detector returned []. Tested all 15 cards, keyword ranking, filters, empty recovery, reset, HTML-input safety, links, reduced motion and mobile overflow. No shipping raster imagery; icons are original geometric SVG; font OFL is included. Source status changes are visible and linked. Long mobile board is intentional; filters shorten it.

## Photoreal update — 9 November 2026
Three ChatGPT-generated stills supply the real oak-framed sage pegboard, low-contrast paper fibers and a hanging-hook material study. Board image has 960/1536px responsive sources; cropped board/wood materials extend the long mobile wall without stretching its perforations. Blank textures keep all text accessible HTML. The existing geometric SVG icons remain intentionally drawn: readable editorial navigation, not Google branding. Facts, official URLs, ranking code and hook-swing logic are unchanged.

Local CSS daylight shift ends after 4.5 seconds; reduced motion removes it and the swing. Fixed the detector's added colored inset shadow and restored the original sage-white page palette; detector now returns []. Headless Edge behavior tests passed at 390px/1440px, including responsive image loading, lazy hook image, no overflow and no JS errors. Generated stills visually inspected and SHA-256 checked distinct. Payload/provenance: docs/assets/PROVENANCE.md.
