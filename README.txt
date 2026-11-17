VAJO.COM — PLAYFUL DASHBOARD PAGE
==================================

WHAT THIS IS
------------
A ready-to-upload static website: the playful "German made easy, made fun"
dashboard page for vajo.com. No server-side code required — any web server
(or a plain folder on your existing host) can serve it.

CONTENTS
--------
index.html              The page (open this)
assets/                 JS, CSS and all optimized images (WebP)
icon-192.png            App icons (PWA / home-screen install)
icon-512.png
manifest.webmanifest    PWA manifest
sw.js                   Service worker (offline caching, best-effort)
vajo-home-button-snippet.html
                        Floating "Home" button for your OTHER vajo.com
                        pages — open it for instructions, set HOME_URL,
                        paste the snippet before </body> site-wide.

DEPLOY
------
Upload ALL files and folders to your web space, keeping the structure.
Works at a domain root (e.g. go.vajo.com) or in a subfolder
(e.g. vajo.com/adventure/) — all paths are relative.

NOTES
-----
- The 12 step cards link straight into the member dashboard tools
  (/membership/dashboard.php#... deep links, /chatroom/index.php,
  /video-hall/lesson.php?course=german-grammar, /extension-guide.php).
  Guests will see the login prompt — by design, it's a signup nudge.
- The "Daily Plan" checklist stores progress in the visitor's own browser
  (localStorage) and resets daily. No backend needed.
- All images are compressed WebP; the whole site is ~1.6 MB with
  lazy-loading, so first paint is fast even on slow connections.
- Fonts (Londrina Solid + Nunito) load from Google Fonts; the page still
  works if a visitor blocks them (system-font fallback).

Built 2026-11-17. Questions → regenerate anytime from the Kimi project.
