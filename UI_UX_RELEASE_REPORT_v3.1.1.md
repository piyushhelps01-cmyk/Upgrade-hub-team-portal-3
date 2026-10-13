# UI/UX Preview & Styling Fix — v3.1.1

## What changed
- Added a standalone, single-file `preview/UpgradeHub_UI_Preview.html` with embedded CSS and a preview-only interaction layer. It opens directly in a modern browser without npm, server setup or credentials.
- Included static-data screens for the Founder overview, task Kanban, team directory, approval centre, audit/security and system operations. Sample data is labelled as preview-only.
- Included desktop/mobile screenshots for an immediate visual reference.
- Fixed browser-native grey/button border styling for project-focus rows and upcoming task rows in the real app stylesheet.
- Updated release version to v3.1.1.

## Verification completed
- Rendered the standalone HTML in headless Chromium with the embedded stylesheet.
- Verified dashboard render with 5 metric cards and 8 featured module cards.
- Verified click navigation to task Kanban (4 lanes) and team directory (6 sample rows).
- Verified module search returns filtered cards.
- Verified 390px mobile layout has no horizontal page overflow (`scrollWidth` equals `clientWidth`).
- These are visual/static-preview checks, not authenticated browser testing of a live backend.

## Important limitations
- The standalone preview uses fabricated sample data, has no database/API connection and does not persist changes.
- The real portal needs the Node.js setup from `README.md`. The UI preview is not a deployed public website.
- This report does not claim all 300 checklist items or all 40 workspaces are production-ready. Review the implementation and release-readiness matrices before using sensitive company data.
