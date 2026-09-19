# DOKIII

DOKIII is a sleek macOS-inspired desktop dock and active widget system for Windows.

## Features

- macOS-style animated dock with fluid magnification
- DOKIII Halo desktop status bar and media overlay
- Customizable desktop widgets (World Clock, Analog Clock, Calendar, System Monitor, Battery, System Controls)
- Windows Global System Media Transport Controls (GSMTC) integration
- Ultra-low idle resource consumption (~1-2% idle CPU)
- Multi-orientation dock placement (Bottom, Left, Right)
- Silent startup mode for Windows boot

## Installation & Releases

Download the latest packaged Windows release (`DOKIII-v*.zip` or `DOKIII.exe`) from the Releases page.

Extract and run `DOKIII.exe`.

## Development

Prerequisites:
- Node.js 18 or later
- npm
- Windows 10/11

Clone and install:
```bash
git clone https://github.com/fluxonbuzz/dokiii.git
cd dokiii
npm install
```

Development server:
```bash
npm run dev
```

Typecheck:
```bash
npm run typecheck
```

Build:
```bash
npm run build
```

Package Windows executable:
```bash
npm run pack
```

## License

MIT
