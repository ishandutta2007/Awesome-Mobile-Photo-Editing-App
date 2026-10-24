# Awesome-Mobile-Photo-Editing-App

# Top Mobile Photo Editing App Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Touch-Optimized Retouching, Batch Processing & Privacy-First Mobile Workflows*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Mobile Photo Editing Apps**. These tools bring pixel-level retouching, filters, cropping, and batch processing to phones and tablets — with a spectrum running from polished commercial apps like Snapseed and VSCO to open-source Android editors like Image Toolbox and Fossify Gallery that run entirely offline.

**Examples** include Image Toolbox, Fossify Gallery, Capy Canvas, and QuickEdit (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, offline processing, and privacy-respecting mobile editing — especially relevant as **Snapseed is no longer in active development** [citation:1], leaving Android users looking for capable open-source alternatives that don't harvest data.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **Snapseed** — **The long-standing free mobile editing standard from Google.** Selective adjustments, healing, HDR, and professional-grade filters with a gesture-driven interface. **No longer in active development** according to community reports, though it remains available [citation:1]. **Trade-offs**: Google ownership and data collection concerns, with an uncertain future. **Best for users** still relying on its familiar workflow while evaluating open-source alternatives.

- **Adobe Photoshop Express** — **Adobe's mobile photo editor.** Core retouching, filters, and Creative Cloud integration. **Free tier with paid Premium**. **Best for Adobe subscribers** wanting mobile access to their ecosystem, accepting subscription upsells and cloud dependency.

- **VSCO** — **The aesthetic-first editing app.** Film-inspired presets, advanced color tools, and a community platform. **Subscription-based** for full preset library. **Best for creators** prioritizing visual style over technical precision.

- **Picsart** — **The all-in-one creative platform.** Photo editing, collage, stickers, AI tools, and social sharing. **Free tier with ads and paid Gold**. **Best for casual creators** wanting broad creative features in one app.

## Open-Source GitHub Projects

- **Image Toolbox** — **The most powerful open-source Android photo editor.** **Open-source (Apache/GPL), available on Play Store and F-Droid** [citation:3][citation:15]. **An entire image manipulation suite** with **over 45 filters, batch processing, background removal (manual and automatic), format conversion (HEIF, AVIF, WebP, JPEG, PNG, SVG), and EXIF metadata editing/removal** for privacy [citation:3]. **Practical professional features**: batch resizing of hundreds of images, compression to specific file sizes, color palette generation, side-by-side image stitching, and image-to-PDF conversion [citation:3]. **On-device AI models** can be downloaded for background removal, equivalent to Google's Object Eraser but with manual selection adjustment [citation:5][citation:15]. **AES-256 GCM encryption** for sensitive images [citation:3]. **Material Design** interface that is modern and intuitive [citation:3]. **The honest caveat**: **it is a toolbox, not a gallery** — you browse tools rather than photos, which takes a moment to learn [citation:15]. **Best for Android photographers** wanting a comprehensive, privacy-respecting editor without subscriptions or ads [citation:3][citation:5].

- **Fossify Gallery** — **The privacy-first Android gallery with built-in editing.** **Open-source (fork of Simple Gallery Pro), available on Play Store and F-Droid** [citation:3][citation:4]. **Basic but capable editor**: crop, resize, rotate, flip, draw, and apply filters [citation:4]. **Privacy-focused**: **no Internet permission requested** — media leaves the device only when you explicitly share it [citation:9]. **EXIF metadata stripping** for GPS and camera details before sharing [citation:3][citation:4]. **Security features**: PIN, pattern, or fingerprint lock for specific photos or the entire app [citation:3]. **Recycle bin** for accidental deletions [citation:3]. **Supports virtually every format**: JPEG, PNG, MP4, MKV, RAW, SVG, GIF, and more [citation:4]. **The honest caveat**: **editing is basic compared to Image Toolbox** — it lacks batch processing, background removal, and advanced filters [citation:3]. **Best for users** wanting a private, ad-free gallery with light editing capabilities [citation:3].

- **Capy Canvas** — **The cross-platform GPU-accelerated painting and photo editing app.** **Open-source, GPU-accelerated with wgpu**, targeting **120+ FPS with brushes thousands of pixels wide** [citation:8]. **Available on Linux, Windows, macOS, iPad, Android, and web** — one app across platforms [citation:8]. **Three workspaces**: Sketch, Paint, and Photo (wide-gamut HDR editing) [citation:8]. **Layers** with groups, masks, blend modes, and selection layers, plus **non-destructive effect chains** [citation:8]. **The honest caveat**: **in active development** — mobile stability and feature parity should be verified before relying on it for production work [citation:8]. **Best for artists** wanting a modern, GPU-native open-source alternative that runs across devices.

- **QuickEdit** — **The lightweight Android photo editor.** **Open-source (Apache-2.0), available on F-Droid** [citation:8]. **Cropping, drawing, text editing with formatting, GPUImage filters, and smooth Jetpack Compose animations** [citation:8]. **Quick saving and direct sharing** to social media [citation:8]. **Best for fast, simple photo enhancements** on any Android device without bloat [citation:8].

- **Drawpile** — **The collaborative art app that doubles as a photo editor.** **Open-source, available on Android via F-Droid**, with stylus pressure sensitivity [citation:10]. **Brushes for painting textures and colors**, selection tools (rectangle, ellipse, lasso, magic wand), layers, and **PSD import/export** [citation:10]. **The honest caveats**: **no HSL sliders or photo filters** — you work with layers, color options, and blend modes; **no version history** (non-destructive editing is limited) [citation:10]. **Best for users** wanting a lightweight drawing app with basic photo manipulation, especially for collaborative work [citation:10].

### Additional Strong Open-Source Options

- **Pocket Paint** — **Lightweight Android paint editor.** Open-source (Apache-2.0), on F-Droid, allowing parts of pictures to be set transparent and zooming to pixel level [citation:8]. Best for simple drawing and pixel-level transparency work.
- **Litrato** — **Android photo editing app with filters and tools.** Open-source (MIT), but **discontinued** — evaluate maintenance status before use [citation:8].
- **RapidRAW** — **GPU-accelerated RAW editor with Android support.** Open-source (AGPL-3.0), with AI-driven masking and 32-bit precision, though primarily desktop-focused with Android listed as a platform [citation:13]. Best for photographers needing RAW processing on mobile.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Mobile photo editing apps differ significantly in feature depth, privacy posture, and platform support. **Snapseed is no longer in active development** — its long-term availability is uncertain [citation:1]. **Image Toolbox is the most capable open-source Android editor** with batch processing and on-device AI background removal, but **it is a toolbox, not a gallery** — you browse tools rather than photos [citation:15]. **Fossify Gallery is privacy-first with no Internet permission**, but its editing is basic — no batch processing or background removal [citation:3][citation:9]. **Capy Canvas is in active development** — verify mobile stability before production use [citation:8]. **Drawpile lacks HSL sliders and version history**, making it a drawing app with basic photo manipulation rather than a full editor [citation:10]. **The choice often comes down to need**: comprehensive editing (Image Toolbox), private gallery (Fossify), or cross-platform painting (Capy Canvas).
- Self-hosted open-source solutions require proper app installation from F-Droid or GitHub releases, and awareness that mobile editors are limited by available RAM and screen size compared to desktop tools.

---

**Made for mobile photographers, casual editors, and developers choosing photo editing apps that respect their privacy and workflow.**
Let's make mobile photo editing more open, privacy-first, and offline-capable.
