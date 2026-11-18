# PWA Launcher

[![npm version](https://img.shields.io/npm/v/pwa-launcher.svg)](https://npmjs.org/package/pwa-launcher)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/yourname/pwa-launcher/actions)

Progressive Web App visual development and cross-platform publishing toolchain

## 🚀 Quick Start

```bash
npm install pwa-launcher
npx pwa-launcher init ./my-pwa
npx pwa-launcher build
```

## ✨ Features

- **Visual PWA Builder**: Drag-and-drop interface for PWA development
- **Multi-Platform Export**: Generate apps for iOS, Android, Windows, macOS
- **Offline First**: Automatic service worker and caching configuration
- **Installable**: One-click PWA installation with proper manifest
- **Cross-Browser Support**: Works on Chrome, Firefox, Safari, Edge

## 📦 CLI Usage

```bash
# Initialize new PWA project
npx pwa-launcher init my-pwa-app

# Build for web
npx pwa-launcher build --target web

# Build for mobile (iOS/Android)
npx pwa-launcher build --target ios
npx pwa-launcher build --target android

# Build for desktop (Windows/macOS)
npx pwa-launcher build --target windows
npx pwa-launcher build --target macos

# Test PWA features
npx pwa-launcher test

# Publish to distribution
npx pwa-launcher publish
```

## 🎯 Platform Capabilities

| Platform | Install Method | Features |
|----------|----------------|----------|
| Web | Browser Prompt | Push, Offline, Install |
| iOS | Share Menu | Web Clip, PWA |
| Android | Add to Home Screen | Full PWA, TWA |
| Windows | MSIX Package | Native Integration |
| macOS | WKWebView | Menu Bar, Touch Bar |

## 📊 PWA Features

- ✅ Progressive enhancement from first visit
- ✅ Installable with custom splash screens
- ✅ Offline support with intelligent caching
- ✅ Push notifications integration
- ✅ Web Share Target API
- ✅ File Handling API (Chromium browsers)

## 🛠️ Architecture

```
┌─────────────────┐
│  Visual Builder │
│  (Drag & Drop)  │
└─────────────────┘
         │
         ▼
┌─────────────────┐
│  PWA Generator  │
│  - Manifest     │
│  - Service Wk   │
│  - Icons        │
└─────────────────┘
         │
         ▼
┌─────────────────┐
│  Platform Pack  │
│  - Web          │
│  - iOS          │
│  - Android      │
│  - Desktop      │
└─────────────────┘
```

## 📈 Performance

- **Build Time**: < 5 seconds
- **Bundle Size**: Optimized for mobile networks
- **Offline Cache**: Automatic resource caching
- **Lighthouse Score**: Target 90+ on all categories

## 📖 Documentation

- [Getting Started Guide](docs/getting-started.md)
- [Platform Guides](docs/platforms/)
- [PWA Best Practices](docs/best-practices.md)
- [API Reference](docs/api-reference.md)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Run tests: `npm test`
4. Submit a pull request

## 📄 License

MIT © 2026 PWA Launcher Contributors

---

**Ready to build your next PWA? Start with PWA Launcher!**