RIFFRAFF PHONE CONTROLLER — DESIGN STUDY 01 / COPY REVISION 0.2
15 October 2026

Open index.html or the GitHub Pages review site:
https://colemanimation.github.io/riffraff-phone-mockups/

Open controller.html for the standalone phone preview. Enter DEMO.
Use the screen selector to jump between all 12 design states.
Open qr.html to display the working clay/foam QR invitation.
Read system.html for the proposed architecture and reference.html for source mapping.

SCOPE
Static pre-production mockups. No live multiplayer connection, backend, camera,
microphone, real score calculation or runtime integration. Timers are static examples.
Sample player names, prompts and scores are illustrative.
Drafts and settings use this tab's session storage. No player content leaves the browser.
The QR links to the public phone demo, not to a live room.

DESIGN
Quiplash 3 phone layout and material direction were examined through official
public controller files, then reinterpreted with RiffRaff art. Its source/assets
are reference-only and are not distributed here.
Existing RiffRaff logo, eight character previews and clay waves are copied intact.
Original artwork remains authoritative; this does not approve new character designs.
Ziggy remains voice only. Royale retains RiffRaff's shared prompt and three tokens.
Rokkitt is an open font from Google Fonts; license: assets/Rokkitt-OFL.txt.
Offcut production typography remains a separate project task.

FLAVOR COPY
Ziggy's display copy uses delighted authority, petty congratulations, mock concern
and theatrical judgment. He is enjoying being in charge. The humor targets generic
confidence, effort and indecision; it does not imply knowledge of a player's answer.
Keep gameplay instructions, receipts, connection status and accessibility labels clear.
The tone is original to Ziggy, with no borrowed character identity or quotations.
This copy pass does not revise the existing recorded voice scripts or audio.

NEW QR ART
The blue foam / tangerine clay frame was made with the built-in image-generation
tool. The final prompt and source provenance are in the local design handoff.
The code is generated as SVG with four-module quiet zone and high error correction.
Foam decoration stays outside the code's quiet zone.

SYSTEM
Chosen prototype direction: phone browser + Cloudflare Worker and Durable Object
room authority over WebSocket. Existing Hearth PeerJS/WebRTC media remains separate.
GitHub Pages hosts this review. Cloudflare Pages remains the proposed live frontend.
No production Cloudflare service or domain has been created by this design pass.
Standalone RiffRaff versus Hearth-activity shipping remains unresolved.

LOCAL DEVELOPMENT
No build step, package installation or runtime library is required by the site.
Serve this directory with a static HTTP server. Keep all paths relative so GitHub
Pages project-subdirectory hosting works. Edit HTML, CSS and JS, then republish.
No secrets or environment variables belong in this public directory.

REVIEW BOUNDARY
Desktop-browser responsive checks and automated QR decoding are not proof of
physical phone, assistive-technology, television-camera scanning or live-room behavior.
Those checks are listed in system.html as implementation acceptance gates.
