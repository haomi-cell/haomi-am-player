# HAOMI AM Player
Player + renderer preset Alight Motion di browser. by xMSHaomi

Fitur target:
- Import preset AM: file XML / link alight.link / Google Drive
- Render WebGL (Canvas 2D fallback) — shape, transform, keyframe, media slots
- Edit manual: ganti media slot, musik, waktu mulai
- Export MP4 via WebCodecs

Struktur:
- public/  → frontend statis (Cloudflare Pages/Workers)
- engine/  → parser XML AM + renderer

Lisensi: MIT (c) xMSHaomi
