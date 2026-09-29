# Build commit manifest

This manifest records the exact upstream commits included in each published artifact release. This repository stores compiled artifacts only; upstream source and its Git history are not mirrored here.

## v0.1.0 — 2026-09-29

| Field | Value |
| --- | --- |
| Upstream repository | `MECCADEV/pingmessenger-platform` |
| Source revision | `bbfc9aabaa9f3733a5c0186beb29109fff0975be` |
| Target | Linux `amd64` |
| Build form | Static API and database-runner binaries, with migrations and seeds |

Included upstream commits, oldest first:

| Commit | Date | Subject |
| --- | --- | --- |
| `d9a06d4a7877264df66b9d0b7b09eca5ee46cf6b` | 2026-09-28 | Initial commit of the PingMessenger platform API. |
| `bbfc9aabaa9f3733a5c0186beb29109fff0975be` | 2026-09-28 | Run migrations through sqlmig. |

## Versioning policy

Each artifact publication receives a new `vMAJOR.MINOR.PATCH` heading. The corresponding table records the source revision, target platform, and all upstream commits included since the preceding build release.
