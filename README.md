# Zyvro Browser Updates

This repository contains public release installers and an Ed25519-signed update
manifest for Zyvro Browser. It does not contain browser profiles, telemetry,
credentials, browsing activity, or the private source repository.

Zyvro checks `manifest.json` at most once every two days. It never installs or
restarts automatically; downloaded updates must pass both signature and SHA-256
verification.
