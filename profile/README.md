<p align="center">
<img src="icon.svg" width="96" height="96" alt="Veilway">
</p>

<h1 align="center">Veilway</h1>

<p align="center">
An open-source VPN platform for networks that block or throttle ordinary VPNs:<br>
one core in Rust, a web panel and first-party clients.
</p>

<p align="center">
<a href="https://veilway-project.github.io/veilway-docs/">Documentation</a> | <a href="https://veilway-project.github.io/veilway-docs/fa/">مستندات فارسی</a>
</p>

## Status

Veilway is early software under active development and has had no outside security review. The tunnel encryption is WireGuard's, unchanged. Everything built around it to make the traffic harder to recognise is experimental, and the documentation says so wherever it applies. Do not rely on it where being detected has consequences.

## Repositories

| Repository | What it holds |
|---|---|
| [veilway](https://github.com/veilway-project/veilway) | The core, the control API and its TypeScript client, the command line tool and the desktop client |
| [veilway-docs](https://github.com/veilway-project/veilway-docs) | The documentation site, in English and Persian, including the draft protocol specification |

## Principles

- No invented cryptography. The tunnel is WireGuard.
- No telemetry, no accounts with the project, no ads.
- Honest labels: nothing is called safe that has not been tested, and every draft says it is a draft.
- Free and open under Apache-2.0: the core, the SDKs, every client and the panel.

## Security reports

Please report vulnerabilities in private, as [SECURITY.md](https://github.com/veilway-project/.github/blob/main/SECURITY.md) describes. Do not open a public issue for one.
