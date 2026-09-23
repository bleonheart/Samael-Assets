<p align="center">
 <strong>Samael Assets</strong><br/>
 A centralized asset library and browser for images, sounds, interface resources, and project media.<br/>
 Built for simple GitHub Pages hosting, direct-link sharing, and organized reuse across Garry's Mod and web projects.<br/>
</p>

<p align="center">
 <a href="https://bleonheart.github.io/Samael-Assets/">
  <img src="https://img.shields.io/badge/GitHub%20Pages-Open%20Asset%20Browser-blue?logo=github" alt="Open Asset Browser" />
 </a>
 <a href="https://github.com/bleonheart/Samael-Assets/stargazers">
  <img src="https://img.shields.io/github/stars/bleonheart/Samael-Assets?style=social" alt="GitHub Stars" />
 </a>
</p>

<h1 align="center">Samael Assets</h1>

---

## Asset Browser

<p align="center">
 Browse the repository through the hosted image and audio viewer:<br/>
 <a href="https://bleonheart.github.io/Samael-Assets/">https://bleonheart.github.io/Samael-Assets/</a>
</p>

The browser automatically discovers supported media from the repository and groups it by folder.

## Features

### Image Browser

- Automatically discovers repository images
- Groups assets by directory
- Thumbnail navigation
- Previous and next controls
- Automatic slideshow playback
- Configurable slideshow delay
- Keyboard navigation
- Fullscreen support
- Direct asset-link copying
- URL state for linking directly to a selected asset

Supported image formats include:

`png`, `jpg`, `jpeg`, `gif`, `webp`, `bmp`, and `svg`.

### Audio Browser

- Automatically discovers audio files
- Groups audio by directory
- Folder selector
- Play, pause, previous, and next controls
- Automatic playback progression
- Direct audio-link copying

Supported audio formats include:

`wav`, `mp3`, `ogg`, `flac`, `m4a`, `aac`, and `opus`.

## Asset Categories

The repository currently contains project assets organized into directories such as:

- `armor`
- `banking`
- `bonemerge`
- `computer`
- `cuffs`
- `dtcomms`
- `falloutrp`
- `identifications`
- `lockpicking`
- `medals`
- `misc`
- `music`
- `radio`
- `starwarsmenu`
- `status`
- `workshop`

## Direct Linking

Assets hosted through GitHub Pages can be referenced directly from other projects:

```text
https://bleonheart.github.io/Samael-Assets/<folder>/<asset>
```

Example:

```text
https://bleonheart.github.io/Samael-Assets/lilia.png
```

This makes the repository useful as a central source for README images, web interfaces, documentation, and other static resources.

## How It Works

The browser first looks for an optional `assets.json` manifest. If one is not available, it uses the GitHub repository tree API to discover supported image and audio files automatically.

The viewer can also be pointed at another compatible repository using URL parameters for the owner, repository, branch, and starting directory.

## Local Usage

Clone the repository:

```bash
git clone https://github.com/bleonheart/Samael-Assets.git
cd Samael-Assets
```

Serve the files with any static web server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Contributing

When adding assets:

1. Place files in the most appropriate category
2. Use descriptive filenames
3. Avoid unnecessary duplicates
4. Verify that the asset loads correctly in the browser
5. Open a pull request describing the assets being added
