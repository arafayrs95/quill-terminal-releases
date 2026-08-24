# Security policy

## Reporting a vulnerability

Do not open a public issue for a suspected vulnerability. Email
**support@quillterminal.app** with the subject **Security report** and include:

- the affected Quill Terminal version and operating system;
- clear reproduction steps and the expected/actual behavior;
- the practical impact;
- logs or screenshots with license keys, API keys, prompts, paths, email
  addresses, and other private data removed.

You will receive an acknowledgement as soon as practical. Please allow time to
investigate and prepare a coordinated fix before publishing details.

## Release verification

Official binaries are linked from <https://quillterminal.app/download>. Public
release notes also live at
<https://github.com/arafayrs95/quill-terminal-releases/releases>. Each release
includes SHA-256 checksums, a Sigstore bundle, and a CycloneDX SBOM. Follow the
website documentation to verify a download before running it.

The initial demand-validation macOS and Windows packages are unsigned. Treat
an unexpected filename, digest mismatch, different download host, or missing
release evidence as suspicious and contact support.
