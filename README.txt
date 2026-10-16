PROJECT ASCENSION — Android-friendly PWA

Files: index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png.

EASIEST TEST: Upload the entire project-ascension folder to an HTTPS static hosting service (e.g. Netlify Drop or Cloudflare Pages). Open the HTTPS URL on your Android phone in Chrome. In Chrome's menu choose Install app or Add to Home screen. The app will then work offline after its first successful load.

Alternatively, on a computer, run python -m http.server 8000 in this folder and open http://localhost:8000 to preview it on that computer. Installation and service worker functionality require HTTPS or localhost; opening index.html directly as a file will not enable offline installation.

All progress is stored in localStorage on the same browser and origin. Use Export Backup in Settings regularly; browser storage can be cleared by the OS or user. The app has no account, cloud sync, analytics, ads, or backend. It is a personal prototype, not a production release. Test carefully before public launch.

Quests reset at local midnight. A completed quest can be unchecked the same day to reverse XP. Deleted custom quests keep XP earned in prior days. XP ranks: E levels 1–5, D 6–12, C 13–22, B 23–34, A 35–49, S 50+.
