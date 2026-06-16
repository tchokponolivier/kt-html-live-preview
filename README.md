# KT - Html Live Preview

An advanced live preview extension for VS Code with instant reload, SPA support, and modern development features.

## Features

### 🚀 Core Features

- **Live Reload**: Automatically reloads browser when files change
- **In-Editor Preview**: Side-by-side preview panel
- **SPA Support**: Works with React, Vue, and Angular apps
- **QR Code Generation**: Scan to preview on mobile devices
- **Multi-Browser Support**: Chrome, Firefox, Edge, Brave
- **HTTPS Support**: Self-signed SSL certificates

### 🎨 Framework Support

- React
- Vue.js
- Tailwind CSS
- Alpine.js

### 🔧 Advanced Features

- Auto-port detection
- File watcher with debouncing
- WebSocket-based live reload
- External network access
- Request logging
- Responsive viewport injection

## Usage

1. **Start Server**: Click the globe icon in status bar or run `KT Live Preview: Start Server`
2. **Show Preview**: Right-click HTML file → `KT Live Preview: Show Preview`
3. **Open in Browser**: Right-click HTML file → `KT Live Preview: Open in Browser`
4. **Generate QR Code**: Right-click HTML file → `KT Live Preview: Generate QR Code`

## Keyboard Shortcuts

- `Ctrl+Alt+V` - Show Preview
- `Ctrl+Alt+B` - Open in Browser

## Configuration

```json
{
  "ktHtmlLivePreview.port": 5500,
  "ktHtmlLivePreview.https": false,
  "ktHtmlLivePreview.autoReload": true,
  "ktHtmlLivePreview.externalUrls": false,
  "ktHtmlLivePreview.spaMode": false,
  "ktHtmlLivePreview.frameworks": ["react", "tailwind"]
}
```
