# Third-Party Notices

## Obsidian

This project downloads and runs [Obsidian](https://obsidian.md) at Docker
build time. Obsidian is proprietary software with its own license terms:

- **Personal use:** Free
- **Commercial use:** Requires a [commercial license](https://obsidian.md/pricing) from Obsidian
- **EULA:** <https://obsidian.md/eula>

The PolyForm Noncommercial license in this repository covers only the
Dockerfile, entrypoint script, CI configuration, and documentation — NOT
the Obsidian application itself. Obsidian's own license terms apply to
the Obsidian binaries contained in built Docker images.

## System Dependencies

The Docker image includes system libraries from Debian (bookworm-slim)
under their respective open source licenses (GPL, LGPL, MIT, BSD, X11).
These are runtime dependencies and are not relicensed by this project.
