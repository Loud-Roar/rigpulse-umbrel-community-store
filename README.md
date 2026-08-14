# RigPulse Umbrel Community App Store

This folder is ready to become a standalone Umbrel Community App Store repository.

Publishing order:

1. Push the main RigPulse source to `https://github.com/Loud-Roar/rigpulse`.
2. Let GitHub Actions publish `ghcr.io/loud-roar/rigpulse:0.3.8`.
3. Make the GHCR container package public.
4. Push this Community Store as a separate GitHub repository.
5. Add that Community Store repository URL in umbrelOS.

The Community Store ID is `rigpulse` and the app package ID is `rigpulse-monitor`.

The GHCR namespace is lowercase because OCI/Docker image repository names must be
lowercase; the GitHub account and links retain the account's `Loud-Roar` spelling.
