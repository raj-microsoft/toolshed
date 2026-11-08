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
