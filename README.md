# PhotoPan

Mobile-first motion photo-board editor inspired by tactile postcard/collage boards.

## v0.1.0
- unlimited multi-photo import (practical limit depends on device storage/memory)
- irregular auto-layout with overlap, scale and rotation
- drag individual photos on the board
- per-photo rotation, scale and motion: tremble / float / breathe / sway
- board color and paper/grain/clean material effects
- editable two-line footer title/copyright
- font, alignment, size, tracking, leading, color and opacity controls
- sticky live preview while editing
- IndexedDB persistence for uploaded photos and photo transforms
- localStorage persistence for board/text styles
- PWA service worker with network-first update behavior
- visible app version in header

## Hosting
Designed for GitHub Pages. Enable Pages for the `main` branch root. After deployment, open the Pages URL in iPhone Safari and choose **Add to Home Screen**.

Uploaded photos and project settings stay in the browser on that device; they are not uploaded to a server by this app.