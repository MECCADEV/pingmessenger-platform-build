# PingMessenger Platform — Build Artifacts

This public repository distributes compiled PingMessenger Platform artifacts only. It intentionally contains no application source code, database scripts, or source history.

## Release v0.1.0

Linux `amd64` artifacts built from upstream source commit [`bbfc9aa`](BUILD_COMMITS.md#v010--2026-09-29):

- `bin/pingmessenger-api-linux-amd64` — API service
- `bin/pingmessenger-db-linux-amd64` — database migration and seed runner

Verify the binaries with:

```sh
sha256sum -c SHA256SUMS
```

Both executables are statically linked Linux `amd64` binaries. Copy them to a Linux host and set the production environment variables before starting the API or running database migrations. See the upstream project documentation for configuration and operational guidance.

The complete version-to-source mapping and included upstream commits are in [BUILD_COMMITS.md](BUILD_COMMITS.md).
