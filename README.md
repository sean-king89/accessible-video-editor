# Accessible Video Editor v0.1 - web video editor 2026

> **Accessible Video Editor is a browser-based MP4 editing tool built for keyboard-led workflows, WCAG-aware interaction, and fast selection-driven cuts in version 0.1.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v0.1-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/sean-king89/accessible-video-editor?style=flat-square)](https://github.com/sean-king89/accessible-video-editor)

---

<p align="center">
  <a href="https://sean-king89.github.io/accessible-video-editor/">
    <img src="https://img.shields.io/badge/Download-Accessible%20Video%20Editor%20Latest-brightgreen?style=for-the-badge" alt="Download Accessible Video Editor">
  </a>
</p>

> **[Direct Download - Accessible Video Editor v0.1](https://sean-king89.github.io/accessible-video-editor/)**

---

[Download Latest Build](https://sean-king89.github.io/accessible-video-editor/)

---

## What Accessible Video Editor Is

Accessible Video Editor provides a simple web editing surface for MP4 files, with an emphasis on selection, playback control, and easy-to-follow navigation. The interface is shaped around accessibility needs, so users who prefer the keyboard can work efficiently while benefiting from clear alerts and interaction patterns aligned with WCAG-informed design.

Rather than aiming at advanced production suites, the project focuses on the core job of reviewing and cutting video. You can load a clip, choose the section you want, trim or remove it, and export the result without leaving the browser. Timestamped alerts and visible playback controls make it useful for review-oriented work where status, feedback, and traceability matter.

---

## Highlights

- Open MP4 files and edit them directly in the browser
- Control playback with seek buttons for more exact positioning
- Create edit ranges using mark-based selection tools
- Trim, delete, and download the chosen segment
- Navigate the editor with keyboard shortcuts and accessible controls
- Inspect alert history with timestamps and downloadable logs
- Use theme and styling changes that prioritize accessibility
- Built on a web stack that includes Flask and HTML

---

## Getting Started

Clone the repository or download the source, then open the project in your local development environment.

```bash
git clone https://github.com/sean-king89/accessible-video-editor.git
cd REPO
```

If the project includes a Flask backend, launch it with your preferred Python entry point and open the app in a browser. For static or classroom-hosted builds, load the project files and open the supplied web page directly.

---

## How to Use It

1. Launch the app in a browser.
2. Upload an MP4 file.
3. Use playback controls and seek buttons to move through the video.
4. Place marks to define the portion you want to edit.
5. Trim or delete the selected range.
6. Download the finished selection when you are ready.
7. Review the alert history if you need a timestamped activity record.

Keyboard shortcuts are available for faster navigation where supported, especially when working without a mouse.

---

## Configuration Notes

Most settings are managed through the application UI and its web assets. If your build exposes server-side options, check the Flask configuration or any environment variables used by the project.

Example structure:

```ini
APP_ENV=development
DEBUG=true
```

Depending on the version you are using, accessibility-focused styling, theme selection, and interface behavior may also be adjusted in the HTML and CSS layer.

---

## Requirements

- A modern web browser
- MP4 input files for editing
- HTML-based frontend assets
- Flask if you are running the project with a Python-backed local server
- Enough local storage for uploaded media and exported selections

---

## FAQ

**How do I get the newest build?**  
Use the download link above, or pull the latest repository version when a new release is available.

**Where are alerts and action records kept?**  
The app includes alert history with timestamps. Depending on your build, those records may be visible in the interface and available to download.

**Is keyboard navigation supported across the editor?**  
Yes. Keyboard-friendly interaction is one of the main design goals of the interface.

**What should I check if the video does not load?**  
Confirm that the file is MP4, verify that your browser supports the format, and make sure the app can access the file or server location.

**Where do I change the visual style?**  
Check the interface settings or the project’s HTML and styling files, where accessibility-oriented theme updates are applied.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
