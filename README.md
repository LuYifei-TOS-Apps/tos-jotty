# Jotty for TOS 7

Jotty stores Markdown notes and checklists on the NAS. This package uses the upstream 1.30.0 image on x86_64 and aarch64.

Open Jotty from App Center or visit `http://NAS:19155`. Create the first administrator in the setup form before giving other users network access. Create a note or checklist to get started. Use a trusted network for local access and an authenticated TLS proxy for remote access.

Jotty runs as UID and GID 1000. The init service prepares its own app-data directories for documents, configuration and cache. Check the Docker Manager mounts at `/app/data`, `/app/config` and `/app/.next/cache`. Back up data and configuration before reinstalling or upgrading. Review app settings before creating links that share notes outside your account.

[Privacy policy](PRIVACY.md) · [Upstream project and license](https://github.com/fccview/jotty)
