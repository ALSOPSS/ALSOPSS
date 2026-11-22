## Al's-Ops LLC

An independent software company in Utah, founded in 2023. We build privacy-first security and infrastructure software
for small teams that run their own servers.

**Tomorrow's Solutions, Built Today.**

### Open source

| Project | What it is |
|---|---|
| [spd-lib-ts](https://github.com/ALSOPSS/spd-lib-ts) | SPD (Secure Packaged Data): a post-quantum-hardened encrypted data format for Node.js, browsers, Deno and Bun. On npm as [`spd-lib`](https://www.npmjs.com/package/spd-lib). |
| [spd-lib-rs](https://github.com/ALSOPSS/spd-lib-rs) | The Rust implementation of SPD. Files, envelopes, signatures and shares open in both directions with the TypeScript library. |

SPD uses Argon2id for key derivation, XChaCha20-Poly1305 with key commitment for encryption, HMAC-SHA3-512 for
authentication, and NIST post-quantum algorithms for recipients and signatures. The full wire format is in
[SPEC.md](https://github.com/ALSOPSS/spd-lib-ts/blob/main/SPEC.md).

### Products

- **[Vigilhold](https://vigilhold.com)**: a host agent for Linux servers, including Docker hosts. It watches process,
  network, file and SSH activity and tells you in plain language what happened and why it matters.
  Try the [live lab](https://vigilhold.com/lab), no login needed.

### Free tools

- **[SSH config checker](https://alsopss.com/tools/ssh-config-checker)**: paste your `sshd_config` or `sudo sshd -T`
  output and get a plain-English list of what to fix. Runs in your browser; nothing is uploaded.

### Find us

[alsopss.com](https://alsopss.com) · [Blog](https://alsopss.com/blog) · [Bluesky](https://bsky.app/profile/als-ops.bsky.social) · [Mastodon](https://mastodon.social/@alsops) · [dev.to](https://dev.to/als-ops)

Sales: [sales@alsopss.com](mailto:sales@alsopss.com) · Vigilhold support: [support@vigilhold.com](mailto:support@vigilhold.com)
