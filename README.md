# Kogitsune CA sitelist

`sitelist.json` is the feed format consumed by Kogitsune's scoped CA trust support. Keep the certificate SHA-256 fingerprint aligned with the PEM certificate. Each `hostnamePatterns` entry is a case-insensitive regular expression matched against the entire hostname.

The browser pins the expected CA fingerprint and refreshes this manifest daily after the user subscribes to the feed.
