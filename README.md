# AppADay 052 — QR Forge

**Category:** Utility (U)
**Published:** 2026-06-27
**Live URL:** https://augustineiacopelli.github.io/appaday-052-qr-forge/

## What It Does

QR Forge generates a scannable QR code from any URL or text you type. The preview updates live as you type, and you can download the result as a PNG with a single tap. Foreground and background colors are customizable, and three size presets (S / M / L) let you dial in the right resolution for print or screen use.

## Features

- Live QR preview with 300ms debounce — no button required
- Three size presets: 128px (S), 200px (M), 280px (L)
- Foreground and background color pickers for custom-branded codes
- Download as PNG with an auto-generated filename based on the input text
- Character limit guard — warns before hitting the QR data ceiling (2,953 chars)
- Fully offline after initial load — no server, no account, no tracking

## Stack

Single-file vanilla HTML/CSS/JS. Uses [qrcodejs](https://github.com/davidshimjs/qrcodejs) via cdnjs for QR encoding and canvas rendering. No build step. GitHub Pages deployable.

## AppADay

Part of the [AppADay](https://augustineiacopelli.github.io/appaday/) project — one complete web app built and shipped every day.
