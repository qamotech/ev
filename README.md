# 🏃🌆 Evony Runner: Apocalypse 2040

**Browser game export with WebAssembly and packaged game data, plus fullscreen, theater-mode, scanline, screenshot, and offline-support assets.**

🏷️ Maintained in [qamotech/ev](https://github.com/qamotech/ev) · 🌐 Public repository

## ✨ What is here

- 🎮 Exported game runtime and packaged data.
- 🖥️ Fullscreen, theater-mode, and scanline shell controls.
- 📸 Screenshot capture interface.
- 📦 Manifest, service worker, offline page, icons, and audio worklets.

## 🧭 Try the project

Serve the complete repository over HTTP, open index.html, allow the game assets to load, and test shell controls after the runtime starts.

## 🚀 Local setup

```sh
git clone https://github.com/qamotech/ev.git
cd ev
```

Use a current browser. Serve the repository root to preserve relative assets and a stable browser origin:

```sh
python -m http.server 8000
```

Open `http://localhost:8000/index.html`. Keep related assets beside the entry file. No npm setup is declared in the inspected repository.

## 🗂️ Source map

- 📄 [`Ev2040.audio.position.worklet.js`](Ev2040.audio.position.worklet.js)
- 📄 [`Ev2040.audio.worklet.js`](Ev2040.audio.worklet.js)
- 📄 [`Ev2040.js`](Ev2040.js)
- 📄 [`Ev2040.manifest.json`](Ev2040.manifest.json)
- 📄 [`Ev2040.offline.html`](Ev2040.offline.html)
- 📄 [`Ev2040.service.worker.js`](Ev2040.service.worker.js)
- 📄 [`index.html`](index.html)

## ⚙️ Configuration & data

Do not open the game through file://; the page itself warns about local-file restrictions. Keep .wasm, .pck, runtime scripts, and worker files together. Engine project source is not present in this export tree.

Keep credentials, private exports, customer records, and personal information out of commits and screenshots. A local browser demo is not evidence of account security, reliable persistence, or connected external services. Preserve exports before changing storage keys or resetting an application.

## 🧪 Verification checklist

- 🔎 Confirm the entry file and asset paths above exist in your checkout.
- ▶️ Start the documented runtime and inspect browser or terminal errors.
- 🧭 Exercise the project-specific workflow described above using sample data.
- 📱 Check narrow and wide layouts when the project has a browser interface.
- 💾 Verify save/export and recovery behavior before trusting important work to it.
- 📝 Record the exact command, browser, operating system, and outcome of your checks.

This guide was prepared from repository files and manifests. It does not claim a fresh build, deployment, security audit, or full functional test of this project.

## 🤝 Contributions & useful reports

Keep changes focused and explain the user-visible result. Preserve existing assets and configuration unless a change requires updating them. Include reproduction steps, expected and actual behavior, and relevant screenshots with personal information removed. For UI work, include the viewport and browser; for runtime issues, include the command and error text.

## 🛠️ Maintenance priorities

- 📚 Keep this guide aligned with implemented behavior and current entry points.
- 🧪 Add or maintain checks for the core workflow before expanding features.
- ♿ Review labels, keyboard navigation, contrast, and responsive layout.
- 📦 Document external services, asset rights, and deployment prerequisites.

## 📜 Licensing & attribution

This documentation update does not grant a new software or asset license. Consult existing license files, source headers, package metadata, and original asset terms; resolve inconsistencies with the owner before redistribution. Third-party names and resources retain their own terms.
