# LightBites Server

LightBites Server is the self-hosted sync server for LightBites. It lets your devices share a photo library on a
computer, NAS, or server you control.

## Download

- **Docker (recommended):** [`elrumo/lightbites-server`](https://hub.docker.com/r/elrumo/lightbites-server) — the
  lightweight server and admin page image for `linux/amd64` and `linux/arm64`.
- **macOS, Linux, and Windows:** download the matching zip from
  [GitHub Releases](https://github.com/elrumo/lightbites-server/releases).

## Guides

Follow the [LightBites Server guides](https://lightbites.app/server) for Docker setup, HTTPS, first-run setup,
connecting the LightBites apps, backups, updates, and troubleshooting.

## Privacy

The server sends anonymous aggregate install and usage events, plus sanitized server error events, to the project's
Bugsink error tracker. Events contain the server version and aggregate counts of configured users and signed-in
devices; they do not include account or device names, photos, paths, or request contents. Bugsink can observe the
server's network address when it receives an event. Set `LIGHTBITES_TELEMETRY=0` to turn telemetry off. The server's
owner controls their data and can remove the `.lightbites-telemetry-installed` marker from the data directory to reset
the one-time install count.

## Source

The clean-room Rust implementation and issue tracker are in
[`elrumo/lightcraft`](https://github.com/elrumo/lightcraft/tree/main/apps/lightcraft-server). This repository
hosts the public downloads and release notes.

## License

MIT. See [LICENSE](LICENSE).
