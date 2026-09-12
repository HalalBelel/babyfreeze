BABY VIDEOS PWA
===============

WHAT IT DOES
- Home screen contains only 5 large YouTube video tiles.
- Tap a tile to start that video.
- Video loops indefinitely.
- Playback screen blocks normal taps, swipes, seeking and YouTube controls.
- It requests fullscreen, landscape orientation and a screen wake lock where the browser supports them.
- If fullscreen is dismissed, a later tap on the video area tries to restore it.
- It traps the in-page Back action while protected mode is active.

PARENT EXIT
Hold BOTH TOP CORNERS of the video screen at the same time for 4 seconds.
A small progress line appears while the gesture is being held.

INSTALLING AS A PWA
A PWA must be served from HTTPS (or localhost). It will not install properly by double-clicking index.html as a file.
Upload this folder to any HTTPS static host such as GitHub Pages, Cloudflare Pages, Netlify, your own HTTPS web server, etc. Then open the site on the phone and choose the browser's Add to Home Screen / Install App option.

IMPORTANT LIMITATION
No ordinary website/PWA can disable the phone's physical Home/Power buttons, app switcher, notification shade, operating-system gestures, or every browser-level exit. For the strongest protection, combine the installed PWA with the phone's OS-level child/kiosk feature (for example Guided Access on iPhone/iPad or App Pinning/Screen Pinning on Android).

YOUTUBE
The app shell can be cached, but YouTube playback still requires an Internet connection and depends on YouTube allowing the videos to be embedded.
