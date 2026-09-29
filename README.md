# CloudVault Omni ☁️📱

**BlackBerry-style multi-cloud free storage maximizer**

Maximize free cloud storage across **Apple iCloud (5 GB)** + **Google Drive (15 GB)** + **Microsoft OneDrive (5 GB)** = **35 GB free pool** using classic BlackBerry techniques:

- Aggressive **Content Compression** before upload
- **Best-fit routing** (files go to the provider with the most free space)
- Keep free space high (local GC + live pool calculator)

## Make it work + Install on your phone (free)

### 1. Enable GitHub Pages (one-time, 30 seconds)

1. Open this repo: https://github.com/aross197/CloudVault-Omni
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Build and deployment** → **Source**, choose **GitHub Actions**
4. Save / wait a few seconds

The workflow will automatically deploy the site.

### 2. Open the live site

After the first deploy finishes (usually 1–2 minutes):

**https://aross197.github.io/CloudVault-Omni/**

### 3. Add to your phone home screen (free PWA)

- **iPhone (Safari)**  
  Open the link above → Share button → **Add to Home Screen**

- **Android (Chrome)**  
  Open the link → Menu (⋮) → **Install app** or **Add to Home screen**

No App Store / Play Store needed. Completely free.

## Features

- Unified free-tier storage pool calculator
- Drag-and-drop staging with automatic BlackBerry-style compression
- Manual aggressive image optimizer (quality + max dimension)
- Best-fit automatic routing across providers
- Local cache + garbage collection button
- Fully client-side (works offline for the UI)

## Local use

Just open `index.html` in any modern browser, or run:

```bash
npx serve .
```

## License

MIT
