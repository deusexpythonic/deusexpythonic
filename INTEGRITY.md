# Integrity

This repository includes a manifest of SHA-256 checksums and a detached GPG signature.

**Files**
- MANIFEST.sha256 : list of files and their SHA-256 checksums
- MANIFEST.sha256.asc : detached ASCII-armored GPG signature of MANIFEST.sha256

**How to verify locally**
1. sha256sum -c MANIFEST.sha256
2. gpg --verify MANIFEST.sha256.asc MANIFEST.sha256

A successful verification shows OK for checksums and Good signature for GPG.
EOF

