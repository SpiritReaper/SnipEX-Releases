# SnipEX Releases

This public repository is the official SnipEX update-feed and release-notes channel. The proprietary application source remains in a separate private repository and is not published here.

## Current stable release

SnipEX Version 2.0.12 Stable is the current employee-testing build. Use the guided `SnipEx-2.0.12-win-x64-Setup.exe` for normal installation. IT administrators may use the accompanying `.msi` for managed deployment. Matching SHA-256 checksum files are provided beside every package.

Version 2.0.12 uses the temporary GitHub collaborator gate: users sign in through GitHub and must be active collaborators on the private source repository. Microsoft company sign-in is not included. The installers remain unsigned while Club OS Tech review is pending.

Installed clients read the latest public GitHub Release and fall back to `manifest.json` for compatibility. On a fresh launch, SnipEX can checksum, install, and restart into a newer stable version directly from the client; users may disable automatic launch updates and retain manual update checks.

## Security

Only download SnipEX from the current release linked by this repository. Verify the matching SHA-256 checksum before installation. Published packages will be code-signed once an organization-approved certificate is available.
