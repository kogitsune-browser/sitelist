# Kogitsune CA sitelist

`sitelist.json` is the feed format consumed by Kogitsune's scoped CA trust support. Keep the certificate SHA-256 fingerprint aligned with the PEM certificate. `hostnames` contains exact DNS names; `hostnamePatterns` contains optional case-insensitive regular expressions matched against the entire hostname. A site is permitted when it matches either list.

The browser pins the expected CA fingerprint and refreshes this manifest daily after the user subscribes to the feed.
