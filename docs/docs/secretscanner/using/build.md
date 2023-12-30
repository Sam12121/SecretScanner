---
title: Build SecretScanner
---

# Build SecretScanner

SecretScanner is a self-contained docker-based tool. Clone the [SecretScanner repository](https://github.com/Sam12121/SecretScanner), then build:

```bash
./bootstrap.sh
docker build --rm=true --tag=toaeio/toae_secret_scanner:2.0.0 -f Dockerfile .
```

Alternatively, you can pull the official toae image at `toaeio/toae_secret_scanner:2.0.0`:

```bash
docker pull toaeio/toae_secret_scanner:2.0.0
```