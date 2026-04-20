# functions.io

Modern solutions for an evolving technology landscape.

## Overview

functions.io is a technology consulting firm based in Utah, USA. We specialize in technology consulting, systems integration, and software development.

This repository contains the source code for the functions.io website and an experimental dashboard for media processing.

## Project Structure

- `index.html`: The main landing page for functions.io.
- `css/`: Custom styles and Bootstrap overrides.
- `images/`: Brand assets and photography used across the site.
- `dashboard/stream/`: A suite of browser-based media tools, including:
  - Video transcoding (using ffmpeg.wasm)
  - Image optimization (using wasm-imagemagick)
  - Real-time video calling (using PeerJS)

## Local Development

You can serve the website locally for development and verification using any static file server. For example, using Python:

```bash
python3 -m http.server 8000
```

Once the server is running, navigate to `http://localhost:8000` in your browser.

## Technologies Used

- **Frontend**: Bootstrap 4 & 5, jQuery
- **Media Processing**: [ffmpeg.wasm](https://github.com/ffmpegwasm/ffmpeg.wasm), [wasm-imagemagick](https://github.com/KnicKnic/Wasm-ImageMagick)
- **Networking**: [PeerJS](https://peerjs.com/)
