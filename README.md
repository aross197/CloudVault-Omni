# CloudVault Omni ☁️📱

**BlackBerry-style multi-cloud free storage maximizer**

Maximize your free cloud storage across **Apple iCloud (5 GB)**, **Google Drive (15 GB)**, and **Microsoft OneDrive (5 GB)** — total **35 GB free pool** — using classic BlackBerry techniques:

- **Content Compression** (aggressive client-side image & file reduction)
- **Best-fit routing** (always send files to the provider with the most free space)
- **Keep free space high** (local garbage-collect + live pool calculator)

## Live Demo / Install on Phone (Free)

1. Visit the GitHub Pages site (enable it below if not already live):  
   **https://aross197.github.io/CloudVault-Omni/**
2. On **iPhone (Safari)**: Share → Add to Home Screen  
3. On **Android (Chrome)**: Menu → Install app / Add to Home screen  

It works as a free Progressive Web App (PWA) — no App Store, no payment.

## Features

- Unified free-tier storage pool calculator
- Drag-and-drop staging with automatic BlackBerry-style compression
- Manual aggressive image optimizer (quality + max dimension controls)
- Best-fit automatic routing across providers
- Local cache + garbage collection
- Fully client-side (no backend required)

## Quick Start (Local)

```bash
# Just open the file
open index.html
# or serve it
npx serve .
```

## Enable GitHub Pages (so you can install on your phone)

1. Go to the repo → **Settings** → **Pages**
2. Under "Source" choose **Deploy from a branch**
3. Branch: `main` / folder: `/ (root)`
4. Save. After ~1 minute the site will be live at:  
   https://aross197.github.io/CloudVault-Omni/

## License

MIT
