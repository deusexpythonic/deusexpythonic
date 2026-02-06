# Signature

This repository is signed by the maintainer's GPG key.

**Key ID**
0BA9C8032CE7EFCDE148C2F93C3F87A1706A6726

**Verify signature**
1. Ensure the public key is available:
   gpg --list-keys --with-fingerprint 0BA9C8032CE7EFCDE148C2F93C3F87A1706A6726
2. Verify manifest signature:
   gpg --verify MANIFEST.sha256.asc MANIFEST.sha256
3. Verify file integrity:
   sha256sum -c MANIFEST.sha256

If verification fails, do not trust the repository until the discrepancy is resolved.
EOF
