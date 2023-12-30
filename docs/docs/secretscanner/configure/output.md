---
title: Configure Output
---

# Configure Output

SecretScanner can writes output to `stdout` it can redirected to a file for further analysis.

```bash
# Write output to ./tmp/node-secret-scan.json

docker run -it --rm --name=toae_secret_scanner \
    -v /var/run/docker.sock:/var/run/docker.sock \
    toaeio/toae_secret_scanner:2.0.0 \
    --image-name node:latest \
# highlight-next-line
    --output json > ./tmp/node-secret-scan.json
```

