# TURNSTILE Gateway

Tinfoil Container config for the repeatable TURNSTILE gateway demo deployment.

- Image: `ghcr.io/theforkproject-dev/strata-ebo-turnstile:tinfoil-demo-002@sha256:ad8ef20c233d7da49cc7cee81b337c8980dac6ea4b83bbbd5a45a6fa07e1d988`
- Endpoint target: `https://turnstile-gateway.amotivv.containers.tinfoil.dev`
- Config tag: `v0.1.0-tinfoil-demo.2`
- Demo reset: enabled at `POST /v1/demo/reset`

The measured TCB is the root `tinfoil-config.yml` in this repo at the tagged release.
