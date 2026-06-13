# WHEP Player

A lightweight WebRTC WHEP stream tester & player. Runs entirely in a single HTML file — no build tools, no dependencies.

## Usage

Just open `index.html` in your browser:

```bash
open index.html
```

Or serve it locally:

```bash
python3 -m http.server 8080
# Then open http://localhost:8080
```

## Features

- Connect to any WHEP-compatible media server
- Real-time frame counter
- ICE connection state monitoring
- Timestamped console log
- Preset URLs for quick switching
- Basic Auth support

## License

MIT
