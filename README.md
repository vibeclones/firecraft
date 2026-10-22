# firecraft (Vibeclones mirror)

Hosted copies of the browser version of [FireCraft](https://github.com/aliasfoxkde/FireCraft), an open-source, clean-room reimplementation of Adobe Fireworks in pure Rust, from [aliasfoxkde](https://github.com/aliasfoxkde). The code is theirs; this repo only hosts it. The project's own web app is at https://firecraft-web.pages.dev, and it also ships desktop and command-line downloads.

- Latest: `/firecraft/latest/`
- A specific version: `/firecraft/v<version>/`, for example `/firecraft/v0.2.0/`
- Version list: `/firecraft/versions.json`

Each release publishes its finished web app as `firecraft-web-<version>.zip`, so each version here is that bundle unpacked. One change: the few root-absolute paths in it (the script and WebAssembly files in `index.html`, and the frame in `host.html`) are prefixed with the version's own folder so the app works from a subfolder. A scheduled workflow mirrors new releases.

**License:** FireCraft is MIT OR Apache-2.0. Every version folder includes both license files and a `SOURCE.txt` naming the release it came from. The full source for each version is at https://github.com/aliasfoxkde/FireCraft (tag `v<version>`).
